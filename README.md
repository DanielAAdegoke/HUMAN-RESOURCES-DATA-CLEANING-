<h1 style="font-size: 26px;">Human Resources Data Cleaning</h1>

<p style="font-size: 16px;">
This project is centered around the meticulous cleaning and preparation of the "human resources 2" dataset for subsequent analysis. The data cleaning process encompasses tasks such as rectifying date format inconsistencies, addressing missing values, and introducing a new column to capture age-related information. Below is a comprehensive overview of each step taken in this data cleaning journey:

<h1 style="font-size: 20px;">Project Objectives </h1>

- Standardizing Date Formats: Ensure that date formats across different columns (birthdate, hire date, termination date) are consistent and adhere to SQL standards for ease of analysis.
- Age Calculation: Derive the age of each employee based on their birthdate, providing valuable demographic insights.
- Data Integrity: Handle missing values and resolve discrepancies in date formats to enhance overall data integrity.

 <h1 style="font-size: 20px;">Data Cleaning Steps</h1>
 
<h1 style="font-size: 20px;">1. Describe the Initial Dataset</h1>

The project commenced with a thorough examination of the structure and characteristics of the "human resources 2" dataset using the `DESCRIBE` command.

 <h1 style="font-size: 20px;">2. Changing Date Formats </h1>

<h1 style="font-size: 18px;">Birthdate Column </h1>

The birthdate column underwent a meticulous cleaning process, addressing variations in date formats. The resulting uniformity was enforced by modifying the column type to `DATE`.

<h1 style="font-size: 18px;">Hire Date Column </h1>

Similar to the birthdate column, the hire date column underwent cleaning to standardize date formats, and the column type was adjusted to `DATE` for consistency.

<h1 style="font-size: 18px;">Termination Date Column  </h1>

The termination date format was updated, and special consideration was given to cases where the date format included time information. The column type was then modified to `DATE`.

 <h1 style="font-size: 20px;">3. Creating an Age Column </h1>

A new column, "age," was introduced to the dataset. This column was populated with age values calculated based on the birthdate column, providing a crucial demographic dimension for analysis.

<h1 style="font-size: 20px;">4. Finding Age Range  </h1>

The dataset was further analyzed to determine the age range of employees. Additionally, a count of employees below 18 years old was obtained to gain insights into the age distribution within the organization.

<h1 style="font-size: 20px;">Next Steps </h1>

Following the successful completion of data cleaning, the dataset is now primed for in-depth analysis. Future steps may involve exploratory data analysis, visualization, and the development of predictive models to extract valuable insights from the "human resources 2" dataset.
</p>
