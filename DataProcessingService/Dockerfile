FROM python:3
LABEL MAINTAINER="Arturo Gonzalez"

WORKDIR /app
ADD app.py /app

RUN pip install flask requests
EXPOSE 3000

CMD ["python", "app.py"]
