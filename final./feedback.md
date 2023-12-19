# Feedback on your final

**Final Score: 46/60**

The grading rubric for the final can be found in GitHub: https://github.com/paulboal/hds5210-2023/blob/main/final/final-instructions.pdf

**Functional Requirements**
* 5 points - Uses data from at least two different sources: local file, internet, web service, relational database, AWS S3, etc; and formats: CSV, JSON, database, XML, Excel, etc
* 5 points - Data from multiple sources has to be joined together at least twice
* 5 points - Data is aggregated or pivoted at least twice during the program
* 5 points - Some kind of field-level transformation is performed at least 5 times
* 5 points - The program creates 3 or more data visualizations 
* 5 points - The program serves a theoretical purpose described in documentation, that could potentially do something in healthcare or another industry of interest

**Modularity / Style**
* 15 points - The code is broken up into various functions or classes to make testing and reuse easier

**Documentation and Professionalism**
* 15 points - All functions are documented and notebook cells include annotations and explanations.


**(-10) Your folder for the final got named with a period at the end: "final." instead of "final".  I decided that since it was so close, I would grade your work rather than giving you a 0 on the final as I said I'd do if you didn't submit correctly.**

**(-1) Merging (joining) on a column that isn't unique or on the default columns by name ends up applything the rows from one side of the joint to multiple rows on the other side.  It ends up duplicating rows.**

**(-2) Concatneating the hosptial and medicine data doesn't make sense.  You can tel because of how many NaN there are.**

**(-1) Generic variable names like `pivot1` or `merged` are not acceptable.  They make it hard for the reader to understand what is going on and what this variable refers to.**

**Your project was very good overall. I wish it hadn't been submitted incorrectly. :( Still, your work was pretty good. Congratulations!**