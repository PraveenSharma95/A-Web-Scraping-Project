<img src="https://github.com/PraveenSharma95/A-Web-Scraping-Project/blob/main/Raw%20files/1mg%20logo.JPG" width="100" height="80" > <h1>**One mg - Homeopathic medicines' Analysis** </h1>

Tata 1mg, previously 1mg, is a healthcare platform based in Gurugram, India. It provides services, including e-pharmacy, diagnostics, e-consultation and health content. It was founded in April 2015 by Prashant Tandon, Gaurav Agarwal and Vikas Chauhan. 

<h2> Objective </h2> 
The main objective of the project was to suggest/consult the client while analysing the 1 mg's dynamic website's homeopathy section by applying web scraping - Exploratory Data Analysis and dedcing insights for an opening of HOMEOPATHY STORE in the market.

<br>
<br>
<br>
<p align="left"><a><img src="https://github.com/PraveenSharma95/A-Web-Scraping-Project/blob/main/Raw%20files/objectives.JPG" width ="300" height = "100"> </p>              <p align="right"><a><img src="https://github.com/PraveenSharma95/A-Web-Scraping-Project/blob/main/Raw%20files/approach.JPG" width ="300" height = "100"> </p>





<br>
<br>
<p align="center"><a> <img src="https://forthebadge.com/images/badges/built-with-love.svg"> <img src = "https://github.com/PraveenSharma95/A-Web-Scraping-Project/blob/main/Raw%20files/made-with.svg"> <img src = "https://github.com/PraveenSharma95/A-Web-Scraping-Project/blob/main/Raw%20files/python-selenium.svg"> <img src = "https://github.com/PraveenSharma95/A-Web-Scraping-Project/blob/main/Raw%20files/microsoft-excel-power-point%20(1).svg"> <img src = "https://github.com/PraveenSharma95/A-Web-Scraping-Project/blob/main/Raw%20files/power-bi.svg">
</p>

<br>
<br>


<img src="https://user-images.githubusercontent.com/106439762/181935629-b3c47bd3-77fb-4431-a11c-ff8ba0942b63.gif" width="48" height="48"> **User's Manual** <p>
| Files/Folder| Description |
| ------------|-------------|
| **CSV**                     | This folder contains the extracted tables from ipynb files in CSV formats and the raw datasets. |
| **Raw Files**               | This folder provides the raw data for the analysis and images for readme files for github .|
|  **Excel**                  | This folder contains the aggregated sheets of excel file containing the insights. |
|  **IPYNB Files**            | This folder contains the file having web scraping and EDA to fetch the desired tables for insights.|
| **Power BI Dashboard**      | This folder contains the pbx file showcasing the visualization and dashboard for insights.|
| **1Mg Project PPT**         | This contains the powerpoint presentation of the project delivering the results as per the objective|
</p>
<br>
<br>
<img src="https://user-images.githubusercontent.com/106439762/181937125-2a4b22a3-f8a9-4226-bbd3-df972f9dbbc4.gif" width="48" height="48" > <h4>Quick Start</h4>

  *1. WEB SCRAPING and Exploratory Data Analysis :*
    
    o Used Python library - Selenium ( as the website is dynamic) for extracting the data from 
      homeopathy medicine's category of TATA 1mg's website to store it into two tables :
      Table1 = Medicine name with its features like  size, maximum retail price, discounted price, star ratings, reviews.etc
      Table2 = Medicine with its ingredients, Key Benefit Areas.etc
<br>
<img src="https://github.com/PraveenSharma95/A-Web-Scraping-Project/blob/main/Raw%20files/web%20scraping%20_%20jupyter%20notebook.JPG" width="900" height="600" >

 
    o	Used Python libraries - pandas, numpy to perform EDA and seperate kew words from Ingredients and Key Benefit Areas.

<br>
<img src="https://github.com/PraveenSharma95/A-Web-Scraping-Project/blob/main/Raw%20files/T1.JPG" width="400" height="200" > <img src="https://github.com/PraveenSharma95/A-Web-Scraping-Project/blob/main/Raw%20files/eda%201.JPG" width="800" height="200" >
<img src="https://github.com/PraveenSharma95/A-Web-Scraping-Project/blob/main/Raw%20files/eda%202.JPG" >
<img src="https://github.com/PraveenSharma95/A-Web-Scraping-Project/blob/main/Raw%20files/eda3.JPG" >



    o  After extracting the first 40 pages of website, Tables were created for 1200+ medicines, and
       were stored in CSVs for analysis.

*2. Analyzing the Tables for insights :*

    o  Excel was used for creating pivot tables, rows to columns and vice-versa in order to generate the number of times
       a particular ingredient is used, and to generate the number of times a particular medicine benefits 
       the particular body part (Focused areas - Hair, Joints, Skin, Eyes).

*3. Creating Dashboard :*

    o  POWER BI was used for creating aggregations, dashboard and generation of useful insights in order to suggest 
       which all medicines should a client consider while setting up a HOMEOPATHY STORE in the desired market.
       
<br>
<br>

<img src=https://user-images.githubusercontent.com/106439762/178428775-03d67679-9aa4-4b08-91e9-6eb6ed8faf66.gif  width="48" height="48"> <h3>Analysis</h3>
   
    
    o Based on various factors like MAX. DISCOUNT offered by a BRAND, AVERAGE Discount offered, Most popular Brand,
      gave a strong insight of the BRAND'S MARKET STANDING.

    o Designed the KPIs to measure the performance of medicines on portal and thus concluded the business opportunities for store.
 
    o Analysed the correlation between types of medicines' ingredients and its affects on various body parts. 

    o Analyzed the popularity of medicines on portal by focusing on the reviews and star-rating.

    o Analyzed the top 10 most used ingredients in homeopathy medicines for better understanding.

    o Analyzed the behaviour/price trends of the medicines in order to understand the market needs in order to make a 
      homeopathy store.
 <br>
 <br>
 
<img src="https://www.getcloudapp.com/wp-content/uploads/2021/03/5aebb952e4867ce13f4d308f_laptop_gif_trans.gif" width="70" height="48"/> 
<h3>Insights</h3>
<br>

*1. Most Popular Brand based on average discount price offerrings :*

<p align = "left"><img src="https://github.com/PraveenSharma95/A-Web-Scraping-Project/blob/main/Raw%20files/Inisght%20_%20avg%20discounted%20price%20by%20brands.JPG" width="400" height="200"/>
<br>
<br>

*2. Most Popular Brand based on maximum discount offered on portal :*

<p align = "left"><img src="https://github.com/PraveenSharma95/A-Web-Scraping-Project/blob/main/Raw%20files/Inisght%20_%20Max%20discount%20offered%20by%20Brand.JPG" width="400" height="200"/>

<br>
<br>

*3. Most Popular Brand based on total number of medicines offered on portal :*

<p align = "left"><img src="https://github.com/PraveenSharma95/A-Web-Scraping-Project/blob/main/Raw%20files/Total%20no.%20of%20medicines%20listed%20on%20portal%20by%20brands.JPG" width="400" height="200"/>

<br>
<br>

*4. Top 10 ingredients used in medicines :*

<p align = "left"><img src="https://github.com/PraveenSharma95/A-Web-Scraping-Project/blob/main/Raw%20files/insight%20_%20top%2010%20ingredients%20used%20in%20medicines.JPG" width="400" height="200"/>

<br>
<br>

*5. Medicines with star-rating above 4/5 :*

<p align = "left"><img src="https://github.com/PraveenSharma95/A-Web-Scraping-Project/blob/main/Raw%20files/insight_%20customer%20Review%20%20(star%20ratings).JPG" />

<br>
<br>

*6. Price trends of medicines focusing on eyes, joints, skin, hair :*

<img src="https://github.com/PraveenSharma95/A-Web-Scraping-Project/blob/main/Raw%20files/inisght%20_%20price%20trends%20for%20skin%20medicines.JPG" width="400" height="200"/>
<br>
<img src="https://github.com/PraveenSharma95/A-Web-Scraping-Project/blob/main/Raw%20files/insight%20_%20price%20trend%20for%20joint%20medicine.JPG" width="400" height="200"/>
<br>
<img src="https://github.com/PraveenSharma95/A-Web-Scraping-Project/blob/main/Raw%20files/Insight_price%20trends%20for%20Eyes%20medicines.JPG" width="400" height="200"/>
<br>
<img src="https://github.com/PraveenSharma95/A-Web-Scraping-Project/blob/main/Raw%20files/price%20trend%20for%20hair%20medicine.JPG" width="400" height="200"/>
<br>
<br>
<img src="https://user-images.githubusercontent.com/108053296/185756908-fbb62168-d923-48f2-992f-b8e2fde848fe.gif" width="100" height="100" > <h4> Conclusion </h4>
   
<br>
<br>
<img src="https://github.com/PraveenSharma95/A-Web-Scraping-Project/blob/main/Raw%20files/conclusion_1mg.JPG">
