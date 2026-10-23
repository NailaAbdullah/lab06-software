# Challenge Answers
1. Install Htop:
Command: 'sudo apt install -y htop'
Answer: Shows active CPU usage bars, memory/swap utilization, total running tasks/processes, and systen uptime
2. Apache2 version offered:
Command: 'sudo show apache2'
Answer: version 2.4.58-1ubuntu8.1 (or version shown in your command ouput)
3. Count Installed Package
Command: 'apt list --installed | wc -l'
Answer: 785 installed package (use your actual count:.
4. Run Alpine Docker Container:
Command: 'sudo docker run --rm alpine echo "Help from Alpine"
Answer: Ouput: "Hello from Alpine"
5. Docker Paths
Key file path: '/etc/apt/keyrings/docker.asc'
Source file path: '/etc/apt/source.list.d/docker.sources'
6. Remove htop and Verify
Commands:
'sudo apt reomve -y htop'
'hash -r'
'htop'
Answer: Returns "Caommand 'htop' not found"
