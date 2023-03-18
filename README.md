# Gre_Mnemonic_Scrapper

This simple python script is used to scrape, up to 3 mnemonics for a list of words from the website https://mnemonicdictionary.com/. The scraped mnemonics are then automatically stored in an Excel file for further use.

<H3>Libraries used in the code</H3>
- requests, BeautifulSoup, pandas

<H3>Steps involved in the code</H3>

1. Read the list of words from an Excel file.
2. Create an empty DataFrame to store the mnemonics.
3. Create a session object for making requests.
4. Loop through each word in the list.
5. Make a GET request to the website using the session object.
6. Use BeautifulSoup to parse the HTML content.
7. Find the mnemonics section and extract up to 3 mnemonics.
8. Append the word and mnemonics to the DataFrame.
9. Sleep for a random amount of time between 1-3 seconds to avoid getting blocked by the website.
10. Save the DataFrame to an Excel file.
11. The code can be modified to suit specific requirements, such as changing the source of the list of words or changing the output file format. It is recommended to avoid scraping large amounts of data in a short period of time to prevent getting blocked by the website.

<H3>To use the code</H3>

 1. Install the required libraries - requests, BeautifulSoup, pandas.
 2. Save the list of words to be scraped in an Excel file.
 3. Update the input file path and output file path in the code.
 4. Run the code.

<H3> Word of Caution</H3>

Web scraping without the user's permission is not recommended and can lead to legal issues. This code should be used for educational purposes only and should not be used for any illegal activities. Before attempting any web scraping, ensure you have obtained proper consent from website owners.
