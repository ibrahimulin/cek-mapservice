## Introduction
Cek Mapservice is a simple python script to check availability of all mapservice within Arcgis Server Rest Services.
It works with opening available hyperlinks within Arcgis Server Rest Service page and checks its maximum response time of 10 seconds.

All process are done within Jupyter Notebook

## Installation
The code requires several dependencies for running
```bash
!pip install "requests" "beautifulsoup4" "openpyxl"
```

## How to use
Load Jupyter Notebook file to your local machine

Replace start_url part with any url you want to check
```bash
start_url = "https://gis.bnpb.go.id/server/rest/services"
```

Replace save location file in your computer
```bash
 wb.save("D:\Download\link_check_results_allrev1.xlsx")
```
