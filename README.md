# MTSD
Mountain Tunnel Semantic Segmentation Dataset.

All pointclouds data are provided in txt files. 
Currently, only a subset of the dataset is publicly available. The full dataset will be released after the publication of our paper.

(1) Construction-stage tunnel dataset
All point clouds were processed using centerline-based sampling and subsequently divided into segments. The resulting files are named "Part_num". 
Each file contains seven columns without a header, arranged in the following order: x, y, z, r, g, b, label.

(2) Operation-stage tunnel dataset.
The filenames follow a specific naming convention: 
The first letter indicates the tunnel cross-sectional shape, with C denoting circular tunnels and S denoting square tunnels. 
The second letter indicates the scanner type, with T denoting a terrestrial laser scanner (TLS) and S denoting a handheld SLAM-based scanner. 
If a third letter is present, L indicates that the scanning was conducted under sufficient illumination.

All files are provided without headers. The column arrangements differ according to the scanning method:
TLS point clouds: x, y, z, intensity, label.
SLAM-based point clouds: x, y, z, r, g, b, label.

The dataset can be downloaded via:
https://zenodo.org/records/23826345?token=eyJhbGciOiJIUzUxMiJ9.eyJpZCI6ImJkNTEyMzY4LTM3MjYtNGUwMS1iYmU0LTNmMzM3NGM5NTcxMCIsImRhdGEiOnt9LCJyYW5kb20iOiI5MzE0M2U5NjMxYWMwMjNkOGE0N2M0NjBlZDZhNDA1NSJ9.11KNMopiwJszhlAgNXQim65sSO_eCSfmRT00mXpggY_d1I8q26_twXsraJNMmD5wsyFeoy4zWiT_NPV1jyfSCg
