# Listeem

Welcome to Listeem! 🚀 

Listeem is a simple to-do list web app.

Among the many to-do list tools already available, it's not always easy to find one that suits our needs. Options are either overloaded with features or lack essentials. Listeem was therefore designed with an emphasis on simplicity and the essentials for effective to-do list management. We hope you'll like it!

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
    
    Modify the `.env` file with your settings following instructions commented in the file.

4. **(Optional) Add your own SSL certificate for HTTPS:**
    
    Create a folder named 'ssl' and add your 'privkey.pem' and 'fullchain.pem' files to this folder. They have to be named exactly this way.

5. **Run the application:**
    ```bash
    docker compose up -d
    ```

Now, the Listeem application should be up and running. Open your web browser and visit `http://your-server-domain:8077` to view it.

You may open it in https with the self signed certificate or your own certificate by opening your web browser and visit `https://your-server-domain:8078` to view it.

In case you get the following error:

 ```bash
    BDD connection error : Connection refused
 ```

 don't panic, the database is probably still initializing. Wait a few seconds and refresh the page.

## Features

Check out some features of Listeem at [Features Link](https://listeem.com/features.php)!

