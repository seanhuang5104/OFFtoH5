# OFFtoH5
Convert ModelNet .OFF files to .h5 files for PointCoud project

PointNet project by Charles R. Qi, Hao Su, Kaichun Mo, Leonidas J. Guibas from Stanford University.
https://github.com/charlesq34/pointnet

During the study of this project,We need to prepare our own model for training or using existing models lik ModelNet10.
Some conversion of the model files are needed since it is .OFF format and only contains endpoints of the model.
Need to populate the dataset with random points on model surfaces for better prediction which requires PCL tool.
This notebook is to record the steps of the conversion for future reference.

One tool in PointCloudLibrary(PCL) is needed,please download and install it first.
The version I use is 1.9.1,eariler version may have issue importing .ply files.
http://www.pointclouds.org/documentation/
