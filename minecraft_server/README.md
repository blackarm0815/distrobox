# create the ubuntu installation (only do this the first time)
distrobox assemble create

# enter the ubuntu installation (do this in future to start distrobox)
distrobox enter ubuntu

# run the setup script
./setup.sh

# get the server.jar from https://mcversions.net/

# start tmux
tmux

# run the server
./run_server.sh

# edit the eula, change false to true
nano eula.txt

# run the java command again
./run_server.sh