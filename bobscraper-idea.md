In this project, I intend to develop a web-scraper to scrape content from a website and to display that data on a second website. 

I am developing this tool on my local development machine where the functionality will need to be tested, but in production, it will be deployed on my web server where I have cPanel access. I want to work on this project in a manner that makes this eventual migration from development to production as easy as possible. 

I believe the best tools to use for this job will include node.js, npm, and the playwright library by Microsoft. That list should be considered neither exhaustive or exclusive. In other words, I am open to any suggestions you may have regarding the best software stack to use for the functionality, which I will explain below:

1. User goes to "Website A" where they are presented with an empty table like this:

|      | Puts | Calls | Ratio |
|------|------|-------|-------|
|OEX   |      |       |       |

2. "Website A" requests that "Website B" be scraped for the data that will fill that table.

3. The software that fulfills this request will need to perform a selection from a drop-down menu, click a button, find the requested data, save it in memory.

4. Depending on which is the better choice, either the server-side script or the client-side script will perform mathematical calculations on the data.

5. The data, whether raw or calculated, will be transported back to "Website A" where it will fill in and re-display what had been the empty table, like so:

|      | Puts | Calls | Ratio |
|------|------|-------|-------|
|OEX   | x | y | x/y |

Anything more specific regarding the functionality will be discussed in later steps.

Please develop an implementation plan for the above.