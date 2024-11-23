FROM python:3

COPY requirements.txt .
RUN python -m pip install -r requirements.txt

WORKDIR /apuri
COPY . /apuri

CMD ["python", "main.py"]