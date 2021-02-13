#FROM python:3.8.0-alpine3.10
FROM python:3.8

RUN pip3 install numpy
RUN mkdir -p /workfloder
COPY ./main.py /workfloder/

CMD ["python","/workfloder/main.py"]