# ApeChain-OPStack-SepoliaL2Testnet
This is a community-maintained [ApeChain L2 Testnet](https://explorerl2-apechain-test-qbuapbatak.t.conduit.xyz/) as a Sepolia rollup using OP-Stack deployed by [jackie.eth](https://x.com/JackieLeeETH/status/1718281383951638786?s=20) using [Conduit](https://conduit.xyz/). There have been lots ApeChain discussions but zero actions. This is why apes are [stepping up](https://forum.apecoin.com/t/aip-377-apechain-a-team-research-deploy-manage-apechain/20163).

# Why ApeChain?
Gas costs and chain revenue should go back to its community. We all witnessed gas wasted on OtherSide mints (i.e., people were paying 2e gas). All these game-related gas could go back to the community if we have our own ApeChain. To prepare for the future growth of onchain game, commerce, and entertainment based on the apes and ApeCoin ecosystem, we need an ApeChain.

### Why L2?
 - L2 is secured by ETH L1 infra. All high value NFTs are on ETH L1.
 - Gas fees are lower https://l2fees.info/

### Why OP-Stack?
 - Used by Base
 - Great dev community (many OP dev friends helped answer questions. thank u all!!)
 - Easier to deploy (for me and for anyone else)
 - Official Optimism support for Superchain (chains deployed using OP Stack)

### AIP-377
This ApeChain Testnet is POC demo of using Optimism's OP Stack. The A-Team will carry out further development stated in [AIP-377](https://forum.apecoin.com/t/aip-377-apechain-a-team-research-deploy-manage-apechain/20163)

### ApeCoin voting
ApeCoin holders can still vote when using ApeChain (w. Snapshot strategies)

## APE as gas?
L2 gas should be ETH, but there are ways to do gas fee reimbursement. 

# Testnet Chain Info
- ChainId `111`
- RPC https `https://l2-apechain-test-qbuapbatak.t.conduit.xyz`
- RPC wss `wss://l2-apechain-test-qbuapbatak.t.conduit.xyz`
- [ApeChain Testnet info via Conduit](https://app.conduit.xyz/published/view/apechain-test-qbuapbatak) 

### Explorer
- https://explorerl2-apechain-test-qbuapbatak.t.conduit.xyz/
- https://explorerl2new-apechain-test-qbuapbatak.t.conduit.xyz/

### Sepolia Faucets (for SepoliaETH)
- Infura https://www.infura.io/faucet/sepolia
- Alchemy https://sepoliafaucet.com/

### Bridging (from Sepolia to ApeChain-Test)
- SuperBridge https://apechain-test-qbuapbatak.testnets.superbridge.app/ (need SepoliaETH) via [Superbridge](https://twitter.com/superbridgeapp)
- Pay erc20 on L1 Goerli/Sepolia to mint NFTs on L2 OP-Goerli/ApeChain-Testnet using OP-Stack native crossdomain messenger - https://github.com/AnotherWorldDAO/L2MintWithAPE

# Future integration
### Account Abstraction (AA)
- Smart accounts (web2 sign-in + fiat onramp + AA) are the way to provide better UX for apps deployed on the future ApeChain. 

### Game integration study - [Another World](https://anotherworld.gg/)
- Another World airdropped $APE to players on Ethereum BUT the gas fee costs too much ([tx](https://etherscan.io/tx/0xe5a9505f8bbe68f4829318621bf99ce0f8f311e1aeda59a1f180df90768ad0ac))
- Another World airdropped [$OP](https://optimistic.etherscan.io/tx/0x17b33f2fec0b0494eeed2138ee32af6a4a3d87cd635a8eeb0d5fb41da2541c0c) and [game item NFTs](https://optimistic.etherscan.io/tx/0xdd2e004c317d2e97ef14b1a5c8c9c2e18afe56a299760d1d6104fb1dec19f1f6) to players on Optimism to reduce costs. 
- Another World is currently using ApeChain Testnet for airdropping [game items (ERC1155)](https://explorerl2-apechain-test-qbuapbatak.t.conduit.xyz/address/0xEA37A064f1Eb0Da834fd01003e7831c902a42EFd) and [scores (ERC20)](https://explorerl2-apechain-test-qbuapbatak.t.conduit.xyz/address/0x9565aAcf12F9Fcb3117AD69348455718AE04840C).

# Related notes
- Posting data to L1 still costs a lot https://twitter.com/0xKofi/status/1735796630769512526
- Vitalik's zkEVM take https://x.com/VitalikButerin/status/1734947774343332116?s=20
- OP loves arts https://x.com/Optimism/status/1732159055420854732?s=20
- RaaS tips https://x.com/KAndrewHuang/status/1720071725348421672?s=20
