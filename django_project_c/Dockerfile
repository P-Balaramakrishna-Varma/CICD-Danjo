FROM python:3.8-slim-buster

WORKDIR /code
COPY requirements.txt /code/
RUN /usr/local/bin/python -m pip install --upgrade pip
RUN pip3 install -r requirements.txt
COPY . .

CMD ["python3", "manage.py", "runserver"]