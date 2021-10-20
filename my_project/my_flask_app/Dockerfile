FROM python:3.9


WORKDIR /my_flask_app

COPY . .

RUN pip install --upgrade pip && pip install -r requirements.txt
ENTRYPOINT ['python']

CMD ['app.py']