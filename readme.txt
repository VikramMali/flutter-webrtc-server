1) verify git is install 
2) run command  git clone sorce code provided by me. 
3) run command  cd flutter-webrtc-server
4) run command  sudo openssl req -x509 -nodes -days 365 -newkey rsa:2048 -keyout configs/certs/key.pem -out configs/certs/cert.pem
5) tell info asked by above command , enter domain name which you will be using while using this project
6) verify golang is install 
7) run command  go run cmd/server/main.go
