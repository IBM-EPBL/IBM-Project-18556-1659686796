  FROM python:2.7
  LABEL maintainer="mukesh, sit19cs034@sairamtap.edu.in"
  RUN apt-get update
  RUN mkdir /app
  WORKDIR /app
  COPY . /app
  RUN pip install flask
  EXPOSE 5000
  ENTRYPOINT [ "python" ]
  CMD [ "app.py" ]
