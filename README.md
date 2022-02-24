# wsl-scripts
A bunch of custom scripts for my WSL setup through various computers.

## cloc-git 

### Description

**cloc-git** is a tool to count the lines and the different types of files from a given git repository. In order to use it, please make sure you have <code>cloc</code> already installed in your system. You can install it by: <code>sudo apt install cloc -y</code> <br/>

### How to execute

- <code>cloc-git {https-from-git-repo}</code>

## shut

### Description

**shut** is a script that utilizes the <code>shutdown.exe</code> windows command in order to shutdown the computer after given minutes. If the minutes given are less than 0 the shutdown process is canceled. If no argument is given an error message appears. 

### How to execute

- Shutdown the computer in 10 minutes: <code>shut 10</code>
- Cancel previously set shutdown: <code>shut -1</code>

## reboot

### Description

**reboot** is a script that utilizes the <code>shutdown.exe</code> windows command in order to reboot the computer after given minutes. If the minutes given are less than 0 the reboot process is canceled. If no argument is given the computer starts rebooting. 

### How to execute

- Reboot the computer: <code>reboot</code>
- Reboot the computer in 10 minutes: <code>reboot 10</code>
- Cancel previously set shutdown: <code>reboot -1</code>
