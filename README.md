docker-coldfusion2016
===================

ColdFusion 2016 as Docker image on Ubuntu 12.04.

Place coldfusion binary in ./build/install/

Then run

    ./prepare.sh

Then build the Docker container:

    docker build -t cf2016 .

And run it with:

    docker run -d  -p 443:443 cf2016
