Test server
===

```
npm install
```

Run each of these. They'll serve the site at localhost:8080. Try visiting that via your machine's IP address. They all work except for the sirv-cli example. Adding `-c` or `--cors` does not solve the problem. Adding the LAN IP address as `-H` or `--host` was the only scenario where I got it to work.

```
npm run live-server
npm run sirv
npm run http-server
```
