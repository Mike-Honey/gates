# Gates Foundation - Grant Analysis
dataviz to analyse the Grants given by the Bill & Melinda Gates Foundation and previous foundations of the Gates family (William H. Gates Foundation, Gates Library Foundation, and Gates Learning Foundation) from 1994 onward.

[Link to interactive infographic - Decomposition Tree](https://app.powerbi.com/view?r=eyJrIjoiNTllMTliNjktNWVlYy00YTk5LWFhYjItMjUwYzMxZjQwY2Y2IiwidCI6ImRjMWYwNGY1LWMxZTUtNDQyOS1hODEyLTU3OTNiZTQ1YmY5ZCIsImMiOjEwfQ%3D%3D&pageName=ReportSection874449a5dc80e84560dc)

[![Click to view and interact with the report](https://github.com/Mike-Honey/gates/raw/main/BMGF-Grants-Decomposition-Tree.png)](https://app.powerbi.com/view?r=eyJrIjoiNTllMTliNjktNWVlYy00YTk5LWFhYjItMjUwYzMxZjQwY2Y2IiwidCI6ImRjMWYwNGY1LWMxZTUtNDQyOS1hODEyLTU3OTNiZTQ1YmY5ZCIsImMiOjEwfQ%3D%3D&pageName=ReportSection874449a5dc80e84560dc)

[Link to interactive infographic - Bar Charts](https://app.powerbi.com/view?r=eyJrIjoiNTllMTliNjktNWVlYy00YTk5LWFhYjItMjUwYzMxZjQwY2Y2IiwidCI6ImRjMWYwNGY1LWMxZTUtNDQyOS1hODEyLTU3OTNiZTQ1YmY5ZCIsImMiOjEwfQ%3D%3D&pageName=ReportSection0dd8b278a1c7c0addc64)

[![Click to view and interact with the report](https://github.com/Mike-Honey/gates/raw/main/BMGF-Grants-Bar-Charts.png)](https://app.powerbi.com/view?r=eyJrIjoiNTllMTliNjktNWVlYy00YTk5LWFhYjItMjUwYzMxZjQwY2Y2IiwidCI6ImRjMWYwNGY1LWMxZTUtNDQyOS1hODEyLTU3OTNiZTQ1YmY5ZCIsImMiOjEwfQ%3D%3D&pageName=ReportSection0dd8b278a1c7c0addc64)

[Link to interactive infographic - Purpose Word Cloud](https://app.powerbi.com/view?r=eyJrIjoiNTllMTliNjktNWVlYy00YTk5LWFhYjItMjUwYzMxZjQwY2Y2IiwidCI6ImRjMWYwNGY1LWMxZTUtNDQyOS1hODEyLTU3OTNiZTQ1YmY5ZCIsImMiOjEwfQ%3D%3D&pageName=ReportSection9b6c1d69de91c8ebbd58)

[![Click to view and interact with the report](https://github.com/Mike-Honey/gates/raw/main/BMGF-Grants-Purpose-Word-Cloud.png)](https://app.powerbi.com/view?r=eyJrIjoiNTllMTliNjktNWVlYy00YTk5LWFhYjItMjUwYzMxZjQwY2Y2IiwidCI6ImRjMWYwNGY1LWMxZTUtNDQyOS1hODEyLTU3OTNiZTQ1YmY5ZCIsImMiOjEwfQ%3D%3D&pageName=ReportSection9b6c1d69de91c8ebbd58)

**Reference:**

Dataviz using data from [Gates Foundation - Committed grants page]([https://ourworldindata.org/](https://www.gatesfoundation.org/about/committed-grants)), where a downloadable database (CSV file) is provided detailing the grants. 

Inspired by [an interview](https://www.linkedin.com/feed/update/urn:li:activity:7176602182513782784/) of [Bill Gates](https://www.linkedin.com/in/williamhgates/) by [Chris Anderson](https://www.linkedin.com/in/chris-anderson-3b2a05bb), where Bill discussed their philanthropic efforts over the years.

**Summary**

This project presents a series of interactive dashboard pages to help analyse and understand the $87BN given since 1994.  The page navigation control is at the centre-bottom, e.g. **< 1 of 3 >**. Click the centre of that control for a menu of the pages.

On every page, slicer controls allow the selection of range of grant dates.  There are also slicers to filter by Division, Region Served, Topic, Grantee location, even individual Grantees and Grants. Combined with visuals on each page that segment and compare the data, many different analyses are possible.  Each visual element e.g. bar of a bar chart can be selected, when it will act as a "cross-filter" to filter every other visual on that page.

On every page, a detailed table at the bottom lists the individual Grants within the scope of the current slicer settings. The Grant Id column in the table has a hyperlink to the Grant Details page on the Gates Foundation website. The Grantee column has a hyperlink to the Grantee website, where provided in the data. The table can be resorted by clicking any column header, and the **Focus mode** button (which appears at the top-right corner of the table on hover) will expand the table to fill the browser window.

The page: **Purpose Word Cloud** presents a word cloud analysis of the contents of the Purpose column (a free text description of each Grant). Each word is sized relative to the $ Amount Committed for Grants that mention that word.

There is a hidden page using the [Key Influencers visual](https://learn.microsoft.com/en-us/power-bi/visuals/power-bi-visualization-influencers?tabs=powerbi-desktop), which is a very powerful no-code, AI-powered analysis engine for understanding the relationships within the data. After every interactive filter you choose, the engine re-runs it's analysis to explore which factors are the Key Influencers for a variable - in this project $ Amount Committed. That visual is not supported by this publishing method, but you can install the free Power BI Desktop tool, download the .PBIX file from this project and open it to explore that page.

![Key Influencers page](https://github.com/Mike-Honey/gates/raw/main/BMGF-Grants-Key-Influencers.png)]

The data visualisation engine is [Power BI](https://powerbi.microsoft.com), featuring the Custom Visual:  [Word Cloud](https://appsource.microsoft.com/en-us/product/power-bi-visuals/WA104380752?tab=Overview). 
