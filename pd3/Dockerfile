FROM python:3.8

WORKDIR /app/pd3

COPY . /app/pd3

COPY requirements.txt /app/pd3
RUN pip install -r requirements.txt

CMD ["python", "application.py"]