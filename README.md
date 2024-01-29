# interview
# Cherrytree 
https://www.giuspen.net/cherrytree/#downl        # download here
# you can use flatpak/snap there is latest version of cherrytree 1.0.4 available
# regular repositories offer much older versions of cherrytree those can be unable to open the file
# before you open knowledge_base_devops.ctb please load cherrytree_preferences.cfg:
File / Preferences / Import Preferences 

# (Linux users) you can also run cherrytre 1.0.4 in docker 
# where knowledge_base_devops.ctb & cherrytree_preferences.cfg are pre-loaded up:
# Use docker-compose.yml; copy it into any dir you wish; open dir in terminal;
docker pull leoncz/cherry:latest    # you can pull img from docker hub manually 
xhost +local:docker                 # run in terminal to allow Connection to X11 server
docker-compose up                   # start up the container

