FROM nextcloud:fpm

RUN apt-get update && apt-get upgrade -y

# Needed for images, videos and pdfs previews
RUN apt-get install -y ffmpeg imagemagick ghostscript

# Clean-up
RUN apt-get autoremove -y && rm -rf /var/lib/apt /var/cache/apt
