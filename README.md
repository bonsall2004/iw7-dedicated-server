# IW7-Mod Dedicated Server for Zombies

Welcome to the IW7-Mod Dedicated Server for zombies! This server allows you to run various maps specifically designed for the zombie mode. 
## Getting Started

### For Windows Users

To start the server on Windows, simply run the `start_zm_server.bat` file.

### For Linux Users

1. If you already have wine installed you can skip to step 6, if it doesn't work then go though this process.
2. Navigate to server directory.
3. Open a terminal window.
4. If you haven't already made the script executable, you'll need to do so. Run the following command:
```shell
sudo chmod +x install-wine.sh start_zm_server.sh
```
5. Execute the `install-wine.sh` script with sudo to set up Wine:
```shell
sudo ./install-wine.sh
```
6. Once Wine is installed, you can start the server by running the `start_zm_server.sh` script with sudo:
```shell
sudo ./start_zm_server.sh
```

## Running the server
To connect to the server from IW7-Mod you need to press the tilde key and type connect IP:Port, this can be a public or private IP address, please make sure that if it's a public IP address then the host is forwarding the port of the server

**Example:**
```bash
connect 10.32.0.40:27016
```

Once you have done that you should be in the server

To change the current map, you can goto your servers console and type 
```bash
map <map_name>
```
- **Zombies in Spaceland** - cp_zmb
- **Rave in the Woods** - cp_rave
- **Shaolin Shuffle** - cp_disco
- **Attack of the Radioactive Thing** - cp_town
- **The Beast From Beyond** - cp_final

**Example:**
```bash
map cp_town
```

## Disclaimers

Please note that this server is exclusively for the zombie mode, and there aren't any multiplayer files included. Attempting to run multiplayer will result in crashes.

This project is intended for educational purposes only. It provides an opportunity for learning about server setup, game hosting, and server management.
