# Discord Bot Template for StyleGANV2
Create a discord bot that generates images with StyleGAN2! All credit for this code goes to NVIDIA, this is just an example use case I recommend you check out if you're looking to extend your discord bot's abilities.

## Setup
1. You'll need to save your networks PKL file into this projects directory and update the `network_path` variable on line 74 of `bot.py`. If you don't have a PKL, or don't know what a PKL file is, it is a pickle file that tells pytorch how to get your network loaded. This file should be named `network-final.pkl` in the results folder after you train your GAN. I recommend checking out the[StyleGANV2 project](https://github.com/NVlabs/stylegan2-ada) for more details on this. 
2. You'll need to add your bot's token to the `token` variable on line 63 of `bot.py`.

Other than that, this project runs like a charm and is a simple and easy addition to add GAN and DeepFake Techniques to your discord bot. 
