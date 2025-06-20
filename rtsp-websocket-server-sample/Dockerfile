FROM java:8
RUN ln -sf /usr/share/zoneinfo/Asia/Shanghai /etc/localtime && echo 'Asia/Shanghai' > /etc/timezone
COPY rtsp-websocket-server.jar /home/rtsp-websocket-server/

ENTRYPOINT ["java","-jar","/home/rtsp-websocket-server/rtsp-websocket-server.jar"]
