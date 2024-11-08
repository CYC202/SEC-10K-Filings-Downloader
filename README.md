# SEC-Downloader

## Project Name
SEC Filings Downloader

## Description
A tool to retrieve filings from the SEC based on a specified identifier (tikcer, cik), form (10k, 20f, etc.), year, amendment, etc. 

I also provide basic functionality for word frequency analysis from a given dictionary, including options for removing stop words and stemming. 

The implementation has been optimized with multithreading to enhance retrieval speed. 

It can skip existing files.

**The code is encrypted for personal use; please reach out for collaboration or academic inquiries.**

## SEC 10-K Filings Downloader
### Overview
This project allows users to download 10-K filings from the SEC by providing a ticker symbol and an optional year. It effectively manages the complexities of the SEC’s package for retrieving filings and speeds up the process through multithreading. Additionally, it includes functionality for word frequency analysis within the downloaded filings.

### Features
1. **Retrieve 10-K Filings**: Access and download 10-K filings based on a specified ticker and year.
2. **Word Frequency Analysis**: Analyze the frequency of terms from a provided dictionary within the filings.
3. **Stop Words Removal**: Filter out common stop words to focus on significant terms.
4. **Stemming**: Reduce words to their root form for accurate frequency counts.
5. **Multithreading**: Optimize retrieval speed using concurrent processing.

### Note
The code is intended for personal use only and has been encrypted. If you have academic needs or wish to discuss further, feel free to reach out for collaboration and exchange of ideas.

**Last Updated:** November 2, 2024
