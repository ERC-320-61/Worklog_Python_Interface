FROM python:3.8

RUN pip install pipenv

ENV PROJECT_DIR /home/ericd/Documents/Code/ActualCode

WORKDIR ${PROJECT_DIR}

COPY Pipfile Pipfile.lock ${PROJECT_DIR}/

RUN pipenv install --system --deploy

