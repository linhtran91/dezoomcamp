FROM python:3.9

RUN pip install pandas
RUN pip install notebook

WORKDIR /app
COPY pipeline.py pipeline.py

# ENTRYPOINT ["python", "pipeline.py"]
ENTRYPOINT ["bash"]