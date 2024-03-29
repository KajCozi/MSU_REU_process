# MSU_REU
Research in cybersecurity - using random forest based methods to detect anomalies in network data

The need for intrustion detection systems (IDS) is becoming more prevalent in today's world as a direct result of the presence of system vulnerabilities. Malicious adversaries seek to exploit these vulnerabilities to obtain sensitive information, which can be detrimental to users. Detecting these attacks can sometimes be an ambiguous task and is often found to be technically demanding and expensive. One potential solution to improve cybersecurity in this area is anomaly detection. This project focuses specifically on finding abnormalities in network data, thus exposing potential threats.

The availability of datasets is exceptionally limited, mainly for privacy reasons. The data that is accessible often has issues of its own, including missing or noisy data. The KDD cup 99 dataset was artificially created with the purpose of providing a large training set to aid in the creation and evaluation of learning algorithms. Although this dataset is not immune to these challenges, it is a great tool to test various algorithms on. This is our selected dataset for this project. The data contains a variety of attack types that can be classified into the following categories: Denial of Service(DoS), User to Root(U2R), Remote to Local(R2L), and Probing. We use both supervised and unsupervised learning algortihms on this dataset to discover patterns that suggest the presence of these attacks.

Random Forest Classifier, Isolation Forest, Local Outlier Factor(LOF)
