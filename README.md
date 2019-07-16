# Multi-Template-Matching
Multi-Template-Matching is a package to perform object-recognition in images using one or several smaller template images.  
The template and images should have the same bitdepth (8,16,32-bit) and number of channels (single/Grayscale or RGB).  
The main function `MTM.matchTemplates` returns the best predicted locations provided either a score_threshold and/or the expected number of objects in the image.  

# Installation
Using pip, `pip install Multi-Template-Matching`  
Once installed, `import MTM`should work.

# Documentaion
Check out the [jupyter notebook tutorial](https://github.com/LauLauThom/Multi-Template-Matching/blob/master/Tutorial.ipynb) for some example of how to use the package.  
The [wiki](https://github.com/LauLauThom/MultiTemplateMatching/wiki) section of this related repository also provides some information about the implementation.

# Citation
If you use this implementation for your research, please cite:
  
_Multi-Template Matching: a versatile tool for object-localization in microscopy images;_  
_Laurent SV Thomas, Jochen Gehrig_  
bioRxiv 619338; doi: https://doi.org/10.1101/619338

# Related projects
See this [repo](https://github.com/LauLauThom/MultiTemplateMatching) for the implementation as a Fiji plugin.  
[Here](https://nodepit.com/workflow/com.nodepit.space%2Flthomas%2Fpublic%2FMulti-Template%20Matching.knwf) for a KNIME workflow using Multi-Template-Matching.


# Origin of the work
This work has been part of the PhD project of **Laurent Thomas** under supervision of **Dr. Jochen Gehrig** at:  
  
ACQUIFER a division of DITABIS AG  
Digital Biomedical Imaging Systems AG  
Freiburger Str. 3  
75179 Pforzheim  

<img src="https://github.com/LauLauThom/Multi-Template-Matching/blob/master/images/Acquifer_Logo_60k_cmyk_300dpi.png" alt="Fish" width="400" height="80">     

# Funding
This project has received funding from the European Union’s Horizon 2020 research and innovation program under the Marie Sklodowska-Curie grant agreement No 721537 ImageInLife.  

<p float="left">
<img src="https://github.com/LauLauThom/Multi-Template-Matching/blob/master/images/ImageInlife.png" alt="ImageInLife" width="130" height="100">
<img src="https://github.com/LauLauThom/Multi-Template-Matching/blob/master/images/MarieCurie.jpg" alt="MarieCurie" width="130" height="130">
</p>
