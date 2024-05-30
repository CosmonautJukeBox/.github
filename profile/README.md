# Cosmonaut Juke Box


## Description

This is a hackathon project for the Awesome CosmWasm Hackathon. We have created Cosmonaut JukeBox, featuring an interactive astronaut who asks, "What is your mood today?" Based on the user's response (e.g., happy or sad), the astronaut plays one of the songs that match the user's mood. Additionally, the astronaut performs a light show with colors that correspond to the user's mood, creating an immersive audio-visual experience. The user can pay for a song in crypto.

## Frontend

Frontend to call the contract.

You will find the frontend in the [Frontend](https://github.com/CosmonautJukeBox/frontend) repository.

## Smart Contract

You will find the smart contract in the [Contract](https://github.com/CosmonautJukeBox/CosmonautJukeBoxContract) repository.

## Observer

Observer which gets the data from contract and frontend. Calls the Astronaut/Cosmonaut.

You will find the observer in the [Observer](https://github.com/CosmonautJukeBox/Observer) repository.


## Tech Stack

### Frontend

- NextJs
- Cosmology
- TypeScript
  
### Smart Contract

- CosmWasm
- cw-orchestrator
- Neutron Testnet

### Backend

- CosmJS
- node-wot
- NodeJs
