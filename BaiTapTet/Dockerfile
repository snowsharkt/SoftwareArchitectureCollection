FROM alpine:latest

RUN apk add --no-cache xvfb x11vnc xfce4 openssl bash sudo

RUN adduser -D -s /bin/bash snow && echo "snow:testvnc" | chpasswd
USER snow

RUN mkdir -p /home/snow/.vnc && x11vnc --storepasswd testvnc /home/snow/.vnc/passwd

ENV DISPLAY :99 
ENV RESOLUTION 1920x1080x24

COPY entry.sh /

CMD ["/entry.sh"]