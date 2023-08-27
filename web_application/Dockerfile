FROM python:3.7
ENV PIP_ROOT_USER_ACTION=ignore
RUN pip3 install --upgrade pip
RUN mkdir /web_application
WORKDIR /web_application
COPY ./ /web_application
RUN pip3 install -r requirements.txt