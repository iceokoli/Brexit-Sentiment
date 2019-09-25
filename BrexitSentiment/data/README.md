# Data

## Sources

Source        |   Type   | How?
:-------------|:--------:|:----------------------------------------------------
Guardian      |   News   | https://open-platform.theguardian.com/documentation/
CNN           |   News   | Web Scraping
Alpha Vantage | Fx Rates | Free API (alpha_vantage python module)

## Format

### News Data

```json
{
    "publish_date": "2017-07-10T00:00:00",
    "title": "UK university proposes post-Brexit campus in Germany",
    "author": ["Judith Vonberg"],
    "url": "https://www.cnn.com/2017/07/10/europe/uk-university-campus-germany/index.html",
    "summary": "London (CNN) Germany may soon be home to .....",
    "full_article": "London (CNN) Germany may soon be home to the UK ...."
}
```

### Finance Data

```json
{
    "date": "2001-08-07",
    "open": 1.6097,
    "high": 1.618,
    "low": 1.6071,
    "close": 1.6147,
    "fx_pair": "GBP/EUR"
}
```
