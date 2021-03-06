The code extracts trees from point clouds.

Usage:
make all
./extractTrees data_file labels.pcd trees.pcd

Example:
./extractTrees data/oakland_part2_ac.xyz_label_conf labels.pcd trees.pcd


labels.pcd will have the labeled point cloud.

trees.pcd will store the extracted trees.

pcd files can be viewed using pcl_viewer.


Theory:

Geometric Description are calculated for every point.
Probabilistic Relaxation is applied.
Spatial filtering and smoothing.


Result:

![picture](data/img.png)



References:

Monnier, Fabrice, Bruno Vallet, and Bahman Soheilian. "Trees detection from laser point clouds acquired in dense urban areas by a mobile mapping system." Proceedings of the ISPRS Annals of the Photogrammetry, Remote Sensing and Spatial Information Sciences (ISPRS Annals), Melbourne, Australia 25 (2012): 245-250.

Demantke, Jerome, et al. "Dimensionality based scale selection in 3D lidar point clouds." The International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences 38.Part 5 (2011): W12.

Zhong, Ruofei, et al. "A method for extracting trees from vehicle-borne laser scanning data." Mathematical and Computer Modelling 58.3 (2013): 733-742.
