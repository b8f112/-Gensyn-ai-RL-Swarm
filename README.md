screen -S swarm   

sudo apt update    

sudo apt install -y git python3 python3-venv python3-pip curl        

python3 -m venv venv  

source venv/bin/activate   




wget -O swarm.sh https://raw.githubusercontent.com/b8f112/-Gensyn-ai-RL-Swarm/refs/heads/main/swarm.sh && sed -i 's/\r//' swarm.sh && chmod +x swarm.sh && ./swarm.sh
