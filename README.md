# compressed_visuals

Tool to recreate your Compressed Visuals NFT from on-chain metadata

## Quick guide

1. Find then copy all the transaction metadata corresponding to your NFT.

2. Open Binder using the button below.

3. Run the notebook. Paste the data once prompted.

## Detailed step-by-step guide

1. Find the asset fingerprint of your NFT. This is visible on Tokhun.io for each NFT.

2. Search that asset fingerprint in a Cardano explorer, such as cardanoscan.io.

3. Navigate to the "Mint transactions" tab, then click on the Trx Hash.

4. Navigate to Metadata tab, then open the "Value" element.

5. Copy all the text inside the popup that opens. This is the data defining your NFT.

6. Click on the "launch binder" button below to start the tool and wait for it to load

7. In the left panel double-click on RECREATE.ipynb

8. Press "SHIFT + ENTER" to run the notebook

9. An empty text field will appear, paste your metadata into it, and press ENTER

10. Wait a few seconds and you will find on the left panel a file ending with .png, right-click then download





[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/pictureknight/compressed_visuals/main)
