# :balloon: Upper air analysis  :partly_sunny:
You can easily use user interface to process many types of data such as csv,excel,txt or icao upper air code
to make many types of Skew-T Log-P Diagrams templates and send output to line notification ([use line token](https://notify-bot.line.me/th/)) and get weather forecast by using TMD (Thai meteological department) [api](https://data.tmd.go.th/dataset/index.php) or
Air quality index (AQI) and PM2.5 air pollution in Thailand from cnaqi api ([use token key](https://aqicn.org/city/beijing/))

![show_ui](https://raw.githubusercontent.com/TOPaz09/Upper-air-analysis/main/figure/my_ui.png)

### How to install?
- Download and extract zip files on your PC. ([google drive](https://drive.google.com/uc?export=download&id=1QMZ2d1FAGA790xp4CONXFCQ--Dljx1lH) or [github repository](https://github.com/TOPaz09/Upper-air-analysis/archive/refs/heads/main.zip))
- Extract file (you need to setting [exclusion folder](https://support.microsoft.com/en-us/windows/add-an-exclusion-to-windows-security-811816c0-4dfd-af4a-47e4-c301afe13b26) from window security because of this program can scan data from you folder to create many outputs)

### How to use?
![method](https://raw.githubusercontent.com/TOPaz09/Upper-air-analysis/main/figure/process.png)

 1. Select input type 
    - [Wind profiler](https://github.com/TOPaz09/Upper-air-analysis/blob/main/Example%20data/20230331_2350_raob.csv)
    - [Rawindsonde text](https://github.com/TOPaz09/Upper-air-analysis/blob/main/Example%20data/CM2024010723_SIGLVLS.txt)
    - [Rawindsonde code](https://github.com/TOPaz09/Upper-air-analysis/blob/main/Example%20data/16112566.txt)

 2. Select process type (single file/all folder)
 3. Locate input file/folder directory
 4. Locate output folder
 5. Select product/option (Unselectable in some options, see detail below)
    - [Upper air analysis (200 mb)](https://raw.githubusercontent.com/TOPaz09/Upper-air-analysis/main/figure/20230331_2355_raob_200mb.png)
    - [Upper air analysis (Full scale)](https://raw.githubusercontent.com/TOPaz09/Upper-air-analysis/main/figure/16112566_full.png)
    - [Skew-t and Inversion](https://raw.githubusercontent.com/TOPaz09/Upper-air-analysis/main/figure/17112566_lr.png)
    - [Skew-t,PM2.5,weather forecast (API)](https://raw.githubusercontent.com/TOPaz09/Upper-air-analysis/main/figure/20230331_2330_raob_inver2.png)
    - [Make CSV](https://github.com/TOPaz09/Upper-air-analysis/blob/main/figure/16112566_full_filter.csv)
    - [Make Excel](https://github.com/TOPaz09/Upper-air-analysis/raw/main/figure/16112566_full_filter.xlsx)
    
    5.1 You can change diagram title and pm2.5 aqi token (optional)  
        ![](https://raw.githubusercontent.com/TOPaz09/Upper-air-analysis/main/figure/file_setting_tab.png)

    5.2 You can change line token and send message and output to line notification (optional)
        ![](https://raw.githubusercontent.com/TOPaz09/Upper-air-analysis/main/figure/line_msg.png)

 6. Save configuration
 7. Press start button to begin process

### Thai User Manual :blue_book:
[คู่มือการใช้งานโปรแกรม upper air analysis.pdf](https://drive.google.com/uc?export=download&id=13BVkQnCQYubDkyte1tc4WWBd98Fq3IVk)


### Exempted options

| Option | WPFL (single file) | RWS (single file) | RWS code (single file) | WPFL (folder) | RWS (folder) | RWS Code (folder) |
| :---- | :----: | :----: | :----: | :----: | :----: | :----: |
| 200 mb | :white_check_mark: | :white_check_mark: |:white_check_mark: |:white_check_mark: |:white_check_mark: |:white_check_mark: |
| full scale | :x: | :white_check_mark:| :white_check_mark: |:white_check_mark: |:white_check_mark: |:white_check_mark: |
| inversion | :white_check_mark: | :white_check_mark: | :white_check_mark: |:white_check_mark: |:white_check_mark: |:white_check_mark: |
| PM2.5 | :white_check_mark: | :white_check_mark: | :white_check_mark: |:x: |:x: |:x: |
| CSV | :white_check_mark: | :white_check_mark: | :white_check_mark: |:white_check_mark: |:white_check_mark: |:white_check_mark: |
| Excel | :white_check_mark: | :white_check_mark: | :white_check_mark: |:white_check_mark: |:white_check_mark: |:white_check_mark: |
| line | :white_check_mark: | :white_check_mark: | :white_check_mark: |:x: |:x: |:x: |


## Develop by Supaporn Noisen :computer:
