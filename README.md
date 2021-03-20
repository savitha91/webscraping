# Webscraping
To check if a website allows web scraping,check if robots.txt is available. Append /robots.txt at the end of the url (amazon.in/robots.txt)

## Steps to be followed
1. Find the URL that you want to scrape
2. Inspecting the Page
3. Find the data you want to extract
4. Write the code
5. Run the code and extract data-> sends request to the url. As a response to the url, server sends data and allows to read HTML/XML page.
The code parses the page, find the data and extracts it
6. Store the data in the required format 

## Python libraries for web scraping
1. Selenium : Automate browser activities
2. BeautifulSoup : Parse HTML and XML content
   beautifulsoup4 is the name of the package.
   bs4 is the name of the module.
   BeautifulSoup is the name of a function that is a member of the module
3. Pandas 

## Setting up chrome driver for Selenium - MacOS
1. Download chrome driver for mac - https://www.edureka.co/community/52315/how-to-setup-chrome-driver-with-selenium-on-macos
2. Check if /usr/local/bin path is available. If not, create the path. Place the downloaded chrome driver at this location








# Reference
1. https://www.edureka.co/community/52315/how-to-setup-chrome-driver-with-selenium-on-macos
