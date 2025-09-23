# Visualization_Power-BI_project

![powerbi-logo](https://github.com/user-attachments/assets/b67459a4-00d6-4be6-8675-f6eee8db0a37)

In this project I exhibited my Visualization skills using Microsoft Power BI and I was able to perform and create Reports, Dashboard and other important insight in decision-making through dashboard and reports.

In this project  we finalise our national survey report. We will use DAX to create measures and columns to enrich our data to ensure accurate and useful data representation on the dashboard. we use all the skills acquired in the course to build a public dashboard. We put together all we have learned in the module to create the survey report.
Our mission is to communicate with transparency: Where did the money go? We will track the total budget against project completion, monitor teams' performance, and compare budgeted versus actual costs to flag potential corruption, promoting transparency and accountability in addressing Maji Ndogo’s water crisis.

# D a t a a n d v i s u a l s

- Tailoring report designs into decison-maker
- Transformin analysis into strategic actions
- Crafting user-focused visual
- Customizing reports for localized decision making
- Crafting data narratives for impactful reporting.

We're creating this report to support decision-makers by providing them with accurate and understandable data relevant to their decisions. But what do they want? The best way of knowing is by putting yourself in their shoes. If we were the users, how would we want to interact with the dashboard? This is called a user story, which answers the question: "As a user, I want to..." and designing the report to meet that need.

Their user story is: As a leader of a particular province, I want to see data only relevant to my province. I need to understand the state of water access in my province, the scope of work we have to complete, and understand the financial aspects related to the improvements.

We will need to show the following data:

  1. Total people served for each water source type in a province.
  2. Number of water sources, their type, and whether it is rural or urban.
  3. Show the relevant stats for towns in that province.
  4. Add relevant provincial data. Queues, gender compositions and crime, broken taps by town, etc., in provinces where it is relevant.
  5. Summary of improvements and costs.

In our story there 3 components; Population/water breakdown, "What do we need to do?", and "How much will it cost?". Let's split our dashboard into three components, but also reserve some space for slicers somewhere, and reserve some space for the big idea results that are linked to the purpose: "How much do we need to spend in Maji Ndogo, and what will that
money do?"

### This is my thinking:

<img width="886" height="486" alt="Skitmap for the slicer task" src="https://github.com/user-attachments/assets/aaea07c1-5f9e-4edc-9d5b-758a35b3665a" />

I grouped similar things in boxes, and the three different boxes tell this story:
  • Who are we doing this for and where are they?
  • What do we need to do, and where do we need to do it?
  • What will this cost?
The data story is natural in this order. We don't start with cost, then who we're improving water for, and end with what we want to do. Make
sense?

<img width="846" height="481" alt="National_project for slicer" src="https://github.com/user-attachments/assets/fa0486e9-42da-4993-8463-cced6151a261" />

I also added a map which was provided as `JSON`file into Power BI. So now, when we select a province in the slicer, the map highlights where that province is.

<img width="504" height="335" alt="Mapping of maji_ndogo type of water source province" src="https://github.com/user-attachments/assets/b9642cb5-9f9b-4b5a-ac96-941c8ff9f788" />

Mapping of maji_ndogo type of water source province

<img width="2552" height="2028" alt="MD_Map" src="https://github.com/user-attachments/assets/4670371d-8237-421e-9ec6-638135206ad3" />

The `JSON`Map that was imported into Power BI

<img width="758" height="434" alt="National_level" src="https://github.com/user-attachments/assets/b8026751-5ca2-4148-9193-9595f3b84eef" />

The Report dashboard that shows the connections between the Province, Water_sourcce, Towns, and City.

<img width="558" height="349" alt="Av queue Hour_day and Day_week" src="https://github.com/user-attachments/assets/5daddffd-d2ff-469a-8169-2d1715e134ef" />

The Report showing Average queue Hour_day and Day_week in Maji_Ndogo (Line chart).

<img width="605" height="389" alt="Ave time_in_queue and number_people_served" src="https://github.com/user-attachments/assets/70b5209b-3292-46af-884d-8e4630d660bf" />

The Report showing Ave time_in_queue and number_people_served in Maji_Ndogo (Scattered chart).

<img width="567" height="382" alt="Ave_queue Percent male_female_children on each Day_of_week" src="https://github.com/user-attachments/assets/265c2a30-6d20-4e24-b1b2-42ef3fe43057" />

The report showing average queue percentage of Malle, Female, Children on each Day_of_week in Maji_Ndogo (Column chart)

<img width="552" height="359" alt="Ave_queue_time and Day_of_week" src="https://github.com/user-attachments/assets/bd05dea2-1076-42f4-bbf6-382e1f66b178" />

The report showing average queue time and day_of_week (Bar chart)

<img width="768" height="431" alt="Crime_related data" src="https://github.com/user-attachments/assets/02b7d7eb-132e-47c1-9580-07ea395cc5c5" />

A dashboard showing how Crimes are related by Gender, Time, and Province in Maji_Ndogo.

<img width="1252" height="492" alt="Improvements Bookmark" src="https://github.com/user-attachments/assets/095f4df8-102c-4f60-8932-c2dd1ce84679" />

A dashboard for making Bookmark in Power Bi and making a View restricted for other views to make the dashboard easy to access in Maji_Ndogo.

<img width="1248" height="483" alt="Province Bookmark" src="https://github.com/user-attachments/assets/5ea460b8-5def-47a5-90b5-8d6a9c2cd98b" />

A Bookmark dashboard showing how to restrict other views in Maji_Ndogo.

<img width="761" height="434" alt="Queue_visual" src="https://github.com/user-attachments/assets/0f465e0a-fa6a-4a98-89a3-002102c0baba" />

Dashboard showing how the flow of queue in the province and town in Maji_Ndogo.

<img width="376" height="330" alt="total population using the various water sources" src="https://github.com/user-attachments/assets/f304bb31-9540-4705-99ae-cff0e68d83de" />

Report showing total population using the various water sources in Maji_Ndogo.

<img width="370" height="335" alt="Urban vs Rural Population in Maji Ndogo" src="https://github.com/user-attachments/assets/4fa5460d-2367-4b68-9b5e-a66ace2cf38f" />

Report showing Urban vs Rural Population in Maji Ndogo.

# Conclusion

Now this report is far from perfect. It is better to get a report like this into the hands of the user, to see if they find it useful. This will enable us to generate more insight in the data and enable stackholders to be able to make very accurate decisions.
