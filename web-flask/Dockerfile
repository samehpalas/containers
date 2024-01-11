FROM     python:3.6.5-alpine
WORKDIR  project
COPY     app.py install.txt   /project
RUN      apk update && apk upgrade
RUN      pip install -r install.txt
EXPOSE   5000
CMD      python app.py
