FROM python:3.10
RUN apt-get update && apt-get install -y gettext
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone
COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt
