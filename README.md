# Pharmacy
Pharmacy Shop Website Development Project
Problem Statement
A pharmacy shop with millions of customers needs a website to manage their products and streamline their offline order processing. Additionally, the pharmacy collaborates with various diagnostic centers to offer lab test services, including sample collection at patients' doorsteps, lab analysis, and report delivery via email or hard copy. Your organization has taken up the project to develop a homepage for the products and a lab test form.

Requirements
Homepage
Header and Footer:

Create a header with the text "Pharmacy" and a footer with the text "@copyright. Only for demonstration purposes".
Align both the header and footer to the center of the screen.
Horizontal Navigation Bar:

Place the navigation bar below the header with the following links:
Home
Our Medicines
Dropdown links: Fever, Muscle Pains, Cold & Cough
Health Care
Dropdown links: Baby Care, Skin Care, Home Care, Personal Care, Pet Care
Lab Test
Clicking on this opens a form to book a slot.
Ensure the background color of the links changes on hover.
Make the navigation bar sticky so it remains visible at the top of the page when scrolling.
Image Animation:

Display promotional images at the top of the page.
Use provided images to create a simple animation that cycles through the images infinitely.
Apply a border of 2px solid steelblue.
Product Sections:

Create two product sections: Covid Care and Diabetes Care.
Each section should display products with the following details:
Product name
Image
Price
Price after offer
Add to Cart button
On click, change the button background color to rgb(250, 234, 230) and the border to rgb(0, 255, 76).
On hover, slightly increase the product's width and height.
Lab Test Form
Form Details:

Patient Contact Details:
Full Name
Patient Id (if exists)
Contact Number
Email Id
Address:
House Number
Street
Area
District (dropdown list with the first option as "Choose")
Test Type (with a validation message "Check at least one box without fail"):
CBC
Complete Urine
Lipid Profile
Thyroid Stimulating Hormone (TSH)
Glucose Test
Report Delivery Preference:
Yes
No
Comfortable Date and Time:
Date
Time
Reset and Submit buttons
Form Appearance:

Include an image on the right side of the form that remains fixed when scrolling.
Ensure the form layout matches the provided design.
General Instructions
Ensure the webpage and form are responsive and adapt to browser resizing.
Provide appropriate padding, margins, page titles, and page names.
Write all CSS code in a separate .css file.
Upload all files, including images, ensuring they are well-organized.
Name the files appropriately.
Do not upload zip/compressed files.
Ensure all links/URLs are correct and relative to the project structure for GitHub, avoiding local machine references.
Project File Structure
lua
Copy code
/pharmacy-website
|-- /images
|   |-- image1.jpg
|   |-- image2.jpg
|   |-- ...
|-- /css
|   |-- styles.css
|-- index.html
|-- labtest.html
|-- README.md
index.html
This file contains the structure for the homepage, including the header, footer, navigation bar, image animation, and product sections.

labtest.html
This file contains the structure for the lab test booking form.

styles.css
This file contains all the CSS code for styling the homepage and the lab test form.

README.md
This file provides an overview of the project requirements and guidelines for development.

Ensure to follow the specifications closely to meet the client's needs and deliver a high-quality product.





