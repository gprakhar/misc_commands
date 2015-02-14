############################################################
# Dockerfile to build Bowtie2 container images
# Based on Ubuntu 14.04
############################################################

# Set the base image to Ubuntu
FROM ubuntu:14.04

# Set noninterative mode
ENV DEBIAN_FRONTEND noninteractive

################## BEGIN INSTALLATION ######################

RUN apt-get update 
#RUN apt-get upgrade -y


# Install Bowtie2 toolkit
RUN apt-get install bowtie2 -y

##################### INSTALLATION END #####################

# Set entrypoint for bwa execution
ENTRYPOINT bowtie2

# File Author / Maintainer
MAINTAINER Felipe da Veiga Leprevost <felipe@leprevost.com.br>
