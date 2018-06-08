## The repository for the Nonlinear Dynamics Laboratory website ##
---
The website is currently hosted at: https://nld-iiserk-sb.github.io/

It was created using [Jekyll](https://jekyllrb.com/) and [GitHub pages](https://pages.github.com/).
___
### Website pages ###

1. Home
2. Research
3. People - Group Leader, Masters, PhDs, Post-docs, Alumni
4. Teaching and Outreach
5. Contact Us
___
### How to make changes to content ###

Ideally, you should not have to touch any file except for those in the _data folder. 
To change the relevant content, navigate to the folder _data, open the relevant file, make changes and commit. You **do not** need
to write any code for this.
The change should appear on the website within 10 miniutes. 
While adding an item to any of the .yml files, please make sure to stick to the format used for the other items (*including spaces 
newline characters!*).

Refer to the **Directory structure and files** section for information on content.
___
### Directory structure and files ###

- _data: Contains data files for all pages
  - articles.yml : List of journal articles for the Research page
  - books.yml : List of books for the Research page
  - news.yml : News items for 'Latest News' link on Home page
  - outreach.yml : List of outreach activities for Teaching and Outreach page
  - people_categories.yml : List of categories for people page (leader,masters,phds,etc.)
  - people.yml : Information about all lab members sorted by category
  - projects.yml : List of ongoing lab projects for Research page
  - teaching.yml : List of courses taught for Teaching and Outreach page
  
- _includes : Contains html templates for different elements of the webpage
- _layouts : Contains layouts for the webpages
  - default.html : html and Jekyll code for default layout of all webpages
- css : Contains the css files for the webpages
- fonts : Contains font information for the css files
- images : Contains all images used on the website
  - people_img : Contains profile photos of lab members for People page
- js : Contains javascript files for the website
- people_pdfs : Contains files with CV/extra information of lab members for the People page.
- _config.yml : Contains basic information about website
- index.md : html and Jekyll code for Home page
- research.md : html and Jekyll code for Research page
- leader.md,masters.md,phds.md,postdocs.md,alumni.md : html and Jekyll code for People page
- teach.md : html and Jekyll code for Teaching and Outreach page
- contact.md : html and Jekyll code for Contact Us page
- 404.html : html code and Jekyll code for Page not Found page.
- Gemfile,Gemfile.lock : Jekyll build files






