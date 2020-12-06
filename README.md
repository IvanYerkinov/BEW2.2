# GIF search


Search for gifs by keyword, hosted on: https://gif-search1.herokuapp.com

Kevin and Konstantin


Steps for running program through Docker:
1.) git clone the directory
2.) Build the image ' docker build -t gif-search-image . '
3.) Build the container ' docker run -p 5000:5000 --rm --name gif-search-container gif-search-image '
