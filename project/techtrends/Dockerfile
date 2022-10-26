FROM python:3.8

EXPOSE 3111/tcp
COPY . /app
WORKDIR /app
RUN python -m pip install -r requirements.txt && python init_db.py

CMD [ "python", "app.py" ]