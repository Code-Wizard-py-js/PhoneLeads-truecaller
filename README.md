# truecaller-automatic-bulk-phone-query

The Truecaller Automatic Bulk Phone Query is a Python tool that leverages the Selenium framework to automate the retrieval of bulk phone numbers from the web through the Truecaller platform. By utilizing Selenium, the tool performs actions such as automatic sign-in and the extraction of relevant phone number details using XPath to locate HTML tags.

However, it is essential to note that Truecaller imposes limitations on the number of searches allowed per day. Presently, the limit is set to 5 searches per day, rendering the tool less effective for bulk searching purposes. To overcome this limitation, multiple Truecaller accounts would be required. Previously, Truecaller permitted a higher number of searches within a specific timeframe, allowing continuous data fetching with multiple accounts.

If you are interested in understanding the tool's functionality and exploring tips and tricks, you can experiment with different XPath expressions to locate elements accurately. Pull requests are welcome for contributions to the codebase.

#To use the tool, ensure that the required packages are installed: 

- pip install webdriver_manager --user
- pip install bs4
- pip install selenium
