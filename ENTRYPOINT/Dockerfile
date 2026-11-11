FROM almalinux:9
#CMD ["ping", "google.com"]
#ENTRYPOINT ["ping", "google.com"]

CMD ["google.com"] #override input and output values
ENTRYPOINT ["ping"] # standary values



[ec2-user@ip-172-31-24-94 ENTRYPOINT]$ docker run entry:1.0.2 facebook.com
PING facebook.com (57.144.74.1) 56(84) bytes of data.
64 bytes from edge-star-mini-shv-02-iad3.facebook.com (57.144.74.1): icmp_seq=1 ttl=54 time=0.923 ms
64 bytes from edge-star-mini-shv-02-iad3.facebook.com (57.144.74.1): icmp_seq=2 ttl=54 time=0.993 ms
64 bytes from edge-star-mini-shv-02-iad3.facebook.com (57.144.74.1): icmp_seq=3 ttl=54 time=0.953 ms
64 bytes from edge-star-mini-shv-02-iad3.facebook.com (57.144.74.1): icmp_seq=4 ttl=54 time=0.985 ms
64 bytes from edge-star-mini-shv-02-iad3.facebook.com (57.144.74.1): icmp_seq=5 ttl=54 time=1.06 ms
64 bytes from edge-star-mini-shv-02-iad3.facebook.com (57.144.74.1): icmp_seq=6 ttl=54 time=0.943 ms
^C
--- facebook.com ping statistics ---
6 packets transmitted, 6 received, 0% packet loss, time 5007ms
rtt min/avg/max/mdev = 0.923/0.976/1.061/0.044 ms
[ec2-user@ip-172-31-24-94 ENTRYPOINT]$
