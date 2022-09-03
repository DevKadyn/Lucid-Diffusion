# Lucid-Diffusion
![visitor badge](https://visitor-badge.glitch.me/badge?page_id=DevKadyn.Lucid-Diffusion) ![Stars](https://img.shields.io/github/stars/devkadyn/lucid-diffusion) [![Maintenance](https://img.shields.io/badge/status-Unmaintained-red.svg)](https://github.com/DevKadyn/Lucid-Diffusion) [![Issues](https://img.shields.io/github/issues/devkadyn/lucid-diffusion)](https://github.com/DevKadyn/Lucid-Diffusion/issues) <img alt="GitHub all releases" src="https://img.shields.io/github/downloads/DevKadyn/Lucid-Diffusion/total">
<img alt="GitHub" src="https://img.shields.io/github/license/DevKadyn/Lucid-Diffusion">
## About
Lucid Diffusion was originally a personal notebook offshoot of Disco Diffusion V5.6 to practice python, but having added some interesting features, I thought it best to release it to the public. This fork restructures the Google Colab notebook and the python code in a way that is a bit more organized for the end user:
* init_images includes new features and is now found in the ideation section.
* Google Colab GUI to enter your prompt
* And more...


## Change Log
Release 1.2.1 - Sep 3rd, 2022 (Last Release)

- Added in some more helpful documentation within the notebook.
- Change some of the default settings to get new users started.
- New way to authenicate with HuggingFace. Type your token into the string and it will auto authenicate each time instead of needing to retype it in.
- Updated the license and credits section.
- More code clean up and fixes.

Release 1.2.0 - Aug 30th, 2022

- Added in Google Colab weight sliders from -20 to 20 so you don't need to edit the code to change the weights.
- Added in code so if you leave out a section of Text Prompts completely, the weight variable will be ignored and not influece it.
- Added Google Drive saving for Stable Diffusion. It will now export a local temp file and save to your exports folder. It will also automattically increment from 0000 to 9999
- Stable Diffusion pipeline will now generate a text file to save your settings.
- export_name now replaces batch_name and is found in the generate image section for easy access.
- You are now able to set your seed. Setting your seed to zero will make it random.
- You are now able to disable and enable the NSFW Filter during the pipeline setup. This will stop the black boxes from happening, but may include nsfw content.
- More code clean up and fixes.

Release 1.1.0 - Aug 29th, 2022

- Added Stable Diffusion models to the mix. You are now able to load in one or both diffusions to play with.
- More code clean up and fixes.

Release 1.0.0 - Aug 28th, 2022

- Reorganized everything. At the core, most guides should help. A setting may be in a different location.
- You are now able able to manually type out your Google Drive path in the Colab forms rather than touching the code.
- Moved init_image to the Ideation section.
- Added in a dropdown menu and code to support init_image. You are able to select None, Custom Path, and the new beta option, Random Unsplash. Random Unsplash option will pull a random image, to size of your export and use it as an init image.
- Added in a a Google Colab GUI for the text_prompt. Currently only supports one image at a time. But it will output a string of text that you can copy

