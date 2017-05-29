# Standford Corenlp Server
Docker image for Stanford corenlp server

## Installation
  - Pull Image
   
        docker pull v1shwa/standord-corenlp-server    
  - Launch a jupyter notebook in detached mode
  
        docker run -p 9000:9000 --name corenlp-server -d v1shwa/standord-corenlp-server
    
    You can now access the Corenlp server at [localhost:9999](http://localhost:9999/)

## API Usage
  Follow the instructions here on [Corenlp documentation](https://stanfordnlp.github.io/CoreNLP/corenlp-server.html#api-documentation)

## License
[The MIT License](https://github.com/v1shwa/standford-corenlp-server/blob/master/LICENSE)

