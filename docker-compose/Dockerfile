FROM ubuntu:latest
LABEL authors="conwaymc"
#requires the NANOBOT_DIR env variable(set to the top level of ehlc-curation, e.g. export NANOBOT_DIR=`pwd`)
RUN apt-get update
#RUN apt-get install -y git curl
#RUN git clone https://github.com/NIEHS/ehlc-curation.git
WORKDIR /ehlc-curation
#RUN curl -L -o nanobot https://github.com/ontodev/nanobot.rs/releases/download/v2024-07-31/nanobot-v20240731-x86_64-linux
#RUN chmod +x nanobot
#CMD ["tail", "-f", "/dev/null"]
CMD ["./docker-compose/nanobot", "serve", "--connection", ":memory:"]