# WIS Benchmark
The frames are extracted from 200 video segments in the Waymo Open Dataset (WOD) validation set. 
We provide instance annotation in COCOformat for testing.
The maximum number of masks in a picture is 66, and the average number of masks per image is 12.
All instance masks are annotated in the form of polygon points.
For instances that are divided into multiple parts due to occlusion, we label them separately and link them to the same instance ID. We select 10 frames in each video segment. 
Specifically, we choose frame indexes at 0,20,40,60,80,100,120,140,160,180 for manual annotation.