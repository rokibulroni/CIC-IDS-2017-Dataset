
# Phishing Email Forensic Framework & CIC-IDS-2017 PCAP Datasets Repository

This repository hosts open-source datasets and resources essential for analyzing phishing email patterns, developing forensic frameworks, and studying network traffic. These datasets are derived from the **CICDataset/CIC-IDS-2017**, a freely available DDoS traffic dataset from the **Canadian Institute for Cybersecurity (CIC)**. These resources are ideal for building and testing models for phishing detection, intrusion detection systems (IDS), and cybersecurity threat intelligence.

**Source**: [CICIDS2017 Dataset - Canadian Institute for Cybersecurity](https://www.unb.ca/cic/datasets/ids-2017.html)

---

## 📂 Repository Contents

### 1. **CSV Datasets**

#### **GeneratedLabelledFlows**
- **File**: [`GeneratedLabelledFlows.zip`](http://205.174.165.80/CICDataset/CIC-IDS-2017/Dataset/CIC-IDS-2017/CSVs/GeneratedLabelledFlows.zip)  
  - **Description**: A compressed archive containing pre-processed and labeled flow data for phishing detection.
  - **Size**: 271 MB
  - **MD5 Checksum**: [`GeneratedLabelledFlows.md5`](http://205.174.165.80/CICDataset/CIC-IDS-2017/Dataset/CIC-IDS-2017/CSVs/GeneratedLabelledFlows.md5)

#### **MachineLearningCSV**
- **File**: [`MachineLearningCSV.zip`](http://205.174.165.80/CICDataset/CIC-IDS-2017/Dataset/CIC-IDS-2017/CSVs/MachineLearningCSV.zip)  
  - **Description**: A zip file containing CSV datasets formatted for machine learning algorithms, designed to identify phishing patterns and anomalies.
  - **Size**: 224 MB
  - **MD5 Checksum**: [`MachineLearningCSV.md5`](http://205.174.165.80/CICDataset/CIC-IDS-2017/Dataset/CIC-IDS-2017/CSVs/MachineLearningCSV.md5)

---

### 2. **PCAP Files and MD5 Checksums**

| Day         | File Name                           | Size   | Description                          | Download Link                                                                                      | MD5 Checksum                                                                                      |
|-------------|-------------------------------------|--------|--------------------------------------|---------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------|
| Friday      | `Friday-WorkingHours.pcap`          | 8.2 GB | PCAP file for Friday working hours   | [Download](http://205.174.165.80/CICDataset/CIC-IDS-2017/Dataset/CIC-IDS-2017/PCAPs/Friday-WorkingHours.pcap)          | [Download MD5](http://205.174.165.80/CICDataset/CIC-IDS-2017/Dataset/CIC-IDS-2017/PCAPs/Friday-WorkingHours.md5)         |
| Monday      | `Monday-WorkingHours.pcap`          | 10 GB  | PCAP file for Monday working hours   | [Download](http://205.174.165.80/CICDataset/CIC-IDS-2017/Dataset/CIC-IDS-2017/PCAPs/Monday-WorkingHours.pcap)          | [Download MD5](http://205.174.165.80/CICDataset/CIC-IDS-2017/Dataset/CIC-IDS-2017/PCAPs/Monday-WorkingHours.md5)         |
| Thursday    | `Thursday-WorkingHours.pcap`        | 7.7 GB | PCAP file for Thursday working hours | [Download](http://205.174.165.80/CICDataset/CIC-IDS-2017/Dataset/CIC-IDS-2017/PCAPs/Thursday-WorkingHours.pcap)        | [Download MD5](http://205.174.165.80/CICDataset/CIC-IDS-2017/Dataset/CIC-IDS-2017/PCAPs/Thursday-WorkingHours.md5)       |
| Tuesday     | `Tuesday-WorkingHours.pcap`         | 10 GB  | PCAP file for Tuesday working hours  | [Download](http://205.174.165.80/CICDataset/CIC-IDS-2017/Dataset/CIC-IDS-2017/PCAPs/Tuesday-WorkingHours.pcap)         | [Download MD5](http://205.174.165.80/CICDataset/CIC-IDS-2017/Dataset/CIC-IDS-2017/PCAPs/Tuesday-WorkingHours.md5)        |
| Wednesday   | `Wednesday-workingHours.pcap`       | 12 GB  | PCAP file for Wednesday working hours| [Download](http://205.174.165.80/CICDataset/CIC-IDS-2017/Dataset/CIC-IDS-2017/PCAPs/Wednesday-workingHours.pcap)       | [Download MD5](http://205.174.165.80/CICDataset/CIC-IDS-2017/Dataset/CIC-IDS-2017/PCAPs/Wednesday-workingHours.md5)      |

---

## 🔧 Usage Instructions

### 1. Verify File Integrity
Use the provided `.md5` checksum files to ensure the integrity of the downloaded files:
```bash
md5sum -c GeneratedLabelledFlows.md5
md5sum -c MachineLearningCSV.md5
md5sum -c Friday-WorkingHours.md5
md5sum -c Monday-WorkingHours.md5
md5sum -c Thursday-WorkingHours.md5
md5sum -c Tuesday-WorkingHours.md5
md5sum -c Wednesday-workingHours.md5
```

### 2. Extract Files
	•	For CSV datasets:

```
unzip GeneratedLabelledFlows.zip
unzip MachineLearningCSV.zip
```


	•	PCAP files do not require extraction.


### 3. Analyze Data
	•	Use tools like Wireshark, Zeek, or pandas for analysis.
	•	CSV datasets can be directly used for:
	•	Phishing Analysis
	•	Machine Learning Model Training
	•	PCAP files can be utilized for:
	•	Intrusion Detection System (IDS) testing
	•	Network Traffic Analysis
	•	Phishing and Anomaly Detection

## 📖 About the Dataset Source

These datasets are derived from the CICDataset/CIC-IDS-2017, provided by the Canadian Institute for Cybersecurity (CIC). The CICIDS2017 dataset is a widely used resource for research in intrusion detection, DDoS traffic analysis, and phishing detection.

For more information, visit the official dataset page:
https://www.unb.ca/cic/datasets/ids-2017.html

## 🤝 Contribution

Contributions are welcome!
If you have additional datasets or improvements, feel free to submit a pull request or open an issue.

## 📜 License

This repository is distributed under the MIT License. See the LICENSE file for details.

## 🛡️ Disclaimer

This repository is intended for research and educational purposes only. Misuse of the datasets for malicious intent is strictly prohibited.

## 📧 Contact

For questions or collaboration inquiries, please reach out to Rokibul Islam Roni.

Start analyzing phishing threats and network traffic today! 🚀

This unified file integrates details about both the CSV datasets and PCAP files, providing clear instructions and download links for both. Let me know if further adjustments are needed!
