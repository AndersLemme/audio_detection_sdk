# audio_detection_sdk
To be able to use the SDK I created a new environment with python 3.10. I decided to create a new repo for working with python 3.10 and the AI_Software_Development_Kit.

## Description


## Setup Notes

- Setup WSL for window's

### Venv & SDK setup windows (old):

- C:\Users\my_user\AppData\Local\Programs\Python\Python310\python.exe -m venv venv (location of python)
- venv\Scripts\activate (to activate)
- pip install AI_Software_Development_Kit_v2.1.0/simaticai-2.1.0-py3-none-any.whl (install sdk package)

### Venv & SDK setup Linux (wsl):

- python -m venv venv (with preinstalled python 3.10 and active version 3.10)
- source venv/bin/activate (to activate)
- pip install AI_Software_Development_Kit_v2.1.0/simaticai-2.1.0-py3-none-any.whl (install sdk package)




### WSL


- sudo update-alternatives --config python

## Resources and Documentation

- [AI Software Development Kit](https://support.industry.siemens.com/cs/document/109810711/ai-software-development-kit-?dti=0&lc=en-NO) - Here you can download the SDK and and manuals/release notes for the different versions.
- [AI SDK tutorials GitHub](https://github.com/industrial-edge/ai-sdk-tutorials) - This includes all cind of guides on setup to packaging for AI Inference Server. 
- [Introduction to AI Software Development Kit](https://docs.industrial-operations-x.siemens.cloud/r/en-us/ai-sdk-operation-manual/introduction/introduction-to-ai-software-development-kit) - Documentation and manual for AI SDK.


## Notes - steps I think I have to do.

- On vertial environment install jupyter notebook + Ipython kernal: https://github.com/siemens/simatic-ai-launcher/tree/master/environments/virtualenv
- with image-classification example ?? 
