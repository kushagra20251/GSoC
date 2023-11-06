# GSoC'23

Hi, I am Kushagra Sharma, and was selected as a GSoC 2023 contributor for OpenPrinting @ The Linux Foundation. My project was adding CPDB support to the Chromium and Firefox print dialogs.

I have managed to add Common Print Dialog Backends (CPDB) support to chromium print dialogs. From Firefox we did not receive upstream support and we hope once chromium is merged we will get upstream support for other print dialog as well. 

The GSoC 2023 program has ended, and my 1 month extension (due to exams and classes) is also about to come to an end. Here's a brief project report.

-----

## Chromium Print dialog

The Chromium print dialog had well defined and well planend interfaces for print backends, and hence adding a new backend was relatively easy and I was furtuante to receive great support from chromium dev team whi are currently reviewing code for merging, There were sereval difficulties I had faced during adding CPDB support to chromium one of them is to add separate pkg config file for CPDB and even for data type conversion from C code to CPP code and setting up build flag to support third party support I had to constantly refer to the other already implemented print backends for help.

The merge request has been created upstream, and is under review as of now:  
(https://chromium-review.googlesource.com/c/chromium/src/+/5007092)

Here is a video for the working demonstration  of CPDB print backend 
(https://drive.google.com/drive/folders/1kMTco74uKhDGTCQN5R8kEgegf06fdPvh?usp=sharing)

-----

## Monthly Reports in OpenPrinting

June - (https://openprinting.github.io/OpenPrinting-News-June-2023/)

July - (https://openprinting.github.io/OpenPrinting-News-July-2023/)

August - (https://openprinting.github.io/OpenPrinting-News-August-2023/)

September - (https://openprinting.github.io/OpenPrinting-News-September-2023/)

October - (https://openprinting.github.io/OpenPrinting-News-October-2023/)

-----

## Word of Thanks

I would like to thank [@till](https://github.com/tillkamppeter) for his continous and quick support throughout the GSoC period in all areas and chromium dev team for patiently answered all the querries and last but not the least I would like to thank Gaurav Guleria for his unwavering support and guidance, without his assistance and spending countless hours cramming documentation and resolving errors it was amazing haivng a friend and a mentor alongside.
