# Convert-CZI-file-to-PNG
This repository provides a Python-based pipeline for processing multi-channel .czi images of mouse brain sections

Mouse brains are often sliced, and stained with antibodies. With the .czi file generated from the microscope, this code input the czi file, renders it with the colour of the fluoresent (you will need to have the RGB code for each of the fluorescent dye! this can be done from any colour picker), merge the channels, and output as png.

It allows batch processing for multiple .czi files, and provides a framework for adjusting brightness/contrast of any of the fluorescent channels
