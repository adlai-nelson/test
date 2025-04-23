# test

<details>
 
<summary><h3>Folder Setup</h3></summary>
 
1) Create a folder labelled 'Moore' in your PCs data drive.

![image](https://github.com/user-attachments/assets/f4114424-de88-45c0-a2e0-ca8516849279)


2) The Moore folder should contain GIS_Files (downloaded from canvas) and a folder for each country we're working in.

![image](https://github.com/user-attachments/assets/f25117ec-1982-4676-8e09-05d91508468f)

3) As quads are assigned, create a new folder with the quad number as a label within the relevant country folder.

![image](https://github.com/user-attachments/assets/eef90db7-2e3f-410b-bb7e-83e96db19c37)


3) Within each quad folder, there should be two folders: 'resources' and 'working'. Place each of the layers from sandy into the Resources folder.

![image](https://github.com/user-attachments/assets/a58dcf4e-530b-40db-a027-fecb5107f85a)


###  Setting up a project in Terrset

1) In Terrset, right click in the empty space of the 'projects' tab and select 'New Project'

![image](https://github.com/user-attachments/assets/c0051a12-4a76-4590-b35e-0e9fa6d28f0c)


2) Navigate to the working folder within the quad you're working on.

![image](https://github.com/user-attachments/assets/61ff0760-9e7c-45f4-b567-c54ceae8f581)

3) Change the name of the project from 'working' to the quad number

![image](https://github.com/user-attachments/assets/bfb0389e-334f-48d1-a741-55d774e9628f)

4) Add the resources and gis_files folders as resource folders. The completed setup should look like this.

![image](https://github.com/user-attachments/assets/f9506303-4997-4f79-b581-83a8d33a6620)

5) Start digitizing!


 
</details>



<details>
<summary><h3>Layer Description</h3></summary>

## Layer Description

![image](https://github.com/user-attachments/assets/0f43b00b-0b62-47e7-9e7e-79833aa70565)

Sentinel 1 Imagrey:

Imagrey from Synthetic Apereature Radar (SAR) sensor from Sentinel 1 sattelites, indicates the relatively smoothness of ground cover.


![image](https://github.com/user-attachments/assets/5c99cd7f-b64a-46be-bbf6-b4117619f5b5)

Tasseled Cap Wetness:

The [tasseled cap](https://yceo.yale.edu/tasseled-cap-transform-landsat-8-oli) transformation results in images representing the greenness, wetness, and brightness of an image.

![image](https://github.com/user-attachments/assets/3fd7206a-7b64-4605-8085-188ee5803222)

Mask:

This image masks a quad to the study area.



| Layer Name                 | Description            | Preview      | 
|----------------------------|----------------------|-----------------|
| ![image](https://github.com/user-attachments/assets/3fd7206a-7b64-4605-8085-188ee5803222)     | Mask of Study area |  ![image](https://github.com/user-attachments/assets/a22d9554-a2aa-48ee-a014-2e61d5f0e1ba) |
| ![image](https://github.com/user-attachments/assets/0f43b00b-0b62-47e7-9e7e-79833aa70565)     | Sentinel-1 [Synthetic Aperature Radar](https://www.earthdata.nasa.gov/learn/earth-observation-data-basics/sar) (SAR)              |       n/a       | 
| NY and PA roads            | line                 |          n/a    | 
| Eastern Hemlock Basal Area | raster image         | 250 m           |
| Temperature                | raster images        | 2.5 arc minutes | 
| Terrain Products           | raster images       | 90 meters       |               
|  ![image](https://github.com/user-attachments/assets/8b49c643-3765-4533-b7e0-a2301a59aed7)       | raster images        | 2.5 arc minutes | 

 </details>
