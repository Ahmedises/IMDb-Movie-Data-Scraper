# IMDb-Movie-Data-Scraper
This project focuses on scraping JavaScript-rendered pages from IMDb to extract detailed movie information, including titles, ratings, genres, high-quality posters, directors, and writers. The goal was to collect accurate, structured data to feed content for a movie-focused channel.

The process began using Playwright to render dynamic content and interact with page elements. Later, I integrated Scrapy-Playwright, combining Playwright’s rendering power with Scrapy’s pipelining and item processing abilities. This allowed the scraper to handle large-scale requests efficiently while maintaining clean, organized datasets.

IMDb’s strong bot detection system required advanced countermeasures, including custom HTTP header strategies to mimic real browser traffic and rotating proxy IPs to avoid bans. These methods ensured stable access over long scraping sessions.

By merging dynamic rendering handling with robust anti-bot bypass techniques, the scraper consistently delivered high-quality data despite IMDb’s JavaScript-heavy and detection-rich structure.
