FROM python:3.9
RUN pip install pandas
#RUN pip install polars

#Directory in which image will be working out of
WORKDIR /app

# Copying from local machine to docker image
# COPY local_name docker_name
COPY pipeline.py pipeline.py

ENTRYPOINT [ "python", "pipeline.py" ]