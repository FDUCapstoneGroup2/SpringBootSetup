# Capstone_AutomaticED

**1. Project Title:**  
Performance Optimization and Enhanced Encryption in Automatic Data Encryption Systems for Large-Scale Databases  

**2. Project Description:**  
This project aims to improve the performance of encryption algorithms used in the automatic encryption and decryption system proposed in the original paper. The focus will be on reproducing the original system and optimizing the algorithm efficiency for large-scale data handling by replacing the DES algorithm with AES.

**Original Paper Overview:** The original paper presents a system that automatically encrypts and decrypts sensitive data in databases using JPA’s Attribute Converter and the DES encryption algorithm. The system is efficient for small to medium datasets but may struggle with performance at larger scales due to the limitations of DES. 

**Problem Statement:** DES, while functional, is outdated and inefficient for large-scale applications. Its 56-bit key is vulnerable to brute-force attacks, and the performance bottlenecks in handling larger datasets are significant.

**Proposed Improvement:** We propose replacing the DES encryption algorithm with AES, which offers a higher level of security and better performance for large-scale data handling. We will compare the encryption and decryption speeds of AES and DES, particularly when handling large datasets.

**Impact of Improvement:** The improvement will significantly enhance the system’s scalability and security. AES, with its larger key sizes and faster encryption speed, will enable the system to handle large datasets more efficiently, making it more applicable for real-world enterprise scenarios.

**3. Original Paper Reference:**  
Zhang, X., Hu, H., & Xu, Y. (2024). The Design and Implementation of an Automatic Encryption and Decryption System for Sensitive Words in Databases Based on Spring Boot. 2024 5th International Seminar on Artificial Intelligence, Networking, and Information Technology (AINIT), IEEE. DOI: 10.1109/AINIT61980.2024.10581490.

**4. Project Scope:**    
**Algorithm Optimization:** Replace the DES encryption algorithm with AES and optimize the system for handling large datasets.

**Performance Enhancement:** Measure and compare encryption/decryption speeds of DES vs. AES to quantify performance gains.

**New Data or Experimentation:** Test the system using large-scale datasets to ensure the improvement holds in real-world scenarios.

**5. Novel Aspect:**  
The unique aspect of this project is the replacement of an outdated encryption algorithm with a more secure and efficient one. By directly comparing the performance of AES and DES, the project introduces quantifiable data to demonstrate how modern algorithms can improve existing systems.  

**6. Technology Stack:**  
**Languages:** Java    
**Framework:** Spring Boot, Spring Data JPA  
**Encryption Libraries:** Java Cryptography Extension (JCE) for AES implementation  
**Database:** MySQL    
**Tools:** JUnit for performance testing, SLF4J for logging  
