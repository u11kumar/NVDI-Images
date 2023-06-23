# Generate NDVI (Normalized Difference Vegetation Index) Images from Sentinel-2 AWS Dataset.
__________________________________________________________________________________________________________________________________
“Normalized Difference Vegetation Index (NDVI) quantifies vegetation by measuring the difference between near-infrared (which vegetation strongly reflects) and red light (which vegetation absorbs).”
_________________________________________________________________________________________________________________________________

This code will generate NVDI Images using the desired coordinates from bboxfinder.com and pulling data from the Sentinel-2 Satelite(AWS Open Dataset).

#Steps:-
Step 1:
Import all the Libraries and Create a free account on "https://apps.sentinel-hub.com/dashboard/#/account/settings" for credentials.
Step 2:
Go to bboxfinder.com and get the exact box coordinates .
Step 3 :
Input the coordinates in bbox function and mention date in time interval function.
We can change the Image format from jpg to png as well by just providing the full file name in 

responses=[
        SentinelHubRequest.output_response('default', MimeType.PNG),
    ],

All the output will be saved in a folder named in data_folder function.
Step 4:
Generate Images can be found in the folder .


## Screenshots

![FireShot Capture 001 - NEW - Jupyter Notebook - localhost](https://github.com/u11kumar/NVDI-Images/assets/47977758/cc91820c-5368-49f2-8ad9-ed2251246fc5)



'''
"http://bboxfinder.com/#0.000000,0.000000,0.000000,0.000000" for coordinates
"https://sentinelhub-py.readthedocs.io/en/latest/configure.html" for docs
"https://apps.sentinel-hub.com/dashboard/#/account/settings" for credentials
'''


# Download Full Project in Zip File
# https://anonfiles.com/2cU6m9y1z7/NVDI_images_7z

# Watch the whole video to get idea how to generate image.
# https://anonfiles.com/49U1mdyezb/2023_05_24_10_21_13_mkv
