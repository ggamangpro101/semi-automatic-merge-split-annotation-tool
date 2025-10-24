# SMAT: Semi-automatic Merge–Split Annotation Tool
> A GUI tool for anomaly-centric video annotation with [YOLO](https://github.com/ultralytics/ultralytics) + [SAM2](https://github.com/facebookresearch/sam2) + [XMem++](https://github.com/mbzuai-metaverse/XMem2) and an automatic Merge–Split mechanism.

## Features  
- YOLO detection → SAM2 segmentation → XMem++ tracking  
- Automatic **Merge–Split** for interaction (group-level) boxes  
- Export: structured **TXT** + overlay **MP4**  

<img src="https://github.com/ggamangpro101/semi-automatic-merge-split-annotation-tool/blob/master/images/annotation_tool.png" height="80%"/>

This repository demonstrates Semi-Automatic Merge-Split Annotation Tool (SMAT).  
Public release coming shortly: stable builds, documentation, and sample workflows will will be available soon.  
Thank you.

Annoation Process Example  
<img src="https://github.com/ggamangpro101/semi-automatic-merge-split-annotation-tool/blob/master/images/Annotation_Tool_v2.png" height="80%"/>  

Full Annotation Process :  
YOLO Object detection --> Apply Bounding box --> SAM 2 Segmentation --> XMem++ Tracking --> Merge-Split --> Export (.txt/.mp4)
<img src="https://github.com/ggamangpro101/semi-automatic-merge-split-annotation-tool/blob/master/images/AT_process.png" height="80%"/>

