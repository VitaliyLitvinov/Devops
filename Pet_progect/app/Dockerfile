FROM python:3.13.3-slim
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt
COPY web_application.py .
EXPOSE 8000
ENV AUTHOR="USER"
ENTRYPOINT ["python"]
CMD ["web_application.py"]