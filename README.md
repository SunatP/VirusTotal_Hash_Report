# VirusTotal Hash Report Using API

## VirusTotal File Report

You can read more details about the API GET method below

![API Reference](https://developers.virustotal.com/reference/file-info)

## What is VirusTotal?

VirusTotal is an Internet security, file and URL analyzer

## Why VirusTotal?

Because it's free and I can request the result up to 500 requests/day (4 lookups/mins), which is enough for the present. Moreover, getting the data using the API is not complicated and easy to handle with the python coding language.

## Folder Structure

```
    .
    ├── Config                   # Stored the credential file
    ├── Input                    # Input files
    ├── Output                   # Output files
    ├── Virus Total API.ipynb    # Main Code
    └── README.md
```

## Requirements

- Python 3 or Jupyter Notebook with Anaconda
- Internet
- Some of OS knowledges

## How does my code work?

My code is working on Jupyter Notebook (Python based) with Threading Semaphore to count and block exceeding limits from requests and combination with a Threading Timer function to schedule that release of the Semaphore process

