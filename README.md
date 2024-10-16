# Dynamic NFT Gallery
**Current Version: 1.5**

## Introduction

Welcome to my NFT gallery website! This was designed to showcase a NFT collections based on the wallet address but now making it opensource to the bulic. It allows users to display NFTs from the Ethereum and Polygon Blockchain.

## Why I Made It

I created this website initially to showcase my own NFT collection so I could put the website on LinkTree. However after googeling I wasn't able to find a valid provider that will do this job. Every Website I found was inputting a address and it will display the images. However I wanted a more static yet dynamic solution. This is the solution


## Features

- Interactive NFT gallery
- Smooth hover effects and animations
- Integration with Ethereum and Polygon blockchains
- Supports multiple wallets:
    - First wallet address is the "main" wallet and will be loaded on reload
    - Every subsequent wallet will be loaded in about 3 seconds after each other due to API limitations.
- Customizable based on your wallet address and NFTs
- Using the Archemy API
- Customizable Filter against scam or unwanted NFTs


## Make if yours!

If you’re interested in customizing or using this site for your own purposes, you can copy the code from this repository. Here’s how:

(THIS TUTORIAL ASSUMES THAT YOU ALREADY HAVE GITHUB ACCOUNT SET UP. If NOT please follow the offical github setup tutorial here: [Github Getting Started](https://docs.github.com/en/get-started/start-your-journey/creating-an-account-on-github). You could also host this on a VPS. Your choice! :3)

- Download the repository: `git clone https://github.com/MrMidnight7331/mrmidnight7331.github.io.git` or download it as a zip and decompress it.
- Create a GitHub repository with the name: {YourUserName}.github.io (Example: mrmidnight7331.github.io): [Tutorial](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site)
- Customize the config.json file:
    - Make an account on [Alchemy](https://www.alchemy.com/nft-api)
    - Get the API key and put it into config.json
    - Login into your [SkyMavis](https://developers.skymavis.com/console/applications/) Developer account and get your API key for the ronin api (if you want to use ronin chain)

    - Change the wallet address to your own ethereum addresses. It works with multiple addresses!
    - Change your username

- Customize your profile picture:
    - Put your own pfp.ico into "icons"
- Upload all the contents to the repository and wait for deployment
- Enjoy!

(If you are also a developer and wants to do more with the api, I included a test.js that will pull the raw json response just like app.js!)

Feel free to contribute to this project or use it as a base for your own NFT gallery!

## Services:

If you have no idea about github or technology, I could:
- walk you through the setup process for a cup of coffee
- remote desktop to your pc and set it up for you for 5 cups of coffee

## Technologies Used:

- HTML
- CSS
- JavaScript
- Alchemy API

## Changelog:
- V1.0 
    - Initial Deployment
- V1.1
    - Changes in color scheme
    - Lighting improvement
    - Added better footbar animation
- V1.2
    - Cards are flippable for more information
    - General bug fixing
    - Change ethereum address link to contract address link
- V1.3
    - Added Light / Dark mode toggle
    - Added cookie to remember modes
    - Centered Button
- V1.4
    - Integrated Base Blockchain
    - Updated Color Scheme
    - Better Animation
    - General Bug Fixes
    - Appearance Fixes
    - Footer fixes
- V1.5
    - Integrated Ronin Blockchain
    - Integrated Sidekick NFTs
    - Integrated Pixels Pets NFTs

## Future Plans:
- ~~Add collection address to title of card instead of wallet address.~~
- ~~Add options to change dark, light mode~~
- Add options to view NFTs from other addresses
- Add more customization methods like color scheme
- ~~Add more info on the back side of the card. Turn around transition with smooth animation~~
- Make a official service out of it like link tree. (Need a team)


## Contact
Feel free ho contact me on my socials if you face any problem or need help with tbe setup process!

- [Twitter: @MrMidnight53](https://twitter.com/MrMidnight53)
- [Instagram: mrmidnight7331](https://www.instagram.com/mrmidnight7331)
- [LinkTree: MrMidnight53](https://linktr.ee/MrMidnight53)

## Donate
If you think I did a good job feel free to donate here to help me create OpenSource Projects (Money doesn't grow on OpenSource):

ETH: 0x939A9353e1a72e5d6Da07424c74815a6651a86f4

MATIC: 0x939A9353e1a72e5d6Da07424c74815a6651a86f4

SOLANA: HsNpPDGhDsmq4j1PBTDuMx67svj6446m8aUWGSpjGCjk

BTC: bc1q55kfd0elssc9u3ha86gw4ea9w3l5cw7ch58hce

Or buy me a coffee here:

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/S6S7NRQSG)

## License

This project is licensed under the MIT License.

