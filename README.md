# IMDb-Movie-Data-Scraper
Objective: Extract detailed information for IMDb’s top movies, including titles, ratings, genres, and high-quality posters, from a JavaScript-rendered site.

Initial Approach: Started with Playwright to handle client-side rendering and interact with dynamic elements on the page.

Integration: Migrated to Scrapy-Playwright to take advantage of Scrapy’s pipelining, item processing, and scalability, while still benefiting from Playwright’s rendering capabilities.

Bot Detection Challenge: IMDb uses a strong bot detection system. Implemented custom HTTP headers to mimic genuine browser behavior, combined with rotating proxy IPs to avoid blocking
