FROM ubuntu
MAINTAINER Soumyadeep.paul
RUN sudo apt-get -y update && \
echo '#!/bin/bash' > /script.sh && \
echo 'while true; do echo "running"  ; sleep 2; done' >> /script.sh  && \
chmod +x /script.sh \
CMD ["/script.sh"]
