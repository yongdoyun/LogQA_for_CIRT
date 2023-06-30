# LogQA_for_CIRT

This repository contains a program developed using RayStation scripting programming Python for performing Log-Based Patient-Specific Quality Assurance (QA) in radiation therapy treatment planning. The program analyzes log files generated by radiation therapy delivery systems to verify the accuracy and precision of the treatment delivery process for individual patients.

Table of Contents

1. Introduction
2. Features
3. Requirements
4. Installation
5. Usage
6. Contributing
7. License

## Introduction

The Log-Based Patient-Specific Quality Assurance (QA) program is designed to assess the quality of radiation therapy treatment plans by analyzing the log files generated during the delivery of radiation to the patient. By comparing the expected treatment parameters with the recorded log data, the program helps ensure that the radiation treatment is delivered accurately and precisely according to the treatment plan.

This program has been developed using RayStation scripting programming Python, which is a powerful tool for automation and customization within the RayStation treatment planning system. It utilizes Python libraries and modules to process and analyze the log files, providing valuable insights into the treatment delivery process.

## Features

Log File Parsing: The program parses log files generated by radiation therapy delivery systems and extracts relevant treatment information.
Data Analysis: It analyzes the extracted log data to calculate various metrics, such as dose delivery accuracy, beam delivery time, and monitor unit verification.
Comparison with Treatment Plan: The program compares the log data with the treatment plan parameters to ensure that the treatment delivery matches the intended plan.
Visualization: It provides visual representations, such as graphs and charts, to aid in the interpretation and understanding of the QA results.
Reporting: The program generates comprehensive reports summarizing the QA results and highlighting any discrepancies or issues identified during the analysis.
Requirements

To run this program, you need the following:

RayStation scripting programming Python
Python 3.x
Required Python libraries (specified in the requirements.txt file)

## Installation

Clone this repository to your local machine or download the source code as a ZIP file.
Install RayStation scripting programming Python if you haven't already.
Install the required Python libraries by running the following command:
Copy code
pip install -r requirements.txt

- RayStation 11B was tested.
- external lib (pydicom, pymedphys, numpy, scipy)

## Usage

Open the RayStation scripting programming Python environment.
Load the program file (log_based_qa.py) into the scripting environment.
Modify the program parameters and settings as needed for your specific QA requirements.
Run the program by executing the main script.
Detailed instructions on program usage, including parameter customization and interpreting the results, can be found in the documentation provided within the repository.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please submit a pull request or open an issue on the repository.

## License

This program is licensed under the MIT License. Feel free to modify, distribute, and use it in your projects.
