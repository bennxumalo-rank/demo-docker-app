# Demo Docker App

This is a simple Node.js application to demonstrate how to containerise an app using Docker.

## 🔧 Requirements

- [Docker](https://www.docker.com/)
- [Node.js](https://nodejs.org/) (for local dev)

## 📦 Installation

Clone this repo:

```bash
git clone https://github.com/bennxumalo-rank/demo-docker-app.git
cd demo-docker-app

# Build the image
docker build -t demo-docker-app .

# Run the container
docker run -p 3000:3000 demo-docker-app