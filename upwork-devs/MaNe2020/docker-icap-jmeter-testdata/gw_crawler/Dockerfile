FROM python:3.6
RUN mkdir /malicious_file_crawler

COPY malicious_file_crawler /malicious_file_crawler

WORKDIR /malicious_file_crawler

RUN pip install -r requirements.txt

CMD [ "python", "-m", "src.glasswall_crawler_runner","DASMAL" ]
