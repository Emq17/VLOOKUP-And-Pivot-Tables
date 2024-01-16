<p align="center">
<img src="https://i.imgur.com/oyzKMtJ.png" alt="Logo"/>
</p>

<h1 align="center">VLOOKUP</h1>

In this repository, I'm excited to share a quick example highlighting how I've effectively utilized the VLOOKUP function as a valuable tool within previous Data Specialist roles. Join me in exploring the practical application of this feature, making tasks more efficient and data manipulation a seamless experience.

<h2>What is VLOOKUP?</h2>
VLOOKUP is a powerful tool for quickly and efficiently locating and retrieving information from large datasets in a vertical direction, making it a fundamental function in data analysis and management within spreadsheet applications. VLOOKUP, short for Vertical Lookup, is a function in Microsoft Excel and other spreadsheet software designed to search for a specific value in the first column of a table or range. Once the function identifies the matching value, it retrieves data from a specified column in the same row. The syntax for the VLOOKUP function includes the lookup value, the table or range where data is stored, the column number from which to retrieve the data, and an optional parameter indicating whether to find an exact or approximate match.

<h2>Scenario</h2>

I used the VLOOKUP function to simplify the extraction and analysis of data from large databases. For example, when working with two separate files—one containing price information and the other detailing net/gross weights—VLOOKUP was incredibly helpful. The challenge was to create a consolidated table matching the order of the first file, even though the item order differed in both files.

To illustrate, imagine dealing with 500 items and needing to create a column displaying their weights. Instead of manually searching the second file for each item, I utilized VLOOKUP. By establishing a connection between a specific criterion (like the item's name) in the first file and the corresponding data in the second file, VLOOKUP automatically fetched the required weight information. This not only saved a significant amount of time but also made the process much more efficient.

- Below is a part of the invoice. I will have to create a summary table that must match the order of these items.
- Next, I will have to find the weights from the other file and match it with the corresponding part number or description whichever is available.

![Screen Shot 2024-01-15 at 8 04 29 PM](https://github.com/Emq17/VLOOKUP-Function/assets/147126755/eaadddaf-cecc-4c0b-80bb-ccc86f456015)

- Below is an example of information regarding the weights of certain units from the other file

![Screen Shot 2024-01-15 at 8 02 54 PM](https://github.com/Emq17/VLOOKUP-Function/assets/147126755/84e6bc8b-3358-49bc-8156-cd0e8b7f94f1)

![Screen Shot 2024-01-15 at 8 03 18 PM](https://github.com/Emq17/VLOOKUP-Function/assets/147126755/efe32b5b-06cf-4ac3-a54f-c6ff97724d8b)

- I can also implement the VLOOKUP Function for other columns & not just when I'm looking for the corresponding weights.
- Here you can see in the final tab how I was able to use this tool to combine information from the invoice tab into the packing list tab

![Screen Shot 2024-01-15 at 8 11 36 PM](https://github.com/Emq17/VLOOKUP-Function/assets/147126755/9a14928a-d520-4b91-b7e4-bec0e2f3ad0d)

![Screen Shot 2024-01-15 at 8 11 21 PM](https://github.com/Emq17/VLOOKUP-Function/assets/147126755/22967edf-5a1a-4943-a79b-4c8b0c927e7a)

![Screen Shot 2024-01-15 at 8 11 03 PM](https://github.com/Emq17/VLOOKUP-Function/assets/147126755/5b87e0d1-d9ac-43ab-8c0d-b8c18df869da)

<h2>What Are Pivot Tables?</h2>

A Pivot Table is a data processing and analysis tool in spreadsheet software, such as Microsoft Excel. It allows users to summarize and rearrange selected columns and rows of data from a larger dataset, providing a more organized and condensed view for analysis. Users can dynamically reorient the data, apply functions, and create cross-tabulations, making it easier to explore patterns, trends, and relationships within the information. Pivot Tables are particularly valuable for simplifying complex datasets and gaining insights into the data's structure, facilitating effective decision-making in data analysis tasks.

<h2>Scenario</h2>
For Pivot Tables, I would also utilize them to identify not only the top heaviest or lightest items by weight but also to discern which items held the highest value based on price. This powerful tool enabled me to delve into comprehensive data analysis, providing insights into the weight distribution and value hierarchy of items. Whether it was pinpointing the weight outliers or identifying the most valuable assets, Pivot Tables proved instrumental in extracting meaningful patterns and facilitating informed decision-making. Unfortunately, privacy constraints and the sensitivity of company data prevents me from sharing these tables publicly.


<h2>Conclusion</h2>

In summary, I use these tools to quickly find important data when creating new tables and combining information. They act like shortcuts, saving me from doing repetitive manual tasks. Although I won't go into all the small details, it's essential to clean up and organize your data first before diving in. Despite these prep steps, these tools are amazing. They've saved me a lot of time and made working with data much easier.
