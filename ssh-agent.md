### Using ssh-agent to authentificate with public key

ssh-agent ne se lance au démarrage que sur les systèmes linux

autrement on lance la commande dans un sh :

eval `ssh-agent`

echo $SSH_AGENT_SOCK
