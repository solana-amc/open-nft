# Open NFT Collection

### How to access the existing NFTs

- Access is at `https://raw.githubusercontent.com/solana-amc/open-nft/main/solana/<your-project>/nft.json`
- For example, to access NFTs of Solana AMC, check `https://raw.githubusercontent.com/solana-amc/open-nft/main/solana/solana-amc/nft.json`

### How to add your Solana NFT

- Create a folder for your project under solana directory
- Add the images of NFTs in asset folder inside your project directory
- Create json file for you NFTs like below:

  ```json
  [
    {
      "src": "https://raw.githubusercontent.com/solana-amc/open-nft/main/solana/solana-amc/assets/lady_luck.png",
      "thumbnail": "https://raw.githubusercontent.com/solana-amc/open-nft/main/solana/solana-amc/assets/lady_luck.png",
      "thumbnailWidth": 512,
      "thumbnailHeight": 512,
      "mint": "FXJqywZv1sX77qLL2Bxj2N5dmVVQfGsH34i2eXrbrUPU",
      "name": "Lady Luck"
    }
  ]
  ```

- Raise the PR, it will be approved by a community member
