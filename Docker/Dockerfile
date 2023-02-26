# Ubuntu 16.04 as the base image
FROM ubuntu:16.04

# Update package lists and install ping utility

RUN apt-get update && apt-get install -y iputils-ping

# Set default target for the container

CMD ["ping", "google.com"]



# after writing dockerfile, we need to build and run this

# sudo docker build -t ubuntuimage .

# sudo docker run ubuntuimage

# output on the terminal is 

    # PING google.com (142.250.193.46) 56(84) bytes of data.
    #64 bytes from del11s15-in-f14.1e100.net (142.250.193.46): icmp_seq=1 ttl=119 time=4.57 ms