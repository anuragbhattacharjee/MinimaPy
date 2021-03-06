PythonScripts
=============

1. ```greads.py``` - Scraped all the pages of the user's liked list by using HTML scraper and added them to a file.

2. ```greads_rss.py``` - Scraped the rss feed of the user's liked quotes and then randomly displayed anyone quote from all the quotes.

3. ```img_download.py``` - Downloads an image from a given link.

4. ```combine_csv_0.py``` - Combines a list of csv files into a single csv. Header needs to be same. Requires ```pandas``` module.

5. ```combine_csv_1.py``` - Combines a list of csv files into a single csv. Header needs to be same. Handles UnicodeDecodeErrors, to some extent. Requires ```pandas``` module.

6. ```csv_to_SQL.py``` - Reads a CSV and uploads it to a SQL Database. Requires ```pandas``` and ```sqlalchemy``` modules.


7. ```edd.py``` - Generates an EDD of a file. Requires ```pandas``` module.

8. ```csv_2_excel_adj_widths.py``` - Converts CSV into Excel with the column with adjusted to the max length in the column.

9. ```word_freq.py``` - Word frequency.

10. ```move_cursor.py ``` - Moves the cursor to the lower right corner and keeps clicking there after every 5 seconds. Prevents the screen from sleeping.

11. ```address_similarity.py``` - Gives a similarity between 2 addresses.

12. ```split_csv.py``` - Splits a CSV into multiple CSVs.

13. ```sql_2_formatted_excel.py``` - Extracts table from MS SQL DB and saves it into CSV and Column adjusted Excel.

14. ```state_from_address.py``` - Extracts State and City from an address column.

15. ```pdf_2_csv_0.py``` - Extracts simple table from a PDF document. Requires the installation of ```Java``` based ```Tabula``` and ```tabula``` python module.

16. ```pdf_2_csv_1.py``` - Extracts tables from a PDF document, page by page. Requires the installation of ```Java``` based ```Tabula``` and ```tabula``` python module.

17. ```pdf_2_csv_1.py``` - Extracts tables from a PDF document. First tries to convert it as a whole, if it fails, converts it page by page. Requires the installation of ```Java``` based ```Tabula``` and ```tabula``` python module.

18. ```sql_select_into.py``` - Creates new tables in SQL DB using SELECT INTO using Python.

19. ```prime_gen.py``` - An iterator that generates primes.

20. ```lat_log_2_addr.py``` - Gets address from lat-long using Google Maps API. This is an old code so I am not sure if it'll work now.

21. ```sentence_boundary.py``` - Determines sentence boundaries.

22. ```correct_encoding.py``` - Converts a mixed encoding CSV file into a utf-8 compliant CSV.

23. ```wiki.py``` - Fetches the page contents in plain text. Depends on ```wikipedia``` module. (```pip install wikipedia```)

24. ```gtransliterate.py``` - Gets a transliteration of a word from hindi to english (and vice-versa).

25. ```gen_wordcloud.py``` - Generates a wordcloud from a given text and writes it to a PNG file. Depends on - ```wordcloud``` and ```matplotlib```.

26. ```parallelism_process.py``` - Python parallel processing code using multiple processes.

27. ```parallelism_thread.py``` - Python parallel processing code using multiple threads.

28. ```parallelism_pool.py``` - Python parallel processing code using multiple processes but with simpler syntax.



