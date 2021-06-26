FROM continuumio/anaconda3:4.4.0
COPY . /usr/app
EXPOSE 5000
WORKDIR /usr/app
RUN pip install --upgrade pip
RUN pip install -r requirements.txt
ADD . /usr/app
ADD . . 
CMD python flask_api_swaggar.py