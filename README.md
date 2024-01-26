# NFT Project

## Basic NFT

This basic NFT contract allows users to mint a dog NFT. The contract will map the tokenId to the URI.
The image is stored on IPFS.
It also has a getter function for the tokenURI that takes a tokenId as an input.


# Dynamic NFT

MoodNft.sol is a dynamic NFT. The token has a "state". When it's minted it will start out in the HAPPY state.
There is a function that flips the mood of the NFT between happy and sad, and the token's metadata will update based on the state, including the image.
