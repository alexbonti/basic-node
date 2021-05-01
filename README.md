This is my super basic node with docker. 
Runs normally on 8080 or env, use nmp start.

Modify and build image using
docker build -t {username}/{nameoftheimage} .

Run as a docker using 
docker run -p 10000:8080 -d alexbonti/basic-node