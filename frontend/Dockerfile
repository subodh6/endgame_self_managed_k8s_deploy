#FROM python:3.6-slim
FROM 954503069243.dkr.ecr.us-east-1.amazonaws.com/subodhpythonv:latest
WORKDIR /app
COPY . /app
RUN pip3 install -r requirements.txt
EXPOSE 5000
CMD ["python3","app.py"]
