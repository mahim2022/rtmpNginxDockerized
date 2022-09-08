FROM node
WORKDIR /usr/src/app
COPY . /usr/src/app
# RUN apt-get -y update
# RUN apt-get -y upgrade
# RUN apt-get install -y ffmpeg
RUN npm install
CMD ["npm","start"]
EXPOSE 8000
# EXPOSE 1935