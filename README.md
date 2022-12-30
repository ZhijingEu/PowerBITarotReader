# PowerBITarotReader
This is the Github Repo for all the files/source documents used to develop a simple Tarot Reading app implemented in Power BI 

Tarot Reading is a fortune telling technique that uses cards to gain insight into the past, present or future. Practitioners of tarot typically formulate a question, then draw cards under a certain set of layouts and make interpretations of the selected cards.

About This App
===============
This PowerBI report uses a bunch of Power Query scripts, Power Automate flows and some custom HTML visuals to generate tarot readings.
More details here : https://youtu.be/rH5098J5fhw

About The Files In This Repo
============================
Tarot.pbix - the Power BI file with the report/dashboard
Tarot_Project.xlsx - the source file for the said Power BI Report
Extract_Card_Interpretations.ipynb - the Python Notebook used to webscrape the card meanings from www.BiddyTarot.com 
Invert_Images.ipynb - the Python Notebook used to rotate the publicly available images from wikimedia by 180 degree to reflect the inverted tarot card readings
All Inverted Images were stored in this GitHub repo to be easily referenced as web image urls by the PowerBI 
