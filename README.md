
# Course Project | DDOS Detection by naive bayes
The project aims to apply one machine learning (ML) technique to solve an issue in any field.
### Issue description 
**Distributed Denial of service (DDoS)** attacks users from accessing the network and makes services unavailable or only partially available. The attacker floods the targeted machines or resources with excessive requests. The victim's incoming traffic originates from many different sources. Attackers use many (remotely) controlled computers to attack the victim. 
### Machine learning (ML) technique
In this project, we use the [Naive Bayes technique](https://scikit-learn.org/stable/modules/naive_bayes.html) to detect which if the request ddos or benign.
### Dataset
The [Dataset](https://www.kaggle.com/datasets/devendra416/ddos-datasets) is extracted from different IDS datasets that were produced in different years and different experimental DDoS traffic generation tools, it has more than 12 milion records (ddos and benign) and 85 features.
###  Instructions to run notebook
Required packages:

ipaddress
```bash
pip install ipaddress
 ```
seaborn
```bash
pip install seaborn
 ```
pandas
```bash
pip install pandas
```
matplotlib
```bash
pip install matplotlib
```
sklearn
```bash
pip install -U scikit-learn
```




