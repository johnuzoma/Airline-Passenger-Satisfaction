### Executive Summary
Using Power BI, I created a dashboard showcasing customer satisfaction scores from 120,000+ airline passengers of a hypothetical airline, including additional information about each passenger, their flight, and type of travel, as well as ther evaluation of different factors like cleanliness, comfort, service, and overall experience.

### Ordered workflow in getting to the solution

1. Data import from csv file.
2. Data transformed in Power Query and loaded to data model.
3. Six many-to-one relationships created to form a star schema.
4. Visuals created in report view, enriched with relevant DAX measures.

### Data model I implemented (star schema)
![image](https://github.com/user-attachments/assets/2f0d923f-5080-49dd-b34c-97bbedbee93c)

### Data visualization

1. Proportions of customers across different segments such as flight class, age split, cutomer type and purpose of travel.
2. Key dissatisfied customer segements.
3. Major contributors to customer dissatisfaction.
4. Strategic recommendations to improve customer satisfaction across those 3 major contributors.
<img width="774" alt="final_report" src="https://github.com/johnuzoma/Uji-Airline-Passenger-Satisfaction/assets/18267074/c361e000-ccb0-4cdb-9c11-03513b647cf7">

### Solution Deliverables
They can be accessed via the [solution](https://github.com/johnuzoma/Airline-Passenger-Satisfaction/tree/main/solution) folder.

Deliverables include -

1. Final report that includes intuitive and compelling visuals to tell the story.
2. Data model: Star schema (with 6 many-to-one relationships).
3. All Power Query tables: 1 fact table and 6 dimension tables.

