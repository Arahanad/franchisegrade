# franchisegrade

1. Navigate to the Project Directory:

cd <franchisegrade>

2. Install Dependencies:

pip install beautifulsoup
pip install requests
pip install selenium
pip install undetected_chromedriver
pip install psutil
pip install mysql.connect


3. To scrape the site:

    steps:

    1. Get the listing =>
            python get_listing.py
        output file: listing.json

    2. get the data of listing =>
            python main.py
        output file: Output_Final.json
    
    3. json data to csv file =>
            json_helper.py
        output file: franchisegrade_data.csv