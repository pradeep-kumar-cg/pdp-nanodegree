

## Project 5: Decentralized Star Notary

1) ERC-721 Token Name	: "Udacity Star Notary Token"
2) ERC-721 Token Symbol	: "USNT"
3) Version of Truffle 	: 5.0.21
4) Version of openzeppelin-solidity: 2.1.2


#Contract function: 
function lookUptokenIdToStarInfo (uint _tokenId) public view returns (string memory) 
#Description:
Looks up the stars using the Token ID, and returns the name of the star.


#Contract function: 
function exchangeStars(uint256 _tokenId1, uint256 _tokenId2) public 
#Description:
Twp users can exchange their star tokens.


#Contract function: 
function transferStar(address _to1, uint256 _tokenId) public 
#Description:
Transfers a star from the address of the caller to given address



