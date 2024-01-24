# Hi, I'm Mariam Lobjanidze!

## About Me

I'm a journalist based in New York City specializing in covering business stories through the lens of data. I am currently pursuing an M.S in Data Journalism.

## Contact

Feel free to reach out to me at ml4998@columbia.edu

This repository includes two main Jupyter notebooks:

1. **BBC Movie Data Scraping**: The first notebook is dedicated to scraping a [BBC page](<link-to-BBC-page>) for various details including:
   - Movie names
   - Director names
   - Critic names and their nationalities
   - Release years
   
   The output of this notebook is a CSV file containing all the above information.

2. **Director Nationalities and IMDB Links Scraping**: The second notebook focuses on extracting the following data from another [web page](<link-to-second-page>):
   - Nationalities of directors
   - Links to their personal pages on IMDB

   This process results in two CSV files: one with the nationalities of 330 directors, and another with a mapped list of these nationalities.



## Documentation and Useful Links

For setting up the project environment, you will need to install certain Python packages and import modules. Below are the necessary commands and links to their documentation:

### Installation Commands

Use the following commands to install the required packages:

- **Pandas**: A powerful data manipulation and analysis library.
- [Pandas Documentation](https://pandas.pydata.org/pandas-docs/stable/)

- **Beautiful Soup**: A library that makes it easy to scrape information from web pages.
pip install beautifulsoup4
[Beautiful Soup Documentation](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)

### Module Import

- **Regex**: A module for working with regular expressions.
```python
import re

