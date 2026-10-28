# CRX Packer

## **Usage (New)**

1. Upload chromium extension in zip format `./*.zip`.

2. Run `CRX Packer` in GitHub Action .
   
4. Download the CRX from the Artifact.


Usage [OLD]
-----

This Python script packs Google Chrome extensions (CRX files).


    -usage: crx-packer.py [-h] --dir DIR --key KEY --crx CRX
    
    -CRX Packer by jthuraisamy (2013)
    
    -optional arguments:
      -h, --help  show this help message and exit
      --dir DIR   Extension Directory
      --key KEY   Private Key (PEM file)
      --crx CRX   Output CRX

Dependencies
------------

OpenSSL

Licence
-------

Public Domain
