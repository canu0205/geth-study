# Geth Study

🔎 An in-depth study (Jan, 2024 - Apr, 2024) of the networking stack and execution layer internals of **go-ethereum (Geth)**.

## Contents

- **Discovery v4/v5 Protocols**  
  Node discovery protocols for finding peers in Ethereum P2P networks.
- **DevP2P Stack and RLPx**  
  Encrypted and authenticated communication between nodes via the DevP2P stack and RLPx.
- **Execution-Consensus Client Separation**  
  Post-Merge Ethereum architecture and how Execution Clients and Consensus Clients interact via the **Engine API**.

## Key Concepts

- **Discovery Stack**: UDP-based peer discovery (Discv4, Discv5 migration).
- **DevP2P Stack**: TCP-based encrypted messaging (RLPx handshake and communication).
- **Engine API**: Defines how Execution and Consensus clients coordinate (e.g., `engine_newPayload`, `engine_forkchoiceUpdated`).

## Why This Study?

Understanding **networking fundamentals** and **client modularization** is critical for Blockchain Core Development, especially in scaling and securing decentralized networks.

## References

- [go-ethereum Github](https://github.com/ethereum/go-ethereum)
- [Ethereum.org Developer Docs - Nodes and Clients](https://ethereum.org/en/developers/docs/nodes-and-clients/)
- [EIP-1459: Node Discovery via DNS](https://eips.ethereum.org/EIPS/eip-1459)
- [Ethereum DevP2P Protocol Spec](https://github.com/ethereum/devp2p)

---

🧠 Part of my preparation for entering the Blockchain Core Developer field.
