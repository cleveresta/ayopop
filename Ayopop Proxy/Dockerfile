FROM python:3.9-slim
ADD ayopop-proxy /run
WORKDIR /run
COPY ayopop-proxy/requirements.txt .
RUN pip install -r requirements.txt
EXPOSE 8080
CMD ["python", "handler.py"]