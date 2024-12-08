# flask.py
Docker python app run 
create directory then create the files inside it Dockerfile,app.py and requirements.txt
docker build -t custom_flask_img .
docker run -d --name flask_container -p5000:5000 custom_node_image (The -p 5000:5000 flag maps port 5000 on your machine to port 5000 in the container.)
Visit http://localhost:5000/ in your browser.
