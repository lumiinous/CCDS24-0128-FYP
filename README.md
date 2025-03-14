# **CCDS24-0128-FYP**

## **Description**  
This project explores the implementation of **Multi-Key Fully Homomorphic Encryption (MK-FHE)** in **Machine Learning (ML) models** to enable privacy-preserving computation on encrypted data. The implementation leverages the **OpenFHE** library to perform encrypted operations efficiently.

## **Requirements**  
This project requires the **OpenFHE** library to run. Ensure you have the following dependencies installed before proceeding.

### **1. Install OpenFHE**  
Follow the official OpenFHE installation guide:  
🔗 [OpenFHE Installation Guide](https://github.com/openfheorg/openfhe-development)

Alternatively, you can install OpenFHE using CMake and Git:
```bash
git clone --recursive https://github.com/openfheorg/openfhe-development.git
cd openfhe-development
mkdir build && cd build
cmake ..
make -j$(nproc)
sudo make install
