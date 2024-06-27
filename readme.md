install python

install pip 

pip install virtualenv

python -m venv venv (venv — Creation of virtual environments)

venv\Scripts\Activate.ps1  (Command to activate virtual environment)

pip install scrapy



scrapy startproject scraperr

cd scraperr



cd scraperr/spider

scrapy genspider spider https://services.nvd.nist.gov



scrapy crawl spider             

scrapy crawl spider -o data.csv 
