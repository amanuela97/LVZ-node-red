LVZ-node-red
============

A gimbal/camera control system using levitezer protocol/box.

## Quick Start/Node-RED Installation.

1. `sudo npm install -g --unsafe-perm node-red`

Once installed as a global module you can use the node-red command to start Node-RED in your terminal. You can use Ctrl-C or close the terminal window to stop Node-RED.

2. `node-red`

You can then access the Node-RED editor by pointing your browser at

3. Open <http://localhost:1880>

Check out https://nodered.org/docs/getting-started/local for full instructions on getting
started.

## Developers

If you want to run the latest code from git, here's how to get started:

1. Clone the code:

    git clone https://github.com/amanuela97/LVZ-node-red.git \
    cd node-red

2. Install the node-red dependencies

    npm install

3. Build the code

    npm run build

4. Run

    npm start

5. Once you have installed the project locally, connect the gimbal and camera directly to your device 

6. After connecting the cables, full deploy the project from the node-red workspace

    ![deploy button](https://aws1.discourse-cdn.com/business6/uploads/nodered/original/3X/2/d/2d31440e4eb591d989cc575e9d6cd653e2868348.png)

7. you can then access the user interface from <http://127.0.0.1:1880/ui>

8  Lastly, connect to the gimbal by going to [Setting tabs -> Gimbal Setups], selecting tcp connection then providing the ip and port number of the box.

   ![When the connection status turns green, the connection has been established](https://github.com/amanuela97/LVZ-node-red/blob/master/setup.png)
   

### About

A gimbal/camera control system using levitezer protocol/box.
for more info about levitezer check out http://levitezer.com/
