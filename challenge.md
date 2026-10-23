# Challenge Answers

1. Program: htop
   Command: sudo apt install -y htop && htop
   Details: Shows real-time CPU core usage, memory usage, tasks, and process list.

2. Apache2 Version Offered:
   Command: apt show apache2 | grep Version
   Details: Version 2.4.58-1ubuntu8 (or similar based on Ubuntu release)

3. Number of Installed Packages:
   Command: apt list --installed | wc -l
   Details: <Insert your exact total count here, e.g., 785>

4. Run Alpine Container:
   Command: sudo docker run --rm alpine echo "Hello from Alpine"
   Details: Container pulled alpine image and printed "Hello from Alpine".

5. Key & Source Paths:
   Command: ls /etc/apt/keyrings/docker.asc /etc/apt/sources.list.d/docker.sources
   Details: Key path: /etc/apt/keyrings/docker.asc | Source path: /etc/apt/sources.list.d/docker.sources

6. Remove htop & Verify:
   Command: sudo apt remove -y htop && hash -r && htop
   Details: bash: /usr/bin/htop: No such file or directory (htop is successfully removed).
