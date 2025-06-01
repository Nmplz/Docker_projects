FROM python:3.12-alpine
ENV PYTHONUNBUFFERED=1
RUN pip install --upgrade pip
RUN pip install --no-cache-dir numpy
WORKDIR /python-app
COPY . .
CMD [ "python", "main.py" ]