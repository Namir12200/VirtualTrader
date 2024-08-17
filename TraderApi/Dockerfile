FROM python:3.12.5-alpine3.20

ENV PYTHONWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1

RUN pip install --upgrade pip

WORKDIR /backend

COPY ./requirements.txt /backend/requirements.txt

RUN pip install -r requirements.txt

COPY . /backend/

CMD [ "python", "manage.py", "runserver", "0.0.0.0:8000" ]