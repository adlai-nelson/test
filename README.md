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

Below is a description of each ogh the images used in digitizing mangroves.


| Layer Name                 | Description            | Preview      | 
|----------------------------|----------------------|-----------------|
| ![image](https://github.com/user-attachments/assets/3fd7206a-7b64-4605-8085-188ee5803222)     | Mask of Study area. <br> The study area for this project is 10 km on eihter side of the coast line, extending up to 60 km inland in low elevation areas.  |  ![image](https://github.com/user-attachments/assets/a22d9554-a2aa-48ee-a014-2e61d5f0e1ba) |
| ![image](https://github.com/user-attachments/assets/0f43b00b-0b62-47e7-9e7e-79833aa70565)     | Sentinel-1 [Synthetic Aperature Radar](https://www.earthdata.nasa.gov/learn/earth-observation-data-basics/sar) (SAR). <br> SAR imagery records the relative smoothness of the land surface. For example, the lowest values are found in smooth terrains such as open water and graded construction sites. The highest SAR values are found in complex terrains, such as mountainous terrains and dense urban areas. |    ![image](https://github.com/user-attachments/assets/e1559985-ed03-403f-a473-7adfa8f36492)  | 
| ![image](https://github.com/user-attachments/assets/af67fc90-e199-4fce-99e5-228bbaa108a6)    | Wetness image from the [tasseled cap transformation](https://pro.arcgis.com/en/pro-app/latest/help/analysis/raster-functions/tasseled-cap-function.htm). Note that highest wetness values are located in areas of open water and vegetation. Lowest wetness values are found in crop fields and built-up areas.    |  ![image](https://github.com/user-attachments/assets/097ebb71-1b8c-4d2f-9b7f-6c40bc97d894)  | 
|![image](https://github.com/user-attachments/assets/b095d101-0ae3-4334-9451-4512a104d75c) | False color composite using red, near infrared, and shortwave infrared bands. <br> Note that mangroves appear as red, other vegetation as orange, crop fields and built-up areas as cyan, and open water as deep blue.    | ![image](https://github.com/user-attachments/assets/769e7b8f-cd1b-441b-9c82-184605797dc2)    |
| ![image](https://github.com/user-attachments/assets/29318205-d965-4ef4-ad7f-e0b861445d3e)         | Landcover layer from previous years to update. <br> Using the provided ‘aqua’ palette, mangroves are deep green, aquaculture is orange, water is light blue, and other is yellow.  | ![image](https://github.com/user-attachments/assets/ced519ed-9a42-4d34-bd4a-b07c9148f74e) | 
| Terrain Products           | raster images       | 90 meters       |               
|  ![image](https://github.com/user-attachments/assets/8b49c643-3765-4533-b7e0-a2301a59aed7)       | raster images        | 2.5 arc minutes | 

 </details>
