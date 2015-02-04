# Start with a standard Docker Java image and install tesseract and imagemagick.
# This image is based on Ubuntu, so we can use apt-get.

FROM dockerfile/java:oracle-java8
MAINTAINER Alex Johnson <alex@colorandlogic.com>

# Install the Tesseract binaries
RUN apt-get update && apt-get -y install \
    tesseract-ocr \
    imagemagick