## Self hosted TON API instances

This repository is covering ton-http-api and ton-api-v4 instances hosting. In case of API-specific issues, you might want to address those issues in corresponding repository:
https://github.com/toncenter/ton-http-api
https://github.com/ton-community/ton-api-v4

### Quickstart:

1. **Configure your server to work with Docker**
   - user with sudo permissions
   - install Docker and docker-compose
     Simplest way to do this is https://github.com/evertramos/easy-server
2. **Configure and start default proxy stack**
   Use the easy-server's nginx-proxy-automation script or directly use the https://github.com/evertramos/nginx-proxy-automation
3. **Follow instructions configuring .env file for ton-http-api (listed in their repo)**
4. **Replace domain and email in docker-compose.yaml with your data.**
5. Run **docker-compose up -d **

Video tutorial:
https://youtu.be/QHXkA2NZjaM
