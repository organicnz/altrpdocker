FROM litespeedtech/openlitespeed
RUN cd ~ && curl -sL https://deb.nodesource.com/setup_14.x -o nodesource_setup.sh &&  bash nodesource_setup.sh &&  bash nodesource_setup.sh && apt install nodejs && apt install iputils-ping
RUN apt update && apt install net-tools && apt install nano