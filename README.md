ingenius10

defaketo dapp
   -------
   only Dsociety

A blockchain based solution for controlling fake news

The primary focus of this tool is to control fake news by providing the users the right to vote on each news post. People all over the world having coinbase accounts in ethereum blockchain can cast a single vote on each post just by giving a single click. The user can either upvote or downvote a post by clicking the corresponding button. Users can provide sources / evidences for a post and can earn ethers (.05 ether donation from each user who likes the evidence)

There are two main screens,

1. News Feed - A consolidated list of all the news from all over the world. This is the primary screen and users can either upvote or downvote a post.

2. Post Feed - A list of evidences/sources submitted by users of blockchain to substantiate a news post. Each news post can have a list of evidences submitted by various users and the voting concept applies to these posts too.
               Incentives are given to users who submit such evidences, by clikcing the upvote button. Users who like the evidence submitted can give an upvote and transfer .05 ether to the user who created the evidence. This makes sure a lot of participation occurs in the community.
                Bloom filters are implemented to efficiently calculate whether a user with a particual ethereum account has already cast a vote. 
               
Color Code: A red highlight indicates that the news is probably fake and a green highlight indicates that the news is probable true. The color code is decided based on the number of upvotes and downvotes for each news post and the number of upvotes and downvotes for each evidence provided
   
   
   
Smart Contracts:

1. NewsFeed - This smart contract holds all the information(upvotes, downvotes, authors, bloom filters etc.) pertaining to the news post
2. PostFeed - This smart contract holds all the information pertaining to the evidence posts for each news post


Tools & Frameworks:

    Truffle - For building smart contracts
    Ganache - For running local ethereum blockchain
    Metamask - For connecting to ethereum apps from browser
    

Front end  - JS + jQuery, used webpack for bundling

Backend - Truffle framework for smart contracts, Ganache for setting up local ethereum network
 
Interaction - Frontend uses MetaMask (browser plugin) for interacting with ethereum network
