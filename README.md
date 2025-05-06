[`1K1 Rice Genome Project – Philippines (Overview)`](https://github.com/1K1RG) 

# 🗂️ Project Resource Hub

Welcome to the **Project Resource Hub**! This repository serves as the central location for storing and sharing **small-sized files** used throughout the project. Whether it's configuration files, assets, scripts, or other lightweight resources, this repository ensures that project contributors have a **structured and easy-to-access** location for all resources. Files stored here are intended for **frequent access and sharing** across various parts of the project, ensuring that all team members are aligned and have access to the necessary resources at any given time.

## 🛠️ Key Features:
- **📍 Centralized Storage**: A single location for all small files needed across the project.
- **🔗 Easy Sharing**: Quick access to resources for seamless collaboration.
- **🗃️ Organized Structure**: Files are categorized and easy to navigate, ensuring that everything is where it needs to be.

## 🚨 Sample Data Files:

This list of files contains both the input and output files needed for generating HDF5 files. The input files are the raw data that will be processed to create HDF5 matrices, which are used for visualizing SNP data. The output files include the results of this processing, which will be loaded into a database for easy storage, access, and further analysis.

#### Input Files:
- [`169.vcf.gz`](https://3kricegenome.s3.dualstack.us-east-1.amazonaws.com/snpseek-dl/1k1rg/SampleData/169.vcf.gz) – A VCF or bgzipped VCF file
- [`mat_vcf.txt.gz`](https://3kricegenome.s3.dualstack.us-east-1.amazonaws.com/snpseek-dl/1k1rg/SampleData/mat_vcf.txt.gz) – A text-file matrix 
- [`SampleData_pos.txt`](https://3kricegenome.s3.dualstack.us-east-1.amazonaws.com/snpseek-dl/1k1rg/SampleData/pos.txt) – List of SNP positions (CHR, POS, REF, ALT) 
- [`SampleData_list.txt`](https://3kricegenome.s3.dualstack.us-east-1.amazonaws.com/snpseek-dl/1k1rg/SampleData/sample_list.txt) –  list of sample IDs in the same order as in HDF5 file

#### Output Files:
- [`169_transp.h5`](https://3kricegenome.s3.dualstack.us-east-1.amazonaws.com/snpseek-dl/1k1rg/SampleData/169_transp.h5) – HDF5 file generated from the input data  

By using this repository, we ensure consistency and efficiency throughout the project’s lifecycle. 🌱


