# Start with a standard Docker Java image and install tesseract.
# This image is based on Ubuntu, so we can use apt-get.

FROM dockerfile/java:oracle-java8
MAINTAINER Alex Johnson <alex@colorandlogic.com>

RUN apt-get -qq update
RUN apt-get -qqy install tesseract-ocr