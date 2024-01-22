<p align="center">
<img src="https://i.imgur.com/oyzKMtJ.png" alt="Logo"/>
</p>

<h1 align="center">VLOOKUP</h1>

I will share a quick example highlighting how I've effectively utilized the VLOOKUP function as a valuable tool within previous Data Specialist roles. Join me in exploring the practical application of this feature, making tasks more efficient and data manipulation a seamless experience.

<h2>What is VLOOKUP?</h2>
VLOOKUP is a powerful tool for quickly and efficiently locating and retrieving information from large datasets in a vertical direction, making it a fundamental function in data analysis and management within spreadsheet applications. VLOOKUP, short for Vertical Lookup, is a function in Microsoft Excel and other spreadsheet software designed to search for a specific value in the first column of a table or range. Once the function identifies the matching value, it retrieves data from a specified column in the same row. The syntax for the VLOOKUP function includes the lookup value, the table or range where data is stored, the column number from which to retrieve the data, and an optional parameter indicating whether to find an exact or approximate match.

<h2>Formula</h2>

We can use the VLOOKUP function with the help of a simple syntax. The Syntax for VLOOKUP is:

`=VLOOKUP(lookup_value, table_array, col_index_number,[range_lookup])`

Where, 

- lookup_value: This specifies the value that you want to look up in our data.
- table_array: This is the location where the values are present in excel.
- col_index_number: This specifies the column number from where we need to return the value.
- range_lookup: This has two options; if the value is set to FALSE, that means we are looking for an exact match. If the value is TRUE, then we are looking for an approximate match.

<h2>Scenario</h2>

I used the VLOOKUP function to simplify the extraction and analysis of data from large databases. For example, when working with two separate files—one containing price information and the other detailing net/gross weights—VLOOKUP was incredibly helpful. The challenge was to create a consolidated table matching the order of the first file, even though the item order differed in both files.

To illustrate, imagine dealing with thousands of items and needing to create a column displaying their weights. Instead of manually searching the second file for each item, I utilized VLOOKUP. By establishing a connection between a specific criterion (like the item's name) in the first file and the corresponding data in the second file, VLOOKUP automatically fetched the required weight information. This not only saved a significant amount of time but also made the process much more efficient.

- Below is the file where invoice is located. I will have to create a summary table that must match the order of these items. I had to be careful with exposing company data so I blocked out certain parts.
- Next, I will have to find the weights from the other file and match it with the corresponding part number or description whichever is usually available.

![Screen Shot 2024-01-15 at 9 29 40 PM](https://github.com/Emq17/VLOOKUP-And-Pivot-Tables/assets/147126755/ab8bd43a-05d0-44ba-bda4-fecca43276f9)


- Below is the separate packing list file included with information regarding the weights of certain units.
- As you can see the order does not match from the first file.
- This is when I use the VLOOKUP Function to extract data from both files in order to create a summarized table combining all the information together as well as adding more wanted details.

![Screen Shot 2024-01-15 at 9 22 11 PM](https://github.com/Emq17/VLOOKUP-And-Pivot-Tables/assets/147126755/fd72873c-858f-4bbd-b278-9c944b034c94)

- I can also implement the VLOOKUP Function for other columns & not just when I'm looking for the corresponding weights.
- Here you can see in the `FINAL` tab how I was able to use this tool to combine information from the `pl` tab into the `inv` tab

![Screen Shot 2024-01-15 at 8 11 36 PM](https://github.com/Emq17/VLOOKUP-Function/assets/147126755/9a14928a-d520-4b91-b7e4-bec0e2f3ad0d)

![Screen Shot 2024-01-15 at 8 11 21 PM](https://github.com/Emq17/VLOOKUP-Function/assets/147126755/22967edf-5a1a-4943-a79b-4c8b0c927e7a)

![Screen Shot 2024-01-15 at 8 11 03 PM](https://github.com/Emq17/VLOOKUP-Function/assets/147126755/5b87e0d1-d9ac-43ab-8c0d-b8c18df869da)

<h2>More Examples</h2>

- As you can see below the first table is where all the data is collected
- I use the VLOOKUP Function to create two more tables to help extract specific information by just inputting in different "Patient ID" numbers
- The "Name" and "Notes" cells in both tables automatically populates what information is linked with that ID

![Screen Shot 2024-01-22 at 11 29 33 AM](https://github.com/Emq17/VLOOKUP-And-Pivot-Tables/assets/147126755/313ff705-6858-4376-b208-3b449f533ba7)
![Screen Shot 2024-01-22 at 11 30 09 AM](https://github.com/Emq17/VLOOKUP-And-Pivot-Tables/assets/147126755/7fd42e5d-e763-4e1e-8d28-cd07d408a5b8)


<h2>What Are Pivot Tables?</h2>

A Pivot Table is a data processing and analysis tool in spreadsheet software, such as Microsoft Excel. It allows users to summarize and rearrange selected columns and rows of data from a larger dataset, providing a more organized and condensed view for analysis. Users can dynamically reorient the data, apply functions, and create cross-tabulations, making it easier to explore patterns, trends, and relationships within the information. Pivot Tables are particularly valuable for simplifying complex datasets and gaining insights into the data's structure, facilitating effective decision-making in data analysis tasks.

<h2>Scenario</h2>
For Pivot Tables, I would also utilize them to identify not only the top heaviest or lightest items by weight but also to discern which items held the highest value based on price. This powerful tool enabled me to delve into comprehensive data analysis, providing insights into the weight distribution and value hierarchy of items. Whether it was pinpointing the weight outliers or identifying the most valuable assets, Pivot Tables proved instrumental in extracting meaningful patterns and facilitating informed decision-making. Unfortunately, privacy constraints and the sensitivity of company data prevents me from sharing these tables publicly.

<h2>More Examples</h2>

- I created a quick table with random data inside of it on one sheet then created a pivot table for it onto another sheet below
- There are so many things you can do with pivot tables that'll help provide you with more insights of your data
  - On the right side you can see a section where you can just drag and drop certain parts of your data in order to find the things you need 
- Below I was able to filter by Patient & automatically add up what their current overall balance were if they had multiple vists
  - You can see whenever I click on the Patient number the table automatically displays that Patients added up data 

![Screen Shot 2024-01-22 at 11 37 23 AM](https://github.com/Emq17/VLOOKUP-And-Pivot-Tables/assets/147126755/a6aa1ea1-d7a0-4332-9572-d516a67e979a)
![Screen Shot 2024-01-22 at 11 37 46 AM](https://github.com/Emq17/VLOOKUP-And-Pivot-Tables/assets/147126755/2910b505-d73b-4214-bc56-5bdeb6d6a02d)
![Screen Shot 2024-01-22 at 11 38 03 AM](https://github.com/Emq17/VLOOKUP-And-Pivot-Tables/assets/147126755/63069eb5-3807-4ff6-a857-d54430c0c74f)


<h2>Conclusion</h2>

In summary, I use these tools to quickly find important data when creating new tables and combining information. They act like shortcuts, saving me from doing repetitive manual tasks. Although I didn't go into all the small details, it's essential to clean up and organize your data first before diving in. Despite these prep steps, these tools are amazing. They've saved me a lot of time and made working with data much easier.
