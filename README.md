
# Company_classification


Problem Statement : We are given with web scraped data of various businesses and companies. We need to somehow categorize these businesses and companies across a standard taxonomy (consists of term names and labels that are specific to an organization's information and unique to how that business operates). So that, business can leverage this information and target potential companies.

# Overview of DATASET

Website: The website of the company/business

Company Name: The company/business name

Homepage Text : Visible homepage text

H1: The heading 1 tags from the html of the home page

H2: The heading 2 tags from the html of the home page

H3: The heading 3 tags from the html of the home page

Navlink text: The visible titles of navigation links on the homepage (Ex: Home, Services, Product, About Us, Contact Us)

Meta keywords: The meta keywords in the header of the page html for SEO

Meta description: The meta description in the header of the page html for SEO

We used Kmeans clusternig on the sparse matrix that we got after TF-IDF vectorization to create word clouds that can tell which company it belongs to as an example we have our Healthcare sector as:


![118387620-ffc00780-b63c-11eb-884f-534657116ced](https://user-images.githubusercontent.com/73156397/120102969-0d13e080-c16b-11eb-8abc-42cf78c917a7.PNG)
