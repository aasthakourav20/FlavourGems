# FlavourGems

## Table of Contents

- [FlavourGems](#FlavourGems)
- [Tech Stack Used](#Tech-Stack-Used)
- [Features](#Features)
- [Setup the project](#Setup-the-project)



## Flavour Gems 
FlavourGems goes beyond being just a food store website, it's a culinary haven where affordability meets authenticity. Our carefully curated selection of recipes ensures that you can embark on a gastronomic journey without breaking the bank. Every dish is a blend of top-quality, genuine ingredients, promising a delightful and wholesome cooking experience. But we don't stop at recipes – step into our physical restaurant, and you'll find yourself enveloped in a cozy ambiance that perfectly complements the flavors on your plate. Our dedicated staff ensures that your dining experience is nothing short of exceptional, leaving you with cherished memories of flavor and comfort. At Food Recipe, we believe that good food should be accessible, memorable, and above all, a true celebration of the culinary arts.

 
# Tech Stack 💻

<div align="center">

![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) &nbsp;&nbsp;&nbsp;
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) &nbsp;&nbsp;&nbsp;
![Bootstrap](https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white) &nbsp;&nbsp;&nbsp;
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) &nbsp;&nbsp;&nbsp;
![Azure](https://img.shields.io/badge/microsoft%20azure-%230072C6.svg?style=for-the-badge&logo=microsoftazure&logoColor=white) &nbsp;&nbsp;&nbsp;

</div>


## Features
- Daily Special Offers Updates.
- Online Ordering.
- Recipe Collection.
- Genuine Product Assurance.
- Visual Gallery.
- Customization.
- Interactive Customer Support.
- Social Media Integration.
- Nutritional Information.


### Setup the project

1.Fork the Repo: Fork the Food Recipe repository to your GitHub account by clicking the "Fork" button in the top right of this page.

2.Clone the Repo: Clone the forked repository to your local machine using the following command:

```shell
git clone https://github.com/<your-username>/FlavourGems.git
```
Note: Replace your-username with your actual GitHub username.

3.Change the Present Working Directory: Navigate to the cloned repository using the following command:

```shell
cd FlavourGems
```
4.Create a New Branch: Create a new branch in your forked repository to work on your changes:

```shell
git checkout -b branch-name
```


### Getting started
The following environment variable are necessary for configuring the project in your local -

1. Azure
Step 1: Create an Azure account
You must have an azure storage account for the project.
Images are stored as a blob in azure. So we need to have a blob container which we would access through our access keys
If you are a student then you can sign up for a $100 free credit on azure here.

2. Creating a new Resource
3. Fill the form 
A form is displayed. You only need to fill in the type of subscription and the name of storage account.
Leave rest to default. Then go to the resource and search for access keys.

4. Choose connnection string
   After clicking the access keys, we can see our storage account name and connection string (there are two of them, choose anyone)

5.  Setting up container
    As a last step in the resource page, you have to set up the container where we would store the images.
    In your newly created storage acc dashboard, click on the blob storag
    You must see a page where you can create a new container. Remember this name as we need it
    Environment variables to configure azure storage:

