# create the ubuntu installation
distrobox assemble create

# enter the ubuntu installation
distrobox enter ubuntu

# run the setup script
./setup.sh

# get the server.jar from https://mcversions.net/

# start tmux
tmux

# run the server
java -Xms1024M -Xmx1024M -jar minecraft_server_1.20.1.jar nogui

# edit the eula, change false to true
nano eula.txt

# run the java command again
java -Xms1024M -Xmx1024M -jar minecraft_server_1.20.1.jar nogui