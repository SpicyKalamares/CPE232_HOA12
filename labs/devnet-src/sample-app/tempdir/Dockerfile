FROM python
RUN pip install flask
COPY ./static /home/myapp/static/
COPY ./templates /home/myapp/templates/
COPY sample_app.py /home/myapp/sample_app.py
EXPOSE 8080
CMD python3 /home/myapp/sample_app.py
