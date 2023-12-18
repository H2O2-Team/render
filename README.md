# render
deploy shell in a box on render

The default is Debian If you want to deploy the Ubuntu Dockerfile please fill in `./Ubuntu/Dockerfile`

admin: root

password: 1234

1.
```
apt update && apt install -y curl
```
2.
```
bash <(curl -s https://raw.githubusercontent.com/H2O2-Team/render/main/main.sh)
```
