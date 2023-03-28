#base Docker image that we will build on
FROM python:3.9.1


RUN pip install pandas

WORKDIR /app

COPY pipeline.py pipeline.py


#define what to do first when the container runs
# for this, we will just run the script

ENTRYPOINT ["python", "pipeline.py"]
