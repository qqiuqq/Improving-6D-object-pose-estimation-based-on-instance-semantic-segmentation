# Improving-6D-object-pose-estimation-based-on-instance-semantic-segmentation
1. Set up the python environment:
The python environment is the same as [this] (https://github.com/ethnhe/PVN3D)

2. Download datasets:

LineMod:Download the preprocessed LineMOD dataset from here (refer from DenseFusion). Unzip it and link the unzipped
`linemod_prepocessed/` to `/Pointcloud_feature/datasets/linemod/' (`Instance/instance_module/datasets/linemod/`)

YCB-Video:Download the YCB-Video Dataset from PoseCNN. Unzip it and link the unzipped `YCB_Video_Dataset` to `/Pointcloud_feature/datasets/ycb/`(`Instance/instance_module/datasets/ycb/`)

3.Run the model:
```
cd 
./experiments/scripts/eval_ycb_icp.sh 
./experiments/scripts/eval_linemod_icp.sh
```
