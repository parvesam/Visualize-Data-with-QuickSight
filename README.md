# Visualize-Data-with-QuickSight

## Amazon QuickSight Visualization Project

**Project Overview:**  
Amazon QuickSight is a powerful tool in AWS for visualizing data and gaining insights from datasets. In this project, I used Amazon QuickSight to visualize a Netflix dataset, transforming raw data into intuitive charts and graphs.

<img width="552" alt="Screenshot 2024-09-09 130146" src="https://github.com/user-attachments/assets/eafe9c48-2e99-4e6f-a786-ecaaa944e1da">


**S3 Integration:**  
As part of the project, I utilized Amazon S3 to store two files: `netflix_titles.csv` and `manifest.json`. The `manifest.json` file required an update to reflect the correct S3 URI, ensuring the dataset was properly linked for visualization in QuickSight.

<img width="433" alt="Screenshot 2024-09-09 134214" src="https://github.com/user-attachments/assets/90748130-dc87-4159-9bf7-22999a701782">


**Creating a QuickSight Account:**  
Creating a QuickSight account is free and took me about two minutes to complete. The setup process was smooth and fast, making it easy to get started with the project.

<img width="468" alt="Screenshot 2024-09-09 134356" src="https://github.com/user-attachments/assets/a8847526-ba2b-40a9-bc0a-0d8ea6ac378e">

**Downloading the Dataset:**  
I enabled QuickSight's access to S3 in order to process the dataset stored in my bucket. The `manifest.json` file played a critical role in this step by helping QuickSight correctly locate the dataset within S3.

<img width="565" alt="Screenshot 2024-09-09 134433" src="https://github.com/user-attachments/assets/0b16a58d-799b-450f-8b2b-de2f803221c3">


**My First Visualization:**  
To create visualizations in QuickSight, I dragged relevant fields into the AutoGraph space in the dashboard. My first visualization was a breakdown of movies vs. TV shows for every release year. I achieved this by dragging the release year onto the y-axis and the type (movies/TV shows) into the grouping variable.

<img width="414" alt="Screenshot 2024-09-09 134524" src="https://github.com/user-attachments/assets/28884e6f-4443-43d7-a2e1-57fe84489be3">


**Using Filters:**  
Filters are useful for specifying the exact subset of data you want to analyze, excluding any irrelevant data. For example, in this visualization, I created a breakdown of three genres released between 2015 and 2021. I applied a filter to exclude movies and TV shows released before 2015, focusing only on the relevant timeframe.

<img width="549" alt="Screenshot 2024-09-09 134609" src="https://github.com/user-attachments/assets/ffdf03bf-11e4-4a91-abd0-4ba724db4164">


**Setting Up a Dashboard:**  
As a finishing touch, I edited the titles of my graphs to ensure the purpose of each chart was clear to the reader. QuickSight also allows you to export dashboards as PDFs. After publishing my dashboard, I used the export function to download it as a PDF for easy sharing.

<img width="564" alt="Screenshot 2024-09-09 134735" src="https://github.com/user-attachments/assets/d8a4172e-6f9a-478b-9c83-76593eb8c7e1">


**What I Learned:**  
One unexpected aspect of this project was how enjoyable it was to learn Amazon QuickSight. I was pleasantly surprised by how quickly and easily I could create compelling visualizations.

**Time to Complete:**  
This project took approximately one hour to complete.
