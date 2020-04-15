## Datasets

HTTP Archive includes a number of different datasets. Here are [brief descriptions](https://discuss.httparchive.org/t/what-are-the-effects-of-the-covid-19-pandemic-on-web-usage-and-experience/1901/3) from Rick Viscomi:

`pages` - JSON data about each page including loading metrics, CPU stats, optimization info, and more

`requests` - JSON data about each request including request/response headers, networking info, payload size, MIME type, etc

`response_bodies` - (very expensive) Full payloads for text-based resources like HTML, JS, and CSS

`summary_pages` - A subset of high-level stats per page

`summary_requests` - A subset of high-level stats per request

`technologies` - A list of which technologies are used per page, detected by Wappalyzer

`blink_features` - A list of which JavaScript, HTML, or CSS APIs are used per page

`lighthouse` - (mobile only) Full JSON Lighthouse report containing audit results in areas of accessibility, performance, mobile friendliness, SEO, and more

## Costs

As of April, 2020:

- Queries (on-demand): $5.00 per TB. This is $0.05 per GB.
