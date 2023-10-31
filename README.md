# LSDSSIMR
[LSDSSIMR: Large-Scale Dust Storm Database Based on Satellite Images and Meteorological Reanalysis Data](https://doi.org/10.1109/JSTARS.2023.3325783)

## Abstract
Since meteorological satellites can observe the Earth’s atmosphere from a spatial perspective at a large scale, in this paper, a dust storm database is constructed using multi-channel and dust label data from the Fengyun-4A (FY-4A) geosynchronous orbiting satellite, namely, the Large-Scale Dust Storm database based on Satellite Images and Meteorological Reanalysis data (LSDSSIMR), with a temporal resolution of 15 minutes and a spatial resolution of 4 km from March to May of each year during 2020–2022. Meteorological reanalysis data are added to LSDSSIMR for spatiotemporal prediction methods. Each data file is stored in HDF5 format, and the final LSDSSIMR contains nearly 10,000 HDF5 files. Moreover, some traditional dust detection methods based on spectral analysis are executed as a benchmark.

## Introduction
LSDSSIMR is a database for dust storms from March to May during 2020–2022, with a temporal resolution of 15 minutes and a spatial resolution of 4 km. The data are saved as HDF5 format files. Each HDF5 file contains satellite multichannel observation Level 1 data and dust detection scoring Level 2 data. The results of traditional spectral analysis dust detection methods such as brightness temperature adjusted dust index (BADI), infrared difference dust index (IDDI), and normalized difference dust index (NDDI) are added to the LSDSSIMR, which can be used as a benchmark for dust detection in the future. In addition, 5 the LSDSSIMR includes hourly atmospheric reanalysis data from MERRA-2 and ERA-5. Based on these data, the LSDSSIMR can be used as a database for detecting, monitoring, and predicting dust storms.

## Download
The database data format is HDF5. Please download the data files from BaiduYun or IEEE DataPort.
- BaiduYun: https://pan.baidu.com/s/1eIsQZ_EUR2il-7pS0tU-bA?pwd=p4xw
- IEEE DataPort: https://ieee-dataport.org/documents/lsdssimr-large-scale-dust-storm-database-based-satellite-images-and-meteorologicall#

## Citation
Please cite our papers if the database is useful for you. Thank you !

C. Bai, Z. Cai, X. Yin and J. Zhang, "LSDSSIMR: Large-Scale Dust Storm Database Based on Satellite Images and Meteorological Reanalysis Data," in IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing, doi: 10.1109/JSTARS.2023.3325783.

```
@ARTICLE{Bai2023LSDSSIMR,
  author={Bai, Cong and Cai, Zhipeng and Yin, Xiaomei and Zhang, Jinglin},
  journal={IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing}, 
  title={LSDSSIMR: Large-Scale Dust Storm Database Based on Satellite Images and Meteorological Reanalysis Data}, 
  year={2023},
  volume={},
  number={},
  pages={1-11},
  doi={10.1109/JSTARS.2023.3325783}
}
```
