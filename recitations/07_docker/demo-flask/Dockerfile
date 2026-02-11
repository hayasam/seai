FROM python:3.14.3
COPY . /
WORKDIR /
RUN pip install --upgrade pip
RUN pip install -e .
RUN pip install -r requirements.txt
EXPOSE 8082
ENTRYPOINT [ "python" ]
CMD [ "app/server.py" ]