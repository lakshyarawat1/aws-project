FROM python:3.10-slim-buster

WORKDIR /backend-flask

COPY requirements.txt requirements.txt

RUN pip3 install -r requirements.txt

COPY . .

ENV FLASK_ENV=development

EXPOSE 8001

CMD [ "python",  "-m", "flask", "run", "--host=0.0.0.0", "--port=8001" ]