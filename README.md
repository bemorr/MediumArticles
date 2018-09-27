# `Scraping_SWIFT_codes_Bank_names.py'.

I have refactored the code using selenium and webdriver instead of using `import requests` as with this lib my https request were failing and not pulling the full html doc. 

Also added some error handling in (ln 25) which caught the initial problem. H/T @bruno desthuilliers via Stackoverflow: https://stackoverflow.com/questions/52533473/attributeerror-nonetype-object-has-no-attribute-tbody-spyder-3-3-1-beau.

Original medium article here: https://towardsdatascience.com/a-short-practical-how-to-guide-to-scrape-data-from-a-website-using-python-888373227d4f
