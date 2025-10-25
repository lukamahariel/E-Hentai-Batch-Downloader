# E-Hentai Batch Downloader
A userscript for downloading galleries from E-Hentai or ExHentai in batch mode.

## Description
This script allows you to download multiple galleries from search results or individual gallery pages on E-Hentai/ExHentai. It fetches metadata via the API, scrapes image URLs if needed, downloads images sequentially, and packages them into a ZIP file.

## How It Works

Navigate to a search results page on E-Hentai or ExHentai.
Perform a search query to list galleries.
Click the "Download All Galleries in This Page" button added by the script.
The script will sequentially fetch metadata, download images for each gallery, and save them as ZIP files.

## Features:

Batch downloading from search pages.
Caching of gallery metadata.
Progress bars for batch and individual gallery downloads.
Pause, resume, skip, and cancel options.
Handles API rate limits with retries.
ZIP creation using fflate library.

## Installation

Install a userscript manager:

Violentmonkey (recommended)
Tampermonkey


## Download and install the script:

[Download the script](https://sleazyfork.org/en/scripts/553635-e-hentai-batch-downloader)


Use with the latest versions of modern browsers like Chrome, Firefox.
