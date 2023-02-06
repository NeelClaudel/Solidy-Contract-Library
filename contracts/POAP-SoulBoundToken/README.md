SOUL: Soulbound POAP
SOUL is a soulbound implementation of Proof of Attendence Protocol (POAP), created by SoulBound Protocol. SOAL is SBT (SoulBound Token).

Features
ERC1155: SOUL follows ERC1155 multi-token standard (See EIP-1155). SoulID corresponds to ERC1155 token ID.
Non-transferable: SoulBound
Community Recovery: at extreme condition (losing private key), community multisig (contract owner) can transfer the token to the new wallet under the approvement of the token holder.
How it works?
Project/DAO creates new event at SoulBound Protocol website, free and permissionless. (Shall we bring this step on-chain?)
SoulBound Protocol server links the project/DAO address and event to a SOUL eventId.
Project/DAO submit the address list of event pariticipants.
SoulBound Protocol server signs on the address list, allowing them to mint SOUL.
Participants mint SOUL at the SoulBound Protocol website.