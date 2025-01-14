# CIC-IDS-2017 PCAP Datasets - Working Hours Traffic

This repository contains network traffic PCAP files and MD5 checksums from the **CIC-IDS-2017 Dataset** by the **Canadian Institute for Cybersecurity (CIC)**. These files represent network traffic collected during working hours across various days, useful for intrusion detection, phishing analysis, and cybersecurity research.

**Source**: [CICIDS2017 Dataset - Canadian Institute for Cybersecurity](https://www.unb.ca/cic/datasets/ids-2017.html)

---

## 📂 Repository Contents

### PCAP Files and MD5 Checksums

| Day         | File Name                           | Size   | Description                          | Download Link                                                                                      | MD5 Checksum                                                                                      |
|-------------|-------------------------------------|--------|--------------------------------------|---------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------|
| Friday      | `Friday-WorkingHours.pcap`          | 8.2 GB | PCAP file for Friday working hours   | [Download](http://205.174.165.80/CICDataset/CIC-IDS-2017/Dataset/CIC-IDS-2017/PCAPs/Friday-WorkingHours.pcap)          | [Download MD5](http://205.174.165.80/CICDataset/CIC-IDS-2017/Dataset/CIC-IDS-2017/PCAPs/Friday-WorkingHours.md5)         |
| Monday      | `Monday-WorkingHours.pcap`          | 10 GB  | PCAP file for Monday working hours   | [Download](http://205.174.165.80/CICDataset/CIC-IDS-2017/Dataset/CIC-IDS-2017/PCAPs/Monday-WorkingHours.pcap)          | [Download MD5](http://205.174.165.80/CICDataset/CIC-IDS-2017/Dataset/CIC-IDS-2017/PCAPs/Monday-WorkingHours.md5)         |
| Thursday    | `Thursday-WorkingHours.pcap`        | 7.7 GB | PCAP file for Thursday working hours | [Download](http://205.174.165.80/CICDataset/CIC-IDS-2017/Dataset/CIC-IDS-2017/PCAPs/Thursday-WorkingHours.pcap)        | [Download MD5](http://205.174.165.80/CICDataset/CIC-IDS-2017/Dataset/CIC-IDS-2017/PCAPs/Thursday-WorkingHours.md5)       |
| Tuesday     | `Tuesday-WorkingHours.pcap`         | 10 GB  | PCAP file for Tuesday working hours  | [Download](http://205.174.165.80/CICDataset/CIC-IDS-2017/Dataset/CIC-IDS-2017/PCAPs/Tuesday-WorkingHours.pcap)         | [Download MD5](http://205.174.165.80/CICDataset/CIC-IDS-2017/Dataset/CIC-IDS-2017/PCAPs/Tuesday-WorkingHours.md5)        |
| Wednesday   | `Wednesday-workingHours.pcap`       | 12 GB  | PCAP file for Wednesday working hours| [Download](http://205.174.165.80/CICDataset/CIC-IDS-2017/Dataset/CIC-IDS-2017/PCAPs/Wednesday-workingHours.pcap)       | [Download MD5](http://205.174.165.80/CICDataset/CIC-IDS-2017/Dataset/CIC-IDS-2017/PCAPs/Wednesday-workingHours.md5)      |

---

## 🔧 Usage Instructions

1. **Download Files**  
   - Use the provided links to download the desired PCAP files and their corresponding MD5 checksum files.

2. **Verify File Integrity**  
   - Verify the integrity of the PCAP files using the provided MD5 checksum:
     ```bash
     md5sum -c Friday-WorkingHours.md5
     md5sum -c Monday-WorkingHours.md5
     md5sum -c Thursday-WorkingHours.md5
     md5sum -c Tuesday-WorkingHours.md5
     md5sum -c Wednesday-workingHours.md5
     ```

3. **Analyze Traffic**  
   - Load the PCAP files into tools like **Wireshark** or **Zeek** for analysis.
   - Utilize these datasets for:
     - Intrusion Detection System (IDS) testing
     - Phishing traffic analysis
     - Network anomaly detection

---

## 📖 About the Dataset Source

These PCAP files are from the **CIC-IDS-2017 Dataset**, a freely available dataset created by the **Canadian Institute for Cybersecurity (CIC)**. It is one of the most comprehensive datasets for studying intrusion detection and DDoS traffic.

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

**Start analyzing network traffic today! 🚀**
