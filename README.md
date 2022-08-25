# DAOSolidityDapp

This is a DAO for holders of  CryptoDevs NFTs. From the ETH that was gained through the ICO, there was built a DAO Treasury. 

The NFT holders will be able to create and vote on proposals to use that ETH for purchasing other NFTs from an NFT marketplace, and speculate on price. 
Maybe in the future when an NFT is sold back, the profits can be split among all members of the DAO.

Requirements
-Anyone with a CryptoDevs NFT can create a proposal to purchase a different NFT from an NFT marketplace
-Everyone with a CryptoDevs NFT can vote for or against the active proposals
-Each NFT counts as one vote for each proposal
-Voter cannot vote multiple times on the same proposal with the same NFT
-If majority of the voters vote for the proposal by the deadline, the NFT purchase is automatically executed


To be able to purchase NFTs automatically when a proposal is passed, we need an on-chain NFT marketplace that you can call a purchase() function on. 
To avoid overcomplicating things, we will create a simplified fake NFT marketplace.

