FROM python:3.8
LABEL maintaner="Hossam Mostafa"

ADD ./project/techtrends /app
WORKDIR /app
EXPOSE 3111

RUN pip install -r requirements.txt
RUN python init_db.py
CMD [ "python", "app.py" ]