# Robots Analysis for the Daily Pennsylvanian

The Daily Pennsylvanian's `robots.txt` file is available at
[https://www.thedp.com/robots.txt](https://www.thedp.com/robots.txt).

## Contents of the `robots.txt` file on 2/24/25

```
User-agent: *
Crawl-delay: 10
Allow: /

User-agent: SemrushBot
Disallow: /
```

## Explanation

Line by line 

The first line ensures this appplies to all agents (because of the wildcard)
Second line tells bots to wait 10 secs between requests to avoid overloading server
Third line explicitly allows all bots to access all pages of the website.

This second paragraph specifically addresses the SemrushBot, some web crawler out there.
This last line blocks this SemrushBot from accessing any and all pages of the website.
