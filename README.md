# Network-Analysis-Project

### <a name="_cdp27mhs9hcv"></a>**Project Summary**
#### <a name="_6a1gv1sidshi"></a>**Title: Network Traffic Analysis and Visualization**
**Objective:** Analyzed network traffic data to understand communication patterns between source and destination IP addresses. The project includes data cleaning, exploratory data analysis (EDA), and visualizations to identify key insights and patterns.

-----
### <a name="_alg1519mjw7q"></a>**1. Data Overview**
**Dataset Description:**

- **Source:** Network traffic dataset
- **Size:** 117,084 records
- **Key Features:**
  - No.: Packet number
  - Time: Timestamp of the packet
  - Source: Source IP address
  - Destination: Destination IP address
  - Protocol: Network protocol (e.g., UDP)
  - Length: Length of the packet
  - Info: Additional information about the packet
-----
### <a name="_7gex2clt9oq9"></a>**2. Data Cleaning and Preparation**
- **Null Values:** Removed null values to ensure completeness.
- **Date Formatting:** Standardized date formats for consistency.
-----
### <a name="_1suyfnuz9hr0"></a>**3. Exploratory Data Analysis (EDA)**
### <a name="_hpltxa48bw4q"></a>**1. Protocol Distribution**
- **Visualization Type**: Bar Chart
- **Description**: This chart displays the frequency of various network protocols in your dataset. It provides insights into which protocols are most commonly used, highlighting the distribution of protocol types such as UDP, TCP, etc.
### <a name="_ainrjwxyji0s"></a>**2. Top Source IP Addresses**
- **Visualization Type**: Bar Chart
- **Description**: This chart shows the most active source IP addresses. It identifies which source IPs are sending the most traffic, helping to understand the network's activity patterns and potential sources of high traffic.
### <a name="_f63m08tstwk9"></a>**3. Top Destination IP Addresses**
- **Visualization Type**: Bar Chart
- **Description**: This chart illustrates the most targeted destination IP addresses. It reveals which destination IPs are receiving the most traffic, indicating potential hotspots or targets in the network.
### <a name="_evh3xskudrs4"></a>**4. Packet Length Distribution**
- **Visualization Type**: Histogram
- **Description**: This histogram displays the distribution of packet lengths. It provides insights into the range and frequency of different packet sizes, which can be useful for understanding the nature of network traffic.
### <a name="_pos5bmkqc9h1"></a>**5. Packet Counts Over Time**
- **Visualization Type**: Line Plot
- **Description**: This line plot tracks packet counts over time, showing how network traffic varies. It helps in identifying trends, spikes, or patterns in traffic across different time periods.

### <a name="_bwra3rc635wz"></a>**5. Conclusion**
### <a name="_m7yiwwk8k14u"></a>**Key Findings**
1. **Most Common Protocol**:
   1. **TCP**: The most frequently used protocol, with a total count of 51,036 occurrences.
   1. **Other Notable Protocols**:
      1. QUIC: 41,762 occurrences
      1. TLSv1.3: 12,450 occurrences
      1. TLSv1.2: 3,756 occurrences
1. **Top Source IP Addresses**:
   1. **2409:40f4:100b:c1b6:b9fb:3ec3:5675**
      : 49,902 occurrences
   1. **2600:1901:1:c36::**: 10,065 occurrences
   1. **2405:200:1630:a03::312c**
      : 6,536 occurrences
   1. **64:ff9b::b97d**
      : 4,301 occurrences
   1. **192.168.239.25**: 3,219 occurrences
1. **Top Destination IP Addresses**:
   1. **2409:40f4:100b:c1b6:b9fb:3ec3:5675**
      : 60,423 occurrences
   1. **2600:1901:1:c36::**: 8,550 occurrences
   1. **2405:200:1630:a03::312c**
      : 5,184 occurrences
   1. **64:ff9b::b97d**
      : 3,106 occurrences
   1. **2a04:4e42:25::760**: 2,528 occurrences
1. **Packet Length Distribution**:
   1. **Mean Length**: 675 bytes
   1. **Standard Deviation**: 1,062 bytes
   1. **Length Range**:
      1. 25th Percentile: 86 bytes
      1. Median: 101 bytes
      1. 75th Percentile: 1,292 bytes
      1. Maximum: 17,838 bytes
1. **Traffic Trends**:
   1. **Time Range**:
      1. **Minimum Timestamp**: 1970-01-01 00:00:00
      1. **Maximum Timestamp**: 1970-01-01 01:55:41
   1. **Mean Timestamp**: 1970-01-01 00:42:37

**6. Additional Information**
- **Data Files:** [Link to data files, if applicable]
- **Contact:** [[LinkedIn](https://www.linkedin.com/in/emmanuel-adetoro/)]
