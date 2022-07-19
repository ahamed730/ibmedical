FROM python:3.8
WORKDIR /code
COPY . /code
RUN chmod +x /code
RUN pip3 install --upgrade pip
RUN pip3 install -r requirements.txt
ENV PYTHONUNBUFFERED 1 
ENV PYTHONDONTWRITEBYTECODE 1
EXPOSE 8000
CMD python3 manage.py runserver 0.0.0.0:8000
USER 1001