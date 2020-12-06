# GIF search
https://img.shields.io/badge/flask-1.1.2-blue
https://img.shields.io/github/directory-file-count/IvanYerkinov/BEW2.2


Search for gifs by keyword, hosted on: https://gif-search1.herokuapp.com

Kevin and Konstantin


Steps for running program through Docker:  
1.) git clone the directory  
2.) Build the image ' docker build -t gif-search-image . '  
3.) Build the container ' docker run -p 5000:5000 --rm --name gif-search-container gif-search-image '  
