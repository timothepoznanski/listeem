# Listeem

Welcome to Listeem! 🚀 

Listeem is a simple to do list webapp.

## Table of Contents
- [Installation](#installation)
- [Demo](#demo)

## Installation

To get started with Listeem, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/pozinux/listeem.git
    ```

2. **Navigate to the project directory:**
 
    ```bash
    cd listeem
    ```

3. **Create your configuration:**
    
    Copy the `env_template` file to a `.env` file.
    
    Modify the `.env` file with your settings.

4. **(Optional) Add your own SSL certificate for HTTPS:**
    
    Create a folder 'ssl' and add your 'privkey.pem' and 'fullchain.pem' files into this folder. They have to be named exaclty this way. 

5. **Run the application:**
    ```bash
    docker compose -p listeem-prod -f docker-compose.yml up -d
    ```

Now, the Listeem application should be up and running. Open your web browser and visit `http://your-server-domain:8077` to view it.

You may open it in https with the self signed certificate or your own certificate by opening your web browser and visit `https://your-server-domain:8078` to view it.

## Features

Check out some features of Listeem at [Features Link](https://listeem.com/features.php)!

