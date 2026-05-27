FROM python:3.13-slim

COPY requirements.txt /tmp/dbt-requirements.txt
RUN pip install --no-cache-dir -r /tmp/dbt-requirements.txt

WORKDIR /app/medical_pipeline
CMD ["dbt", "--version"]
