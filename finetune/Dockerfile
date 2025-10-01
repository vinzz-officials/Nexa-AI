FROM pytorch/pytorch:2.1-cuda11.8-cudnn8-runtime
WORKDIR /app
COPY requirements.txt ./
RUN pip install --upgrade pip && pip install -r requirements.txt
COPY . /app
