RecycleCam is an app created to detect and classify objects as waste or recyclable. This app can be used by anyone interested in being more eco-friendly through improving their recycling habits. Anyone with an Apple device can use it. 

Here are the descriptions to each file used within the project:

CVS_classifierSample.xcworkspace: This file should be opened on xcode to run the app

CVS_classifierSample: This file contains every aspect related to the xcworkspace. Opening each file within this will allow you to edit specific portions of the code. 

Pods: This is the data file downloaded from cocoapods. 

AzureCustomVision: The custom Vision file holds our AI model. 

Podfile: This file contains the cocoapods to download onto your computer before running the code. 

Cvexport.manifest:  Exported details of custom vision model. 

labels.txt: Tag names from Custom Vision Model

metadata_properties.json: Custom Vision Model Details (size)

Prerequisites
Things to have downloaded before using this repository:
- Xcode
- Cocoapods
- CustomVision Model

Githubs used during app development:
- Trashnet (https://github.com/garythung/trashnet)
   - Data used to create AI model
- Cognitive Services (https://github.com/Azure-Samples/cognitive-services-ios-customvision-sample) 
   - Code used for implementation of AI model
