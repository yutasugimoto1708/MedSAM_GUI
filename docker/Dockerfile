FROM nvcr.io/nvidia/pytorch:23.06-py3

RUN pip install --upgrade pip

COPY requirements.txt ./

RUN pip install --no-cache-dir -r requirements.txt

RUN apt update && apt -y install git
