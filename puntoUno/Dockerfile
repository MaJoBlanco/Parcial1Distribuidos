FROM python:3.9
WORKDIR /app
RUN apt install curl
COPY mensaje.txt .
COPY . .
CMD ["python","mensaje.txt"]
