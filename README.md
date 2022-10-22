```sh
npm install
```

```json
{
  "CONTRACT_ADDRESS": "0x5865b234E2D690c5A63CE5B843e6A27DC3365583",
  "SCAN_LINK": "https://polygonscan.com/token/0x5865b234E2D690c5A63CE5B843e6A27DC3365583",
  "NETWORK": {
    "NAME": "Polygon",
    "SYMBOL": "Matic",
    "ID": 137
  },
  "NFT_NAME": "BIRDGANG_NFT_ART_ENGINE",
  "SYMBOL": "BNAE",
  "MAX_SUPPLY": 1000,
  "WEI_COST": 100000000000000000,
  "DISPLAY_COST": 0.1000,
  "GAS_LIMIT": 285000,
  "MARKETPLACE": "OpenSea",
  "MARKETPLACE_LINK": "https://opensea.io/collection/nerdy-coder-clones",
  "SHOW_BACKGROUND": true
}
```

Make sure you copy the contract ABI from remix and paste it in the `public/config/abi.json` file.
(follow the youtube video if you struggle with this part).

Now you will need to create and change 2 images and a gif in the `public/config/images` folder, `bg.png`, `example.gif` and `logo.png`.

Next change the theme colors to your liking in the `public/config/theme.css` file.

```css
:root {
  --primary: #ebc908;
  --primary-text: #1a1a1a;
  --secondary: #ff1dec;
  --secondary-text: #ffffff;
  --accent: #ffffff;
  --accent-text: #000000;
}
```

Now you will need to create and change the `public/favicon.ico`, `public/logo192.png`, and
`public/logo512.png` to your brand images.

Remember to update the title and description the `public/index.html` file

```html
<title>Nerdy Coder Clones</title>
<meta name="description" content="Mint your Nerdy Coder Clone NFT" />
```

```sh
npm run start
```

Or create the build if you are ready to deploy.

```sh
npm run build
```
