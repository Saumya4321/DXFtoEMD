# DXFtoEMD
DXFtoEMD is a Python-based tool designed to convert DXF files into EMD format, which is accepted by Feeltek laser scancard.
It makes use of Lenmark3DS software by Feeltek to facilitate the conversion. Make sure Lenmark3DS software is installed on the system before running this converter.


## Installation and Usage
#### Clone the repository
```
git clone https://github.com/Saumya4321/DXFtoEMD.git
cd DXFtoEMD

```
#### Install Dependencies
```
pip install -r requirements.txt
```
#### Run the program
```
python dxf_to_emd/conversion_tool.py
```
This script takes an input folder containing DXF files and converts them to .emd format.

## Project Structure
```
DXFtoEMD/
├── dxf_to_emd/
│   ├── conversion_tool.py          # Main script for conversion
│   ├── input                       # example input files
│   └── output                      # example output folder
├── test_model              # bunch of test files for conversion 
├── requirements.txt        # List of dependencies
|── file_naming.py          # Utility for consistent file naming
└── README.md               # Project documentation

```
