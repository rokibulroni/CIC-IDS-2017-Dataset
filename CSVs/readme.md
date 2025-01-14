# Phishing Email Forensic Framework - Open Datasets Repository

This repository hosts open-source datasets and resources essential for analyzing phishing email patterns and developing a forensic framework. These datasets are derived from the **CICDataset/CIC-IDS-2017**, a freely available DDoS traffic dataset from the **Canadian Institute for Cybersecurity**. These resources are ideal for building and testing models for phishing detection and threat intelligence.

**Source**: [CICIDS2017 Dataset - Canadian Institute for Cybersecurity](https://www.unb.ca/cic/datasets/ids-2017.html)

---

## 📂 Repository Contents

### 1. **GeneratedLabelledFlows**
- **File**: [`GeneratedLabelledFlows.zip`](http://205.174.165.80/CICDataset/CIC-IDS-2017/Dataset/CIC-IDS-2017/CSVs/GeneratedLabelledFlows.zip)  
  - **Description**: A compressed archive containing pre-processed and labeled flow data for phishing detection.
  - **Size**: 271 MB
  - **MD5 Checksum**: [`GeneratedLabelledFlows.md5`](http://205.174.165.80/CICDataset/CIC-IDS-2017/Dataset/CIC-IDS-2017/CSVs/GeneratedLabelledFlows.md5)

### 2. **MachineLearningCSV**
- **File**: [`MachineLearningCSV.zip`](http://205.174.165.80/CICDataset/CIC-IDS-2017/Dataset/CIC-IDS-2017/CSVs/MachineLearningCSV.zip)  
  - **Description**: A zip file containing CSV datasets formatted for machine learning algorithms, designed to identify phishing patterns and anomalies.
  - **Size**: 224 MB
  - **MD5 Checksum**: [`MachineLearningCSV.md5`](http://205.174.165.80/CICDataset/CIC-IDS-2017/Dataset/CIC-IDS-2017/CSVs/MachineLearningCSV.md5)

---

## 🔧 Usage Instructions

1. **Verify File Integrity**  
   - Use the provided `.md5` checksum files to ensure the integrity of the downloaded files.
   - Run the following command in your terminal:
     ```bash
     md5sum -c GeneratedLabelledFlows.md5
     md5sum -c MachineLearningCSV.md5
     ```

2. **Extract Files**  
   - Extract the zip files using any decompression tool or via the command line:
     ```bash
     unzip GeneratedLabelledFlows.zip
     unzip MachineLearningCSV.zip
     ```

3. **Dataset Application**  
   - These datasets can be utilized for:
     - **Email Header Analysis**
     - **Content-Based Phishing Detection**
     - **Machine Learning Model Training and Validation**
     - **Phishing Pattern Recognition and Threat Intelligence**

---

## 📊 Dataset Details

| Dataset                | Size   | Description                                      | Download Link                                                       | MD5 Checksum Download                                                |
|------------------------|--------|--------------------------------------------------|---------------------------------------------------------------------|----------------------------------------------------------------------|
| GeneratedLabelledFlows | 271 MB | Labeled flow data for phishing analysis          | [`Download`](http://205.174.165.80/CICDataset/CIC-IDS-2017/Dataset/CIC-IDS-2017/CSVs/GeneratedLabelledFlows.zip)                | [`MD5`](http://205.174.165.80/CICDataset/CIC-IDS-2017/Dataset/CIC-IDS-2017/CSVs/GeneratedLabelledFlows.md5)                  |
| MachineLearningCSV     | 224 MB | Machine learning-ready phishing detection data   | [`Download`](http://205.174.165.80/CICDataset/CIC-IDS-2017/Dataset/CIC-IDS-2017/CSVs/MachineLearningCSV.zip)                    | [`MD5`](http://205.174.165.80/CICDataset/CIC-IDS-2017/Dataset/CIC-IDS-2017/CSVs/MachineLearningCSV.md5)                      |

---

## 📖 About the Dataset Source

These datasets are derived from the **CICDataset/CIC-IDS-2017**, provided by the **Canadian Institute for Cybersecurity (CIC)**. The CICIDS2017 dataset is a widely used resource for research in intrusion detection, DDoS traffic analysis, and phishing detection.

For more information, visit the official dataset page:  
[https://www.unb.ca/cic/datasets/ids-2017.html](https://www.unb.ca/cic/datasets/ids-2017.html)

---

## 🤝 Contribution

Contributions are welcome!  
If you have additional datasets or improvements, feel free to submit a pull request or open an issue.

---

## 📜 License

This repository is distributed under the **MIT License**. See the `LICENSE` file for details.

---

## 🛡️ Disclaimer

This repository is intended for research and educational purposes only. Misuse of the datasets for malicious intent is strictly prohibited.

---

## 📧 Contact

For questions or collaboration inquiries, please reach out to [Rokibul Islam Roni](mailto:mail@rokibulroni.com).

---

**Start analyzing phishing threats today! 🚀**
