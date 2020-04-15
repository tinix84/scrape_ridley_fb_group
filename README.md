# scrape_ridley_fb_group
this are script collection to backup info in from ridley group

how to install
1. install anaconda or miniconda in your pc
2. install git client like Git Tortoise, github, etc...
2. open the miniconda shell and setup a new environment from environment.yml
3. git clone https://github.com/brutalsavage/facebook-post-scraper.git
4. go to folder run pip install -e .
5. run python scraper.py -p https://www.facebook.com/groups/ridleyengineering/ -l 100 -infinite 1 -comments y
6. the results are in postBigDict.json, bs.html, and data.csv
