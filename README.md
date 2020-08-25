# A Low-cost System for Orchard Mapping Integrating UGV and LiDAR

Growing evaluation in the early stages of crop development can be critical to eventual yield. Pointclouds have been used for this purpose in tasks such as detection, characterization, phenotyping andprediction on different crops with terrestrial mapping platforms based on laser scanning. 3D modelgeneration requires the use of specialized measurement equipment, which limits the access to thistechnology because of their high cost, both hardware elements and software data processing. This work presents the details on each development stage of a low-cost mapping system, which integratesan Unmanned Ground Vehicle UGV and a 2D Hokuyo LiDAR to generate 3D point clouds, allowingthe determination of morphological parameters of the crops. The validation test was carried out on acitrus crop section by a comparison of distance and canopy height values obtained from our generatedpoint cloud with respect to the reference values obtained with conventional methods. By using anassisted processing stage of the generated point clouds, the results provided satisfactory and accuratemeasurements.

This Repository is composed by 3 parts: The development of the robot to collect the data; the data pre-processing and finally the data processing:
* https://github.com/HaroldMurcia/AlphaROVER
* https://gitlab.com/haroldmurcia/alpharover_txt2las
* https://github.com/HaroldMurcia/CropPointCloud_processing
