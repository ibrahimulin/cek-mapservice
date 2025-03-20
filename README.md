## Introduction
Cek Mapservice is a simple python script to check availability of all mapservice within Arcgis Server Rest Services.
It works with opening available hyperlinks within Arcgis Server Rest Service page and checks its maximum response time of 10 seconds or checks whether it has "error" or failed to response.

All process are done within Jupyter Notebook.

## Installation
The code requires several dependencies for running.
```bash
!pip install "requests" "beautifulsoup4" "openpyxl"
```

## How to use
Load Jupyter Notebook to your local machine with [All time out](https://github.com/ibrahimulin/cek-mapservice/blob/main/Cek%20service%20All%20time%20out.ipynb) if you want to check based on max 10 seconds respons time, or load [All error fetch](https://github.com/ibrahimulin/cek-mapservice/blob/main/Cek%20service%20All%20error%20fetch.ipynb) if you want to check based on Error response.

Replace start_url part with any url you want to check.
```bash
start_url = "https://gis.bnpb.go.id/server/rest/services"
```

Replace save location file in your computer.
```bash
file_name = f"D:\\Downloads\\link_check_timeout_{date_string}_{time_string}.xlsx"
```
