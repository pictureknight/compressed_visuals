# compressed_visuals

Tool to recreate your Compressed Visuals NFT from on-chain metadata

For more info about the project, check out [compressedvisuals.io](https://compressedvisuals.io)

## Demo NFT

If you want to try out this tool, before buying, you can find an example NFT [here](https://cardanoscan.io/transaction/24fb1eff93629960183b529fd138442fb9b939cf2e73e4967e3d2fccee7aac92?tab=metadata)

Using this, you can start the process at step 4 of the detailed guide.

## Quick guide

1. Find then copy all the transaction metadata corresponding to your NFT.

2. [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/pictureknight/compressed_visuals/main), then run RECREATE.ipynb

3. Paste the data once prompted.

4. Once the notebook finishes computing, the PNG will be available on the left panel. 


## Detailed step-by-step guide

1. Find the asset fingerprint of your NFT. This is visible on [Tokhun.io](https://tokhun.io) for each NFT.

2. Search that asset fingerprint in a Cardano explorer, such as [cardanoscan.io](https://cardanoscan.io).

3. Navigate to the "Mint transactions" tab, then click on the Trx Hash.

4. Navigate to Metadata tab, then open the "Value" element.

5. Copy all the text inside the popup that opens. This is the data defining your NFT.

6. Click on the [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/pictureknight/compressed_visuals/main) button to start the tool and wait for it to load

7. In the left panel double-click on RECREATE.ipynb

8. Press "SHIFT + ENTER" to run the notebook

9. An empty text field will appear, paste your metadata into it, and press ENTER

10. Wait a few seconds and you will find on the left panel a file ending with .png, right-click then download
