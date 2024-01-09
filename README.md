# DavesFamily
Daves Family
## Ethers integrated
### All needed ethers integration is in this file
`DavesFamily-react-ethers-nft-whitelist\packages\mars-theme\src\web3\interact.js`  
1. Connect Daves-family Smart Contract via Metamask wallet.
2. Check whether its `whitelisted` using `ethers.contract`
3. Set cookies according to `whitelisted`
4. Minting with `value` and `args`.
5. Send transactions via metamask wallet when minting, used `ethers.iface` to make `data` field of transaction. 

#### Required Commands to run

```
npm i react-slick
```
```
npm i slick-carousel
```
```
npm i react-bootstrap bootstrap@5.1.3
```
```
npm i react-circular-progressbar
```
```
npm i d3-ease
```
```
npm i react-move
```
```
npm i react-visibility-sensor
```
```
npm i react-countdown
```
```
npm i react-cookie
```

### Create a production-ready build

```
npx frontity build
```

Builds the app for production to the `build` folder.

This will create a `/build` folder with a `server.js` (a [serverless function](https://vercel.com/docs/v2/serverless-functions/introduction)) file and a `/static` folder with all your javascript files and other assets.

Your app is ready to be deployed.

### Deploy

With the files generated in the _build_ you can deploy your project.

#### As a node app

Use `npx frontity serve` to run it like a normal Node app.

This command generates (and runs) a small web server that uses the generated `server.js` and `/static` to serve your content.
