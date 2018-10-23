# KISSlicer-config
KISSlicer Configuration for 3D Printers for ECE OpenLab

## Directions for Use

1. Download `_materials`,  `_styles`, `_printers` and `_supports` folders from this repo for the configuration. _Or just download the repo as a zip_...
2. Download KISSlicer v1.6.3 Free for your computer from http://www.kisslicer.com/download-v16-stable.html and extract the exectuable to the same directory as where you downloaded the above configuration folders.
  Your folder structure should look like:
    ```
     KISSlicer
      ├── KISSlicer64.exe (Or another executable on Linux/macOS)                
      ├── _KS_backup_profiles.ini (Optional)        
      ├── _materials                      
      │   ├── ABS - Generic.ini           
      │   └── PLA - Generic.ini           
      ├── _printers                       
      │   └── MakerGear M2.ini            
      ├── _styles                         
      │   ├── High Quality, Low Speed.ini 
      │   └── Med Quality, Med Speed.ini  
      └── _supports                       
          ├── Dense, Skirt.ini            
          └── None, Skirt.ini             
    ``` 
3. Start KISSlicer. The configuration files from above are suitable for both MakerGear M2s found in OpenLab, but feel free to make change

If you need some help with KISSlicer, documentation for the program can be found at 

 * Quickstart Guide: http://www.kisslicer.com/uploads/1/5/3/8/15381852/kisslicer_quick_reference_en.pdf
 * v1.5 Manual: http://www.kisslicer.com/uploads/1/5/3/8/15381852/kisslicer_manual_en_201015.pdf
 
Although they are a bit old, they should still be suitable for v1.6. The manual also contains a tuning guide that will help you calibrate KISSlicer for your filament/models to produce better results.

## Notes/FAQ

 * You are not required to use KISSlicer for the printers! If you are more familiar with another slicing software e.g. Slic3r, Cura, etc, feel free to use one of those instead. I chose to provide a KISSlicer setup as the software is more stable, produces better parts, and is easier to use compared to Slic3r (It is also what I personally use). 
 * Feel free to edit the given configuration files. They are only provided as a guidline for you to become familiar with the software/3d printing process. Make changes as needed by your parts/designs/materials.
 * This configuration bundle includes starter settings for __PLA__ and __ABS__ based filaments only. You can use other filaments, but keep in mind the max extruder and bed temperatures of 280 deg C and 110 deg C respectively. Please talk with a lab monitor if you need help or have something particularly exotic (e.g. carbon fiber, metal filled, etc...).
 
 ## Customizations
 
 * [__RECOMMENDED__] One of the most important settings is using actual filament diameter of your filament. Although the MakerGear M2s use nominal 1.75 mm diameter filament, actual filament you buy can vary by 0.1 mm or more. Use a caliper (you can check one out, ask a monitor) and enter the measured diameter into KISSlicer material configuration so it can better estimate the filament extrusion. The default values are 1.75, but don't assume this will be the case for you! Additional instructions can be found on page 37 of the manual linked above.

