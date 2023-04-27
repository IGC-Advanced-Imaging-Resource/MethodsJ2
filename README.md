# MethodsJ2
MethodsJ2 is a tool which can be used to automatically generate materials &amp; methods text for image data captured on AIR microscopes

Note we are currently in the process of implementing and testing this tool, so not all AIR microscopes are available yet. If you cannot find a .json file for a particular microscope and would like to use MethodsJ2, please email AIR-support@igc.ed.ac.uk. You can still find technical information regarding all our systems at https://igmmimaging.com/equipment/tech-specs/

INSTRUCTIONS


Before you start: you will the following: 
•	ImageJ/FIJI https://imagej.net/software/fiji/downloads

•	MethodsJ2 script (MethodsJ2_v1_2_.py; found at https://github.com/ABIF-McGill/MethodsJ2

•	The .json file for the microscope you used. This can be found at the facility GitHub https://github.com/IGC-Advanced-Imaging-Resource/MethodsJ2.git

•	An example image in its raw format


Step 1: 
Download the MethodsJ2 script (MethodsJ2_v1_2_.py), this can be found at https://github.com/ABIF-McGill/MethodsJ2

Step 2: 
Open ImageJ/FIJI. Drag and drop the above script onto the main console. A script editing window will appear. Click ‘Run’
 
Step 3: 
You will be prompted to upload a representative image. Please use the raw data collected from the microscope in its native format (e.g. .czi for Britemac, .nd2 for SoRa). Click ‘Okay’

You will be prompted to add some useful details of your experiment, e.g. sample holder, coverglass thickness. These are optional and do not appear in your materials & methods text. Click ‘Okay’ when done

Step 4: 
The image dimensions will appear (these are read from your image using Bioformats) – check over them and click ‘Okay’

Step 5: 
You now need to tell MethodsJ2 which microscope was used for the acquisition. Select the .json relating to the microscope you used (e.g. Britemac.json). If you can’t find the microscope you are looking for, please contact the facility (AIR-support@igc.ed.ac.uk)

Confirm that the details of this system are correct (e.g. Zeiss widefield) and click ‘Okay’

Step 6: 
Check that the objective has been recorded correctly (e.g. 63x in the example below). If not, choose the correct objective from the dropdown list. Click ‘Okay’

Step 7: 
Add the channel information. For each channel, you will need to add a name (e.g. DAPI) and add/confirm details such as the filters and light source intensities used

You will also be prompted to check that the recorded exposure time is correct: 

Step 8: 
If relevant, select any other devices that were used (e.g. incubation equipment used for live imaging, etc), click ‘Okay’

Step 9: 
Add necessary details to acknowledge the facility. Add the name of technical staff if they have provided particular help with the acquisition (beyond normal expected training/troubleshooting). It is not necessary to fill in an RRID 

Step 10: 
The resultant materials and methods blurb will be appear in a separate window. These can be saved as a .txt or copied and pasted into a Word document. Make sure that you read over this text for accuracy

