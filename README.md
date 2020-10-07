# Hyperlinks, Images, Tables and Forms
## Hyperlinks and Images
1.
    * Download [great-britain.txt](great-britain.txt). This file contains some information about the the countries that make up Great Britain.
    * Using this content, create a **separate** web page for each country.
        - Use the html template (https://github.com/CFT2111/Intro-to-HTML/blob/master/template.html) as your starting point and then copy in content from the *great-britain.txt* file.
        - Mark-up the content e.g. make the name of the country a *h1* element, add a title, create a list for the capital, population and area facts.
        - Validate each of the web pages using the w3c validator, http://validator.w3.org/ and fix any errors.

2.
    * Link the different pages together using the anchor element *a*.

3.
    * Insert an image of the country’s flag into each page.
        * Have a look the web to find images which are licensed for re-use (Wikipedia is often a good starting point).
        * If needed, make sure you also add appropriate attributions.

4.
    * Add some CSS to the website.
        * Create a single CSS file and link it to each of the HTML pages.
        * Change basic properties such as the fonts and colours for the pages.

5.
    * Experiment with hyperlink and image related CSS properties e.g
        * Pseudo-classes for hyperlinks
        * Styling images using CSS

## Tables
1. Create an HTML table that will display the following data.

**Population of Countries in Great Britain**

 |  Country |  Capital City |  Population |
 |----------|---------------|-------------|
 |  England |  London |  54,786,300 |  
 |  Scotland |  Edinburgh |  5,404,700 |  
 |  Wales |  Cardiff |  3,063,456 |    

* Validate the page.
* Add some CSS to this file so that the table cells and table header are coloured.
* England has the highest population. Using CSS can you find a way of colouring the England row in a different colour to the other rows of the table (hint: think about using the class selector)?

## Forms
* Download file [carboot.html](carboot.html). *carboot.html* is a registration questionnaire for a fictional e-commerce Web Site.
* Using this as a basis, create a web page that structures this information as an HTML form.
* You will see that some of the questions have various options as answers, others do not. Using your knowledge of HTML select which form elements are appropriate for each question and generate a complete form.
    * Try to use a range of elements
    * Make sure you validate the page.
* Add some CSS to style the form elements. Here is some advice:
    * You may need to put each pair of label and input elements inside *div* tags.
    * You may need to change the *display* property for the form controls to move them onto separate lines.
    * You may need to use the attribute selector in CSS to style specific types of form element e.g. radio buttons?
