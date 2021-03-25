FROM python:3

WORKDIR /usr/src/app

COPY requirements.txt ./
RUN pip install --no-cache-dir -r requirements.txt
RUN pip install uwsgi

COPY flask_restful_app.py .
COPY wsgi.ini .

CMD ["uwsgi", "wsgi.ini"]
