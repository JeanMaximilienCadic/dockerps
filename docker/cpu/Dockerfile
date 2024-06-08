FROM python:3.13.0b2

COPY dist/*.whl /

RUN pip install /*.whl && rm /*.whl

WORKDIR /workspace
