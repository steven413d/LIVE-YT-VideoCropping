# LIVE-YT-VideoCropping
Repository for "Subjective Portrait Region Cropping in Landscape Videos with Temporal Annotation Smoothing" Submit to IEEE Transactions on Image Processing 

This repository contains the LIVE-YouTube Video Cropping Dataset proposed in the paper - ***'Subjective Portrait Region Cropping on Landscape Video Study with Temporal Annotation Smoothing'***. If this work helps in you research, please cite us.

Cheng-Han Lee, Maniratnam Mandal, Neil Birkbeck, Yilin Wang, Balu Adsumilli, Alan C. Bovik, <em>"Subjective Portrait Region Cropping on Landscape Video Study,"</em>

## LIVE-YT-VideoCropping
The dataset can be downloaded from [here](https://utexas.box.com/s/m66xkxgvk9mhvhi88mzo9kdxrnb58nx2). The **'LIVE-YT-VC'** folder has -
1. **study_videos** - 1800 videos sampled from LSVQ and YT-UGC, which we use to collect bounding box labels. From each video, we sample 30 frames, and each frame is labeled by a human subject.
 
2. **video_bbox_labels.csv** - The csv file contains the bounding box labels for each video in the dataset.
   Column descriptions:

  - <em>video</em> - name of the video file.
  - <em>num_scenes</em> - number of scenes detected in the video using PySceneDetect
  - <em>frameN</em> - bounding box labels in a dictionary containing four coordinates. Here 'N' is the frame index.

## LIVE-YT-VideoCropping++
Coming soon.

## Deep Video Reframing Models
Coming soon.
