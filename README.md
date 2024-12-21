# 3D-Object-Classification
Classifying the different objects given the point cloud points.

## Description:
A *Point Cloud* is a set of 3D points that are invariant to both order and rigid motion, they also comprise meaningful structures within the cloud. Point clouds don’t have any ordering, we can shuffle the (x,y,z) points all we want, but we will still have the exact same point cloud. Neighboring points form meaningful structures (attributes), as a major utility of Point Cloud Processing is that it captures these spatial structures and encodes them as features in lower dimensional space. Using these point clouds of different objects, we utilize **PointNet** to classify these clouds into respective objects.

![Point_cloud_torus](https://github.com/user-attachments/assets/32394490-bbdf-432a-906e-40129ab9b9c9) [Source](https://en.wikipedia.org/wiki/Point_cloud) 

***PointNet***, provides a unified architecture for applications ranging from object classification, part segmentation, to scene semantic parsing. Being simple, PointNet is highly efficient and effective, that directly consumes point clouds, which well respects the permutation invariance of points in the input. Empirically, it shows strong performance on par or even better than state of the art.

## Dataset: 
[ModelNet10](https://www.kaggle.com/datasets/balraj98/modelnet10-princeton-3d-object-dataset/data)

## References:
1. [PointNet paper](https://arxiv.org/pdf/1612.00593).
2. [Kaggle](https://www.kaggle.com/code/balraj98/pointnet-for-3d-object-classification-pytorch).
3. [Medium](https://medium.com/@itberrios6/introduction-to-point-net-d23f43aa87d2).

## Contain:
* 3D-object-detection.ipynb.
