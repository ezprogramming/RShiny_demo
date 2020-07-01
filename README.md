This is a quick demo for RShiny.

The Data comes from Kaggle and the Shiny code comes from an online resource, but I have made some modification to the code, and dockerlize the project, then push to my Github repository.

please clone the project to your local directory and run bash commend 

docker build -t r-shiny-app .

docker run -it -p 8080:8080 r-shiny-app

Then open browser, and type http://0.0.0.0:8080 to address bar to check the Shiny web application.