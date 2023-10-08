# lc-web3
Module for Godot 4 for integration with web3. 

It's mostly made for LunCo.

The intended workflow:

1. User Downloads binary version of LunCo
2. To login Godot starts local server
3. User opens local link in browser with Metamask (or other web3 wallets)
4. Web page updates Godot, e.g. sends signal when user logined, or queries web3 info e.g. what NFT user has
