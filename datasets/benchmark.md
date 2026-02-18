### Checked and Useable

| Name | 3D model | Terrain Data (DTM) | Segmentation | Pose | RGB image | Real / synthetic | Link |
| --- | --- | --- | --- | --- | --- | --- | --- |
| OrthoLoC | Yes (DSM) | No | - | Yes (6-DoF) | Yes | Real | ([cvg.cit.tum.de][3]) |
| UseGeo | Yes (LiDAR / point cloud + depth) | No | - | Yes (OPK + UTM) | Yes | Real | ([UseGeo data][4]) |
| UAVScenes | Yes (LiDAR) | No | Yes (semantic) | Yes (6-DoF) | Yes | Real | ([GitHub][5]) |
| FlyAwareV2 | Yes (Depth; multimodal) | No | Yes (semantic) | - | Yes | Mixed | ([GitHub][9]) |
| UAVid | - | No | Yes (semantic) | - | Yes | Real | ([DatasetNinja][20]) |
| FloodNet | - | No | Yes (semantic) | - | Yes | Real | ([DatasetNinja][21]) |
| AeroScapes | - | No | Yes (semantic) | - | Yes | Real | ([DatasetNinja][19]) |
| SynDrone (Syndrone) | Yes (Depth + LiDAR) | No | Yes (semantic) | Yes (camera extrinsics) | Yes | Synthetic | ([GitHub][8]) |
| GrAco | Yes (LiDAR) | No | - | Yes | Yes | Real | ([GitHub][7]) |
| Semantic Drone Dataset | - | No | Yes (semantic) | - | Yes | Real | ([Kaggle][18]) |

### checked and is not useable

| Name | 3D model | Terrain Data (DTM) | Segmentation | Pose | RGB image | Real / synthetic | Link | Downloadable |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Mid-Air | Yes (depth) | No | Yes | Yes | Yes | Synthetic | ([midair.ulg.ac.be][6]) | Yes | Low quality of 3D model (per your note) |
| WildUAV | Yes (3D recon / depth-related) | No | - | Yes | Yes | Real | ([GitHub][1]) | No | Access via request form (not “open download”) |
| DenseUAV | - | No | - | - | Yes | Real | ([GitHub][37]) | No | Upon request |
| LASED | - | No | - | - | Yes | Real | ([GitHub][38]) | No | Not released |
| VDUAV | - | No | - | - | Yes | Real | ([Paper][39]) | No | Upon request / unclear public download |
| CS-UAV | - | No | - | - | Yes | Real | ([arXiv][40]) | No | Not available |
| UL14 | - | No | - | - | Yes | Real | ([SemanticScholar][41]) | No | No public download found |
| UVL-R2P | - | No | - | - | Yes | Real | ([IEEE][42]) | No | No public download found |
| Multi-UAV dataset | - | No | - | - | Yes | Real | ([MDPI][43]) | No | Upon request |
| ComplexUAV | - | No | - | - | Yes | Real | ([GitHub][49]) | No | Requires contacting authors |
| GauU-Scene V2 | Yes (LiDAR) | No | - | - | Yes | Real | ([Google Form][48]) | No | Requires request/approval (not open download) |
| OpenFly | Yes (toolchain + dataset) | No | - | Yes | Yes | Mixed | ([Project][47]) | No | “Will be open-sourced” (not released) |
| VLA-3D | Yes (3D scans / point clouds) | No | Yes | - | - | Mixed | ([GitHub][53]) | Yes | Not an aerial/UAV dataset (indoor 3D scenes) |
| ALTO | - | No | - | Yes (geo/INS-style pose) | Yes | Real | ([Project][10]) |
| EuRoC MAV | - | No | - | Yes (trajectory) | No (grayscale) | Real | ([ASL ETH][12]) |
| DOTA | - | No | No (bbox only) | - | Yes | Real | ([DOTA][13]) |
| AUAIR | - | No | No (bbox only) | - | Yes | Real | ([AUAIR][14]) |
| MUN-FRL | Yes (LiDAR) | No | - | Yes | Yes | Real | ([Docs][31]) |
| iSAID | - | No | Yes (instance) | - | Yes | Real | ([iSAID][52]) | Yes |
| ISPRS Potsdam (2D Sem. Labeling) | Yes (DSM) | No | Yes (semantic) | - | Yes (orthophoto) | Real | ([ISPRS][50]) | Yes |
| ISPRS Vaihingen (2D Sem. Labeling) | Yes (DSM) | No | Yes (semantic) | - | Yes (orthophoto) | Real | ([ISPRS][51]) | Yes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| CrossLoc | Yes (simulated LiDAR / depth) | No | - | Yes | Yes | Synthetic | ([GitHub][22]) | Yes |
| UAV-VisLoc (VisLoc) | - | No | - | Yes (geo pose) | Yes | Real | ([GitHub][11]) | Yes |
| VisDrone | - | No | No (bbox only) | - | Yes | Real | ([GitHub][16]) | Yes |
| UAVDT | - | No | No (bbox only) | - | Yes | Real | ([Zenodo][15]) | Yes |
| DroneVehicle | - | No | No (bbox only) | - | Yes (+IR) | Real | ([GitHub][29]) | Yes |
| CARPK | - | No | - | - | Yes | Real | ([CARPK][17]) | Yes |
| STPLS3D | Yes (LiDAR / mixed) | No | Yes (3D semantic) | - | Yes | Mixed | ([GitHub][23]) | Yes |
| Hessigheim 3D | Yes (LiDAR) | No | Yes (semantic) | - | Yes | Real | ([IFP Stuttgart][28]) | Yes |
| UrbanScene3D | Yes (textured meshes / 3D scenes) | No | Yes (instance available) | Yes | Yes | Mixed | ([GitHub][30]) | Yes |
| SensatUrban | Yes (LiDAR / point cloud) | No | Yes (3D semantic) | - | Yes | Real | ([GitHub][33]) | Yes |
| CityNav | Yes (3D point cloud / sim city) | No | - | Yes | Yes (RGB-D) | Mixed | ([GitHub][32]) | Yes |
| SUES-200 | - | No | - | Yes (geo-tag pairs) | Yes | Real | ([GitHub][25]) | Yes |
| HazyDet | - | No | No (bbox only) | - | Yes | Real | ([GitHub][26]) | Yes |
| UAVD4L | - | No | - | Yes | Yes | Real | ([GitHub][27]) | Yes |
| AnyVisLoc | - | No | - | - | Yes | Real | ([GitHub][45]) | Yes |
| CVUSA | - | No | - | Yes (GPS pairing) | Yes | Real | ([Kaggle][34]) | Yes |
| VIGOR | - | No | - | Yes (GPS pairing) | Yes | Real | ([GitHub][35]) | Yes |
| University-1652 | - | No | - | Yes (geo pairing) | Yes | Real | ([GitHub][36]) | Yes |
| RealUAV | - | No | - | - | Yes | Real | ([GitHub][44]) | Yes |
| UAV-VLA (UAV-VLPA-nano-30) | - | No | - | Yes (lat/long metadata) | Yes | Real | ([GitHub][47]) | Yes |
| DALES | Yes (airborne LiDAR) | No | Yes (3D semantic) | - | - | Real | ([DALES][2]) | Yes |
| TravelUAV (OpenUAV / VLN platform) | Yes (sim environments) | No | - | Yes | Yes | Synthetic | ([GitHub][46]) | Yes |


---

[1]: https://github.com/hrflr/wuav "WildUAV (access via request form)"
[2]: https://sites.google.com/a/udayton.edu/vasari1/research/earth-vision/dales "DALES"
[3]: https://cvg.cit.tum.de/webshare/g/papers/Dhaouadi/OrthoLoC/ "OrthoLoC"
[4]: https://usegeo.fbk.eu/data "UseGeo dataset page"
[5]: https://github.com/sijieaaa/UAVScenes "UAVScenes"
[6]: https://midair.ulg.ac.be/ "Mid-Air"
[7]: https://github.com/SYSU-RoboticsLab/GrAco "GrAco"
[8]: https://github.com/LTTM/Syndrone "SynDrone (Syndrone)"
[9]: https://github.com/LTTM/FlyAwareV2 "FlyAwareV2"
[10]: https://metaslam.github.io/datasets/alto/ "ALTO"
[11]: https://github.com/IntelliSensing/UAV-VisLoc "UAV-VisLoc"
[12]: https://projects.asl.ethz.ch/datasets/doku.php?id=kmavvisualinertialdatasets "EuRoC MAV"
[13]: https://captain-whu.github.io/DOTA/dataset.html "DOTA"
[14]: https://bozcani.github.io/auairdataset "AUAIR"
[15]: https://zenodo.org/records/14575517 "UAVDT"
[16]: https://github.com/VisDrone/VisDrone-Dataset "VisDrone"
[17]: https://datasets.activeloop.ai/docs/ml/datasets/carpk-dataset/ "CARPK"
[18]: https://www.kaggle.com/datasets/awsaf49/semantic-drone-dataset "Semantic Drone Dataset"
[19]: https://datasetninja.com/aeroscapes#download "AeroScapes"
[20]: https://datasetninja.com/uavid "UAVid"
[21]: https://datasetninja.com/floodnet "FloodNet"
[22]: https://github.com/TOPO-EPFL/CrossLoc "CrossLoc"
[23]: https://github.com/meidachen/STPLS3D "STPLS3D"
[24]: https://github.com/RussRobin/VDD "VDD"
[25]: https://github.com/Reza-Zhu/SUES-200-Benchmark "SUES-200"
[26]: https://github.com/GrokCV/HazyDet "HazyDet"
[27]: https://github.com/RingoWRW/UAVD4L "UAVD4L"
[28]: https://ifpwww.ifp.uni-stuttgart.de/benchmark/hessigheim/default.aspx "Hessigheim 3D"
[29]: https://github.com/VisDrone/DroneVehicle "DroneVehicle"
[30]: https://github.com/yilinliu77/UrbanScene3D "UrbanScene3D"
[31]: https://mun-frl-vil-dataset.readthedocs.io/en/latest/ "MUN-FRL"
[32]: https://github.com/water-cookie/citynav "CityNav"
[33]: https://github.com/QingyongHu/SensatUrban "SensatUrban"
[34]: https://www.kaggle.com/datasets/erkappo/cvusa-dataset "CVUSA"
[35]: https://github.com/Jeff-Zilence/VIGOR "VIGOR"
[36]: https://github.com/layumi/University1652-Baseline "University-1652"
[37]: https://github.com/Dmmm1997/DenseUAV "DenseUAV (upon request)"
[38]: https://github.com/ipapap/Visual-Place-Recognition-for-Large-Scale-UAV-Applications "LASED (not released)"
[39]: https://www.mdpi.com/1424-8220/24/21/6905 "VDUAV paper"
[40]: https://arxiv.org/pdf/2506.09748 "CS-UAV paper"
[41]: https://www.semanticscholar.org/paper/Finding-Point-with-Image%3A-An-End-to-End-Benchmark-Dai-Chen/bb2d692f68804ba37f950959bca43d18d23f3fa7 "UL14 paper page"
[42]: https://ieeexplore.ieee.org/abstract/document/11172695 "UVL-R2P paper page"
[43]: https://www.mdpi.com/2504-446X/9/5/379 "Multi-UAV dataset paper"
[44]: https://github.com/Arancew/RealUAV "RealUAV"
[45]: https://github.com/UAV-AVL/Benchmark "AnyVisLoc"
[46]: https://github.com/prince687028/TravelUAV "TravelUAV (OpenUAV / VLN)"
[47]: https://shailab-ipec.github.io/openfly/ "OpenFly"
[48]: https://docs.google.com/forms/d/e/1FAIpQLSfy4835PDjp28WpFvAl_k4Izx88jbvnxw5TmJmLCCRCxiFbDA/viewform "GauU-Scene V2 request form"
[49]: https://github.com/cjl-2000/ComplexUAV "ComplexUAV (contact author)"
[50]: https://www.isprs.org/resources/datasets/benchmarks/UrbanSemLab/2d-sem-label-potsdam.aspx "ISPRS Potsdam (2D semantic labeling)"
[51]: https://www.isprs.org/resources/datasets/benchmarks/UrbanSemLab/2d-sem-label-vaihingen.aspx "ISPRS Vaihingen (2D semantic labeling)"
[52]: https://captain-whu.github.io/iSAID/dataset.html "iSAID"
[53]: https://github.com/HaochenZ11/VLA-3D "VLA-3D"
