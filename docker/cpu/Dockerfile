FROM python:3.11.9

COPY dist/*.whl /

RUN pip install /*.whl && rm /*.whl

WORKDIR /workspace
