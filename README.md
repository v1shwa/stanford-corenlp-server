# Standford Corenlp Server    [![Build Status](https://travis-ci.org/v1shwa/stanford-corenlp-server.svg?branch=master)](https://travis-ci.org/v1shwa/stanford-corenlp-server)    [![Docker Automated buil](https://img.shields.io/docker/automated/v1shwa/ml-devkit.svg)](https://hub.docker.com/r/v1shwa/stanford-corenlp-server)
Docker image for Stanford corenlp server

## Installation
  - Pull Image
   
        docker pull v1shwa/standord-corenlp-server    
  - Launch a jupyter notebook in detached mode
  
        docker run -p 9000:9000 --name corenlp-server -d v1shwa/standord-corenlp-server
    
    You can now access the Corenlp server at [localhost:9000](http://localhost:9000/)

## API Usage
  Follow the instructions here on [Corenlp documentation](https://stanfordnlp.github.io/CoreNLP/corenlp-server.html#api-documentation)

## License
[The MIT License](./LICENSE)

