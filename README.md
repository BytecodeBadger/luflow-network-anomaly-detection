# LuFlow Network Anomaly Detection
This project explores and tests models on the Lancaster University flow-based network intrusion detection data set.  

## Dataset
Kaggle dataset: https://www.kaggle.com/datasets/mryanm/luflow-network-intrusion-detection-data-set/data

### Kaggle Dataset Description  
<i>LUFlow is a flow-based network intrusion detection data set which contains a robust ground truth through correlation of malicious behaviour. LUFlow contains telemetry containing emerging attack vectors through the composition of honeypots within Lancaster University's address space. The labelling mechanism is autonomous and is supported by a robust ground truth through correlation with third part Cyber Threat Intelligence (CTI) sources, enabling the constant capture, labelling and publishing of telemetry to this repository. Flows which were unable to be determined as malicious, but are not part of the normal telemetry profile are labelled as outliers. These are included to encourage further analysis to discover the true intent behind their actions. Normal traffic is also captured from production services, e.g. ssh and database traffic, and included in this data set.

This data set was created with the intention to promote research into detection mechanisms suitable for emerging threats. Critically, this data set is continuously updated due to the automatic labelling mechanism, therefore, it is able to reflect novel and emerging attack patterns.

This repository is structured into the year and month the telemetry was captured. For example, to find telemetry captured within September 2020, the folder 2020/09 is used.</i>