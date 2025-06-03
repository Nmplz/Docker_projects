FROM python:3.12-slim
RUN groupadd -r groupflask && useradd -r -g groupflask userflask
RUN pip install --upgrade pip
RUN pip install flask
WORKDIR /app
COPY ./flaskprj .
EXPOSE 4000
USER userflask
CMD ["python","site.py"]