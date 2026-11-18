# archive-search-engine
archive-search-engine  .exe file  - search archive org - makes instant html files for search query


# archive-search.exe

A standalone, zero-dependency Windows executable for searching the Internet Archive and generating permanent, self-contained HTML catalogues of direct download and streaming links.

## Features

- **Zero Dependencies:** Single compiled Windows binary (`archive-search.exe`) — no Python, Node.js, or external libraries required.
- **Flexible Search Modes:**
  - **Title Search (Default):** Searches item titles directly (`title:(...)`) for accurate, high-signal results.
  - **All-Metadata Search:** Sweeps descriptions, subjects, and full-text metadata when you need a wider net.
  - **Direct Query Operators:** Supports raw Internet Archive query syntax (e.g. `creator:mulciber687`, `subject:"pirate radio"`).
- **Skips Restricted Collections:** Automatically filters out locked broadcast and borrow-only collections (`radio`, `tvarchive`, `inlibrary`) to keep scans fast.
- **Clean File Filtering:** Extracts direct links for `.wav`, `.mp3`, `.mp4`, `.pdf`, `.txt`, `.html`, `.htm`, `.zip`, `.json`, `.csv`, and `.epub` while ignoring auto-generated thumbnails and metadata clutter.
- **Permanent HTML Output:** Saves a clean, dark-mode `<keyword>.html` file of clickable direct links (`https://archive.org...`) and opens it automatically in your default browser.
- **Continuous Loop:** Run back-to-back searches in one session or press `Enter` on an empty prompt to exit.

## Usage

1. Download `archive-search.exe` into any folder on your Windows PC.
2. Double-click `archive-search.exe`.
3. Enter a search keyword (or a field query like `creator:mulciber687`).
4. Choose **Title only** (press `Enter`) or **All metadata** (`2`).
5. Set the maximum number of archive items to scan (default `10`).
6. Your `<keyword>.html` catalogue is generated in the same folder and opened automatically in your browser.

## Philosophy

Built for longevity and local ownership: no servers, no accounts, no tracking, and no fragile dependency chains. Every generated `.html` catalogue is plain static HTML that will continue working in any browser for decades.

## Author

Built by **Mojo** (`Mulc1b3R`)   MADE IN YORKSHIRE
