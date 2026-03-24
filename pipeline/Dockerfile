FROM python:3.12.0-slim

WORKDIR /app

COPY pipeline.py .

RUN pip install pandas pyarrow

ENTRYPOINT [ "python", "pipeline.py" ]