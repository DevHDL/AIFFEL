# tiangolo/uvicorn-gunicorn-fastapi
FROM tiangolo/uvicorn-gunicorn-fastapi:python3.9-slim AS builder

# setting workdir and copy this dir to /app
WORKDIR /app

# copy requirement.txt to workdir
COPY requirements.txt ./

# buildkit 의 cache mount 사용 및 pip install
RUN --mount=type=cache,target=/root/.cache/pip \
    pip install -r requirements.txt

COPY ./app ./app

FROM builder AS dev-envs

# apk update & install git
RUN <<EOF
apt-get update
apt-get install -y --no-install-recommends git
EOF

# new user setting(vscode) & new group setting(docker)
# vscode user in docker group
RUN <<EOF
useradd -s /bin/bash -m vscode
groupadd docker
usermod -aG docker vscode
EOF

# copy cloursdocker/docker image to this image's root dir
# install Docker CLI, buildx, compose, etc
COPY --from=gloursdocker/docker / /

