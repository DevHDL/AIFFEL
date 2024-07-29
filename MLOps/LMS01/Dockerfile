# python 3.9
FROM amd64/python:3.9-slim

# linux update
# install postgresql
RUN apt-get update && apt-get install -y \

    postgresql-client \
    && rm -rf /var/lib/apt/lists/*

WORKDIR /usr/app

# pip install scikit-learn pandas psycopg2-binary
RUN pip install -U pip &&\

    pip install scikit-learn pandas psycopg2-binary

# copy data_generator.py
COPY data_generator.py data_generator.py

# command
ENTRYPOINT ["python", "data_generator.py", "--db-host"]
# Change CMD to solve host finding error
CMD ["localhost"]
