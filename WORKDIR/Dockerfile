FROM almalinux:9
RUN mkdir /tmp/work-dir-demo
WORKDIR /tmp/work-dir-demo
RUN pwd
RUN echo "Hello from WORK DIR" > hello.txt
CMD ["sleep", "100"]

$ docker build -t work:1.0.0 .

[ec2-user@ip-172-31-24-94 WORKDIR]$ docker run -d --name work work:1.0.0

[ec2-user@ip-172-31-24-94 WORKDIR]$ docker run -d --name work work:1.0.1
28e5e8018cc3d1eac684ed5dae6859e4d0f34b7a688f8c09d3766f1f4be90248

[ec2-user@ip-172-31-24-94 WORKDIR]$ docker exec -it work bash
[root@28e5e8018cc3 work-dir-demo]# pwd
/tmp/work-dir-demo
[root@28e5e8018cc3 work-dir-demo]# ls -ltr
total 4
-rw-r--r--. 1 root root 20 Nov 11 10:43 hello.txt

[root@28e5e8018cc3 work-dir-demo]#

