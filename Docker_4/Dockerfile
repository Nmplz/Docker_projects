FROM python:3.12-slim
RUN pip install --upgrade pip
RUN pip install flask
WORKDIR /app
COPY ./flaskprj .
CMD ["python","site.py"]