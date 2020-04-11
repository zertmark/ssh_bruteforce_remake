# ssh_bruteforce_remake
Simple ssh_bruteforcer on Ruby                                               
# INSTALL:                          
git clone https://github.com/zertmark/ssh_bruteforce_remake.git && cd ssh_bruteforce_remake && chmod +x installer.sh               
./installer.sh                               
# RUN                       
./ssh_bruteforcer -h

usage: ./ssh_bruteforcer [options]
    --host          IP of server(default-localhost)
    -p, --port      Custom port
    -u, --user      Username(default-root)
    -w, --wordlist  Path to wordlist(default-john dictionary)
    -v, --verbose   Enable verbose(default-false)
    -h, --help 
