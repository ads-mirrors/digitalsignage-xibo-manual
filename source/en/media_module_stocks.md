---
toc: "widgets"
maxHeadingLevel: 3
minHeadingLevel: 2
excerpt: "Display trade price information for stock listings"
keywords: "alpha vantage api, alpha vantage connector"
persona: "content manager"
---

# Stocks

Display trade price information for stock listings anywhere on a Layout using **Elements** or select a **Static Template** to display results in Layouts/Playlists.

The Stocks Widget relies in part on the [Alpha Vantage API](https://www.alphavantage.co/) to retrieve stock market data which feeds into configured Elements and Static Templates. The prices returned by Alpha Vantage follow the [stock market standard](https://medium.com/@patrick.collins_58673/stock-api-landscape-5c6e054ee631) of adjusting for corporate events such as splits and dividend payout.

{noncloud}
Please visit [Alpha Vantage](https://www.alphavantage.co/support/#api-key) to create an account and obtain an API key to enter into the Alpha Vantage [Connector.](media_modules_connectors.html)
{/noncloud}

If you need a stock symbol that is only quoted on a specific exchange then you can use the format `SYMBOL:EXCHANGE` to return results. 
Stock symbols can be found on various lookup sites such as [Yahoo Finance](https://finance.yahoo.com/)!

{nonwhite}
{cloud}
The Currencies Module is configured for **Xibo Cloud** hosted customers with an API key provided as part of the service.
{/cloud}
{/nonwhite}

## Overview

- Content for this media is cached by the Players for off-line playback.
- Duration can be applied per item or per page.





















