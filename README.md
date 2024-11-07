# Python Package and Lambda Deployment Tool

This repository provides a Python tool that automates the process of preparing package dependencies and source code for AWS Lambda deployment. 

## Features
- **Requirements File Handling:** Reads a `requirements.txt` file and downloads all specified Python packages.
- **Package Zipping:** Compresses the downloaded packages into a ZIP file for easy deployment.
- **Source Code Zipping:** Takes all Python files from a specified directory and compresses them into a separate ZIP file.
- **AWS Lambda Ready:** Ensures both ZIP files are ready to be uploaded to AWS Lambda for serverless execution.

## Usage
1. Place your `requirements.txt` file in the root directory.
2. Place your Python source files in a designated folder.
3. Run the script to download the packages and create the ZIP files.
4. Upload the resulting ZIP files to AWS Lambda.

## Commands
- To install dependencies: `pip install -r requirements.txt`
- To zip packages: `python zip_packages.py`
- To zip source files: `python zip_source.py`


## Prerequisites
- Python 3.x
- `pip` package installer

## Notes
- Ensure that the AWS Lambda size limits are adhered to while zipping packages and source files.





