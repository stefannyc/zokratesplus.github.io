---
layout: default
---


# ZoKrates
ZoKrates allows for verifiable, privacy-preserving off-chain computations that can help to scale blockchains without compromising their key properties. Hence, allowing for lower transaction costs and enabling privacy without loss of transparency.

# ZoKratesPlus
ZoKratesPlus is a publicly funded project for exploring new application contexts, nurturing the zero knowledge community, and advancing zero knowledge based technologies.


# Existing Application Contexts

## Transaction Aggregation
Zero Knowledge rollups reduce transactional costs and enhance privacy by aggregating transactions offchain and presenting zero knowledge proofs of correct computation, which are then verified on chain. [Polygon Nightfall](https://polygon.technology/solutions/polygon-nightfall/) [uses ZoKrates](https://github.com/EYBlockchain/nightfall_3) to generate zkSNARKs that are verified in a dedicated smart contract on chain.


## Anonymous Credentials
Zero Knowledge proofs enable the verification of identity-related properties without revealing unnecessary information. Hence, allowing for the verification of anonymous credentials by DApps and [other novel aspects](https://arxiv.org/pdf/2209.09584.pdf) that improve on the state of the art. A credential system the world wide web consortium provides [recommendations](https://www.w3.org/TR/vc-data-model/) for verifiable credentials.

https://github.com/JonathanHeiss/ZoKrates-Credential-Verification 

## Accounting in Energy Grids
Households that act as energy prosumers can benefit by forming communities to trade energy locally.

Zero Knowledge proofs enable [transparent accounting](https://www.ise.tu-berlin.de/fileadmin/fg308/publications/2020/preprint-ICBC-Eberhard.pdf) computations on confidential information such as smart meter measurements without revealing the information to other community members. [Field experiments](https://github.com/JacobEberhardt/decentralized-energy-trading) and prototypes helped to demonstrate privacy-preserving accounting in energy grids with ZoKrates. 

## Federated Learning
Blockchains improve security guarantees of federated learning by making the global model management more transparent and tamper-resistant. However, the integrity of training data introduced by edge devices poses a vulnerability. Zero Knowledge proofs allow for local training among edge devices, which then provide integrity proofs that are verified on chain when updating the global model. The performance and applicability of [such a system](https://arxiv.org/pdf/2206.11641.pdf) were evaluated in a [proof of concept](https://github.com/NikolasHaimerl/Advancing-Blockchain-Based-Federated-Learning-Through-Verifiable-Off-Chain-Computations) implementation.


Currently, we are trying to identify projects that would benefit most from our support. Feel free to [reach out](./contact.html) and share your practical zero knowledge experience or needs.
