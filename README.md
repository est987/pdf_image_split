# pdf_image_split 

 crop pdf margins and split into equal size images;  ver 0.0.1 

 
**Install Instructions:**\
See https://pypi.org/project/pdf2image/ for poppler installation instructions (Windows make sure to add bin to PATH)
 ```
#pip install pdf2image
conda install -c conda-forge poppler 
```

 **Variables:**
 * pdf_path: path of pdf to split
 * width_sections=2: # horizontal sections
 * height_sections=3: # vertical sectors
 * w_margin_pct=0: % width to crop (half on each side)
 * h_margin_pct=0:  % height to crop (half on each side)
 * savepath='': Folder to save split images):
 * right_to_left=False: Starts splitting from top right to left Default splits from left to right. Both split top to bottom
   
 
