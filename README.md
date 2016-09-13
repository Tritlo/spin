Spin
=======


The spin model checker installed in a docker container. Version is configureable, but by default it is `6.4.5`.
To run, use


    $ docker run -v $(pwd):/data -it --name spin --rm tritlo/spin --
