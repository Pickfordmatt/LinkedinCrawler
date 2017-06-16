# Prowl

## Install Instructions

* git clone https://github.com/pickfordmatt/prowl
* pip install -r requirements.txt

## Requirements
* BeautifulSoup
* GitPython

## Example usage
### Basic search
python prowl.py -c "Yahoo" -e "&lt;fn&gt;&lt;ln&gt;@yahoo.com"

### Exclude jobs
python prowl.py -c "Yahoo" -e "&lt;fn&gt;&lt;ln&gt;@yahoo.com" -nj

### Change search depth
python prowl.py -c "Yahoo" -e "&lt;fn&gt;&lt;ln&gt;@yahoo.com" -d "10" (smaller is less, larger is more pages to search)

