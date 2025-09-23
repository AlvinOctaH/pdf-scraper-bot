# PDF-scraper-bot

----------------
## Table of contents

- [1. Introduction](#1-Introduction)
- [2. Build Process](#2-Build-Process)
- [3. Results](#3-Results)

----------

## 1. Introduction
This repository will discuss the build process and results of a Robotic Process Automation (RPA) Bot that automatically extracts and filters important data from PDF files using scraping techniques.

<p align="center">
  <img src="https://github.com/AlvinOctaH/PDF-scraper-bot/blob/main/Images/1.jpeg?raw=true" 
       alt="Build Process Robotic Process Automation (RPA)" 
       width="400"
      height="600"/>
</p>

## 2. Build Process
This Robotic Process Automation (RPA) was created using [Uipath](https://www.uipath.com/) and uses [Adobe Acrobat](https://get.adobe.com/reader/) to open PDF documents. Using scraping techniques, the Robotic Process Automation (RPA) will retrieve data and enter it into a predefined Excel (ScrapedInvoiceOutput.xlsx). The data to be retrieved from the PDF are **Invoice Number**, **Invoice Date**, **Customer Name**, **Total Amount**, and **Customer ID**. The creation of the RPA can be seen in the following image:
![Build Process Robotic Process Automation (RPA)](https://github.com/AlvinOctaH/PDF-scraper-bot/blob/main/Images/Scrape.png?raw=true)

## 3. Results
The results of the data scraping that has been done, can be seen in the following figure:
![Results of the data scraping](https://github.com/AlvinOctaH/PDF-scraper-bot/blob/main/Images/Excel.png?raw=true)
