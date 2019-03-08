docker build -t nmap .

docker run -it  nmap:latest

docker run -it  nmap:latest --help

docker run -it  nmap:latest -v -A scanme.nmap.org

