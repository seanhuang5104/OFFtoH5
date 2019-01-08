# OFFtoH5
Convert ModelNet .OFF files to .h5 files for PointCoud project

IF YOU ARE LOOKING FOR OFFICIAL WAY TO CONVERT THE FILE HERE IS THE LINK , GO TO FILE 'modelnet_dataset.py' it explains everything.(but you still need PCLto convert first)
https://github.com/charlesq34/pointnet2.git
Below is my personal record of finding a way to convert before realizing the link above.


PointNet project by Charles R. Qi, Hao Su, Kaichun Mo, Leonidas J. Guibas from Stanford University.
https://github.com/charlesq34/pointnet

During the study of this project,We need to prepare our own model for training or using existing models lik ModelNet10.
Conversion of the model files is needed since the dataset only contains endpoints of the model.
To populate the dataset with random points on model surfaces for better prediction , PCL tool is required.
This notebook records the steps of the conversion for future reference.

One tool in PointCloudLibrary(PCL) is needed,please download and install it first.
The version I use is 1.9.1,eariler version may have issue importing .ply files.
http://www.pointclouds.org/documentation/
