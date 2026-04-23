# Dockerizing an Apache Web Server 🐳

Running Apache web server inside a Docker container.

## Requirements
- Docker installed on your machine

## Steps

**1. Clone this project**
git clone https://github.com/adhilmr/Dockerizing-an-Apache-Web-Server.git
cd Dockerizing-an-Apache-Web-Server

**2. Build the image**
docker build -t apache-server .

**3. Run the container**
docker run -p 80:80 apache-server

**4. Open your browser**
http://localhost

That's it! 🎉

## Built with
- Ubuntu
- Apache2
- Docker
