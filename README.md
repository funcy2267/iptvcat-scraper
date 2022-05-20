# About
This is modified version of [eliashussary/iptvcat-scraper](https://github.com/eliashussary/iptvcat-scraper) with search support.

# Configuration
Install required Go modules and build the scraper:
```
go install && go build
```

# Usage
```
./iptvcat-scraper channel_name
```
Scraped data from IPTV-Cat will be saved to `all-streams.json` and `all-by-country.json`.
