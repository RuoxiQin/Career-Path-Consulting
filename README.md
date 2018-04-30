# Career-Path-Consulting

Career Path Consulting

Have you ever experienced when you know your career goal, but don't know how to achieve it? Have you had a hard time choosing a career path and didn't know which one leads to what you want? I propose a project to use the power of data to solve this problem and provide advice for people making their career decisions.

I use the LinkedIn profile dataset which records the education, experience and current positions of over millions of people. We can either use the data scraped by others or we can scrap the data by ourselves. To do the consulting, we also need the user's LinkedIn profile. We can get this data using the LinkedIn profile API.

For each consulting case, the user needs to input what kinds of people does she want to be by selecting the dream companies and the positions. The desired output of our project is the possible career paths from the user's current stage to her career goal by analyzing people who achieved the same goal and have similar experience as the user. The result also shows the proportion or the importance of each step to help the user make wise career decisions.

To solve this problem, we need to build a database of millions of people's working experience and group them by the name of the companies they have worked in and the corresponding positions. Then for a specific consulting query, we can filter out the people who have achieved the career goal. And we analyze what experience do these successes have when they are in the same stage as our user. We classify these experience into two types. One type is the experience which is hard to change, like the rank of their graduated universities. The other type is the experience they can gain in a short time, like whether they attended the Data Incubator! Then we assign a higher weight on the people who have similar hard-to-change experience as the user, and lower weight on the different ones. Since the career path of someone who graduates from Stanford might not suit for a user graduating from a community college.

Then we can explore the career paths of the successes. For example, if our user is about to graduate, we can explore what portion of successes choose to pursue a higher degree and what portion choose to work. Did they work at a big company in general positions, or they went to start-ups and dedicated on one field.  How important it is to get an internship. More importantly, is there any other paths to achieve the same career goal?

The difficulties of this project are scrapping the LinkedIn profile data and classify each experience into different areas. We can use the default area labels from LinkedIn as classification labels. We also need to combine the experience with other datasets like the USNews College Ranks to measure the similarity of education background.

This project provides meaningful information in the career consulting business. Since the consultant cannot explore the career paths in each area, this project provides rich possibilities of each specific consulting case driven by big data. Thus the consultant can provide more accurate advice for their customers. It can also be used as an independent product to provide the career advice and help users make wise career decisions.
