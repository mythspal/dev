# ssh-keygen
    ssh-keygen -f id_rsa -t rsa -b 4096 # create key to be saved as filename id_rsa using rsa algorithm with key size of 4096 bits

# ssh-agent
    eval $(ssh-agent -s) # start ssh-agent -s forces generation of shell commands on stdout
    echo $SSH_AGENT_SOCK # check if agent is running
    ssh-add -l # list added keys
    ssh-add <PATH_TO_KEY> # to add key to be managed

# References
* ssh-keygen - [https://ssh.com/ssh/keygen]
* ssh-agent - [https://ssh.com/ssh/agent]
