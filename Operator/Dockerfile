FROM python:latest
RUN pip install requests
COPY config_operator.py /config_operator.py
ENTRYPOINT [ "python", "/config_operator.py" ]

