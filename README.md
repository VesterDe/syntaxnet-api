Dockerized SyntaxNet API for Slovenian
=======================================

__NOTE__: this is a fork from [https://github.com/davidsbatista/syntaxnet-api](https://github.com/davidsbatista/syntaxnet-api) who edited the upstream to only server 1 language for performance reasons. It's Portuguese there, and I just changed it to Slovenian.

Install

    git clone https://github.com/VesterDe/syntaxnet-api
    cd syntaxnet-api
    docker build . -t syntaxnet-api
    
Run a docker Container with the built image

    docker run -p 7000:7000 IMAGE_ID

Blog post explaining what the original author did, for context: http://www.davidsbatista.net/blog/2017/07/22/SyntaxNet-API-Portuguese/
