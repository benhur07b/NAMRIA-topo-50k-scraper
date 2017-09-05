## NAMRIA Topo Map (1:50,000) Scraper

### About
This Notebook is used for scraping/downloading the 1:50,000 topographic maps available at the NAMRIA [website]("http://www.namria.gov.ph/download.php") and serves as a basic exercise in scraping using Beautiful Soup and Python 3.

### RUNNING THE TOOL

_**REQUIREMENTS**_
* Python 3.6.1
* jupyter
* Beautiful Soup

They are also found in the **requirements.txt** file.

You can install these requirements using **pip** (sudo **pip install -r requirements.txt** or **pip install -r requirements.txt**)

_**PROCEDURE**_
1. Add the proxy in PROXY (if any).
2. Select the directory to save the scraped files to (SAVEDIR).
3. Add a QUERY list to limit the download (i.e. ["3343"]; only files containing strings matching any of the elements in QUERY will be downloaded).
4. Run All.

### LICENSE
_Copyright (C) 2017 Ben Hur S. Pintor (bhs.pintor@gmail.com)_ [[website]("https://benhur07b.github.io")]

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.
You should have received a copy of the GNU General Public License along with this program. If not, see http://www.gnu.org/licenses/.