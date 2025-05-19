# alu_regex-data-extraction-Laurakarangwa
This repository was created for my formative assignment on Regular Expressions (Regex).

## Regex Data Extraction Web App

This project is a simple **web application** that extracts specific data types from a large text using the Regular Expressions (Regex). It was developed as part of a regex data extraction assignment using Python or JavaScript, but I prefer to use JavaScript with the help of HTML, and CSS. It will be extracting 6 out of the 8 possible data extractions given.

## Features

The application can detect and extract the following types of data:

-  Email addresses  
-  URLs  
-  Phone numbers (various formats)  
-  Credit card numbers
-  Time (12/24hr)
-  HTML tags  

## Technologies Used

- **HTML** – Structure of the web page  
- **CSS** – Styling and layout  
- **JavaScript (Regex)** – Data extraction logic  


##  How to Use

**1.Clone the repository**  
   Open your terminal and run:  
   git clone https://github.com/your-username/alu_regex-data-extraction-Laurakarangwa.git
   
**2.Navigate into the project directory**
cd alu_regex-data-extraction-Laurakarangwa

**3.Open the application in your browser**
You can simply double-click the HTML file, then:

  >Copy any large text or page content into the text area

  >Click the Extract Data button

  >View the extracted results below, categorized by data type

## Sample input and test cases

Sample input:

Contact me at user@example.com or call (123) 456-7890. Visit https://example.com for details.

Expected Output to be extracted:

- Emails: user@example.com  
- Phone Numbers: (123) 456-7890  
- URLs: https://example.com  

In the assignment I had, this was the input:

Email addresses:
user@example.com
firstname.lastname@company.co.uk
URLs:
https://www.example.comLinks to an external site.
https://subdomain.example.org/pageLinks to an external site.
Phone numbers (various formats):
(123) 456-7890
123-456-7890
123.456.7890
Credit card numbers:
1234 5678 9012 3456
1234-5678-9012-3456
Time:
14:30 (24-hour format)
2:30 PM (12-hour format)
HTML tags:
<p>
<div class="example">
<img src="image.jpg" alt="description">
Hashtags:
#example
#ThisIsAHashtag
Currency amounts:
$19.99
$1,234.56

and the output was

Email Addresses
user@example.com
firstname.lastname@company.co.uk
URLs
https://www.example.comLinks
https://subdomain.example.org/pageLinks
Phone Numbers
(123) 456-7890
123-456-7890
123.456.7890
Credit Card Numbers
1234 5678 9012 3456
1234-5678-9012-3456
Time (12/24hr)
14:30
2:30 PM
HTML Tags
<p>
<div class="example">
<img src="image.jpg" alt="description">

This is because I have chosen to extract 6 data types out of 8 given.

##  Author

**Laurakarangwa**




