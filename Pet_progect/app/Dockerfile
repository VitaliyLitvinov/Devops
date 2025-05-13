FROM python:3.13.3-slim
COPY requirements.txt ./app
RUN pip install --no-cache-dir -r requirements.txt
WORKDIR ./app
COPY web_aplication.py .
EXPOSE 8000
ENV AUTHOR="USER"
ENTRYPOINT ["python"]
CMD ["web_application.py"]