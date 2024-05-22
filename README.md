# CloudViewer
基于PCL&Qt的点云可视化，类似pcl_viewer和CloudCompare

Description
-----------
The CloudViewer is a standalone, tiny, cross-platform point cloud visualization desktop software powered by [PCL](https://github.com/PointCloudLibrary/pcl) and [Qt](https://www.qt.io/).

You can learn more from this [document](https://github.com/nightn/CloudViewer/tree/master/doc/cloudviewer-detail-zh.md) (only Chinese version until now).

Compiling
---------
Please refer to the platform specific tutorials (Chinese):
 - [Microsoft Windows](https://github.com/nightn/CloudViewer/tree/master/doc/compiling-cloudviewer-windows.md)
 - [Linux](https://github.com/nightn/CloudViewer/tree/master/doc/compiling-cloudviewer-linux.md)
 
Ubuntu18.04 tested

Issues
------
Please use the [Github issue tracker](https://github.com/nightn/CloudViewer/issues) for all bugs and feature requests.

Module
------
AboutWin - about widget
CloudViewer - pcl cloud process
FileIO - support file for pcd ply obj stl vtk etc.
MeshProcessing - PolygenMesh process
MyCloud - basic operate for cloud
Tool - tool function