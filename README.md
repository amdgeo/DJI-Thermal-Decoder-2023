# DJI-Thermal-Decoder
## Functionality
1. Convert H20T thermal photos to tiff using the DJI Thermal SDK
2. Copy over original EXIF data

## Instructions
1. Download repository from the following link: https://github.com/amdgeo/DJI-Thermal-Decoder-2023/archive/refs/heads/main.zip
2. Extract the ZIP
3. Put H20T thermal images in the 'input' folder
4. Double-click _RUN.exe_.
5. The _output_ folder will be generated where the resultant tiff files are located.

 It is possible to run from source (RUN.py), but this will require Python 3 and installing additional libraries from PIP.
 
 Full credit to https://github.com/radekszostak/DJI-Thermal-Decoder/ for the original code. This update uses the latest DJI Thermal SDK (v1.4) which makes it compatible with the Mavic 2 Enterprise Advanced thermal imagery
