# Unsupervised surface water mapping using airborne LiDAR Data
### Reproduction and evaluation of the method proposed by Song & Jung (2024)

This repository contains the implementation and visualization of an unsupervised method for surface water extraction from airborne LiDAR data, from the workflow of Song & Jung (2024).  

The project consists of two main Jupyter Notebooks:  
- 📄 airborne-lidar-water-mapping.ipynb – Implements the full WERM-based extraction workflow  
- 📄 lidar-visualization-open3d.ipynb – Visualizes .las/.laz point clouds using Open3D for 3D inspection  

#### Data  

The main dataset used corresponds to:  

USGS FL Peninsular 2018 – Lake County Project, obtained via USGS LidarExplorer: https://www.usgs.gov/tools/lidarexplorer
The specific product used for the analysis was https://rockyweb.usgs.gov/vdelivery/Datasets/Staged/Elevation/LPC/Projects/FL_Peninsular_2018_D18/FL_Peninsular_Lake_2018/LAZ/USGS_LPC_FL_Peninsular_2018_D18_LID2019_244261_E.laz

#### References  
Song, H., & Jung, J. (2024). Unsupervised surface water mapping with airborne LiDAR data by leveraging physical properties of water. GIScience & Remote Sensing.
