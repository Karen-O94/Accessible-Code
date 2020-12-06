# Accessible-Code
Horiseon is a leading marketing agency with the singular aim to assist businesses with developing and implementing the best marketing strategies to attract more clients.

 The aim of this project was to refractor the codebase of the Horiseon webpage. We had to ensure the codebase followed best practices and  the webpage met the accessibility standards to ensure their site was optimised for search engines. 

## First steps: Consolidating CSS and Semantic HTML structure
There were multiple duplicate selectors in CSS which the made code base longer than necessary. I grouped together all the selectors with the same property together using commas
Example:
.benefit-lead, .benefit-brand, .benefit-cost {
    margin-bottom: 32px;
    color: #ffffff;

In HTML, there were multiple div tags that I changed into semantic tags to highlight each section. For example instead of <div class="content">, I used <section class="content"> to clarify the meaning of that div tag. As the aim of the project was to improve the accessibiliy standards of the page, using semantic html tags will make it easier for screen readers to identify the purpose of each element.

There was a broken link for one of the images in the content section as the class was not defined in HTML. Once the class was added, the user was able to click one of the headings in the Header tag and directed to the corresponding text in the content page. 

## Second steps: Including alt attributes and adding comments
Alt attributes were used to describe each image in the event images are unable to load or to aid visually impaired users to understand what image represents

Comments were added to the CSS file to clarify what styles were used to design the page and which selectors belonged to a specific section of the page. This aids other potential developers to easily understand the styling choices at a quick glance

## Challenges
The main challenges I faced with this assignment was debugging issues that I came across as I was committing or pushing my code. It took a lot of self-research and peer discussions to understand where I went wrong and how to resolve the issue. 

## Conclusions 
This first assignment was a great way to implement what we had learnt in class and the prework. However, I was also presented with new challenges which required me to seek external help from fellow peers, Google, W3Schools, youtube etc. to complete this assignment to the best of my ability. 

## Built with:
* HTML
* CSS

![code-image] (Acessible-Code.png)

## Credits 
To all the lovely TAs and students of the FSF Coding bootcamp. 