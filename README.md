Dockerized SyntaxNet API for Portuguese
=======================================

__NOTE__: this is a fork from [https://github.com/danielperezr88/syntaxnet-api](https://github.com/danielperezr88/syntaxnet-api) which I changed to work for Portuguese only, it saves much memory, since it loads only the Portuguese model.

Install

    git clone https://github.com/davidsbatista/syntaxnet-api
    cd syntaxnet-api
    docker build . -t syntaxnet-api
    
Run a docker Container with the built image

    docker run -p 7000:7000 IMAGE_ID

Blog post explaining what I did: http://www.davidsbatista.net/blog/2017/07/22/SyntaxNet-API-Portuguese/
