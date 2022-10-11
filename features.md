# Implemented Features

Here is the list of features that have been implemented for the Hackathon:

- NFT collections for cards, enemies and scenes (non-transferable as of now)
- SceneLogic contract linked to a Scene NFT
- Card & Scene catalogs to register a GameMode and retrieve its associated NFTs
- GameMode contract that manage the user session, deck and game state
- A PRNG library based on Realm’s implementation (stateless version of the Realm contract)
- A SessionManager library to hash and save the game state on-chain (the player manages their session off-chain)
- A Player library that generate deck presets.
