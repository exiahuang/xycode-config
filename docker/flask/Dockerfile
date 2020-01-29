FROM python:rc-alpine3.10

ARG project_dir=/app/

ADD app/requirements.txt $project_dir

WORKDIR $project_dir

RUN pip install -r requirements.txt