
# Project: Web, Mobile & Database Agency in React

Web App & Single site.

Topic : Intelligent Web App Software and Mobile App Agency that will help companies to growth their businees and support social enviromental resposability projects by investing money from our earnings in green companies, organic farms and education with a consciousness prospective.

## Goal & Technologies

**Front end** : Javascript, HTML and CSS, Tailwind.
**Framework** :React.
**Backend** : Mongo Db, Node.js & Express.js.

## Features

### 1. Dashboard (Main Page)

The dashboard shows an overview of the all services offered by the Agency.
- Left: Logo 
- Center : Agency's name and a brief introduction
- Right: Google Map with markers at the positions of the blog posts

![Dashboard](/img/1.jpg)

### 2. Menu Bar
- Menu bar : logo (of your choice) , headline , about us ,services , projects, Software Development Training programm,Blog, Contact us .
- Contact area , provide a detailed form where company's and future employees can can contact us for acquiring our services or for being part of our team.
- In the menu provide a login button (text + icon) on the right side.(for company's employees).

> **Icon Resources:**  [FontAwesome](https://fontawesome.com/).

![Menu Bar](/img/2.jpg)


#### About section 


#### Services section 



#### Project section 


#### Software Trainings Section


#### Blog Post web section 

- It contains:
  - title
  - visiting date
  - authors image and name (can be hardcoded)
  - image
  - text  
  - When user clicks on one of the listed blog post, the person gets linked to the service`s page `/post/:id` for acquiring the company's services.  
  -Talks about Topics like the lastest technology in IT and also about social, enviromental programs and solutions for a better planet.
  - Talks about software development trainings in order to attract future employees with no experience.
 
![Map marker](/img/3.jpg)


![Blog Post Detail](/img/blog-post.jpg)

### Imprint / Contact Section

- Create a link `/contact` in the menu bar named "Contact".
- On the contact page place your (and your team mate's).
- Write two sentences about your project.
- Contact details:
  - name
  - address
  - email
  - phone number

### 8. World Map with Google Maps API

- Use the [google-map-react](https://github.com/google-map-react/google-map-react) library to display a world map. for each office location, put a marker on the map at the location of the post.

## Bonus Tasks

### Bonus 2: Get Blog Posts from Backend ( can we do something where I can use these tools but not for a blog ?)

- Create a seperate Node.JS, MongoDB application to handle the BackEnd
- Serve your Blog Posts thourgh a REST Api with JSON.

### Bonus 3:

- With the path `/new` a blog post form is shown, where a new blog post can be added.
- On submit, the new blog post is sent and stored to the backend.
- The form is cleared after adding a new blog post and the user gets directed to the Dashboard, again.  


### Bonus 5. Authentication / Login
- Add authentication to your BackEnd App
- If the login button is clicked, a login form is shown right below the login button under the menu bar.
- The User can login with their email and password.
- If successfully logged in, the login form disappears and instead of the login button a logout button is shown.
- If logged in, there should be another button  that will take employees to a new place ( time scheduler site ) on the left of the logout button. 

### Bonus 6: Provide a user profile page

- Add a link in the menu bar, where the signed-in user( employee)  can edit their profile.
- At the profile page, the signed-in user can upload a profile image and save their name.
- Use this information, if available,
  - in the menu to show logged in users name and image.



-----------------------------------------------------


## Submission

1. Upload your code to a new GitHub repository.
  - If you placed your API keys directly into your code, remember to remove your API keys.

    **Hint:**
    There is a way to use keys in the React project without the risk to push those to a repository accidentally:
      - Add a file `.env` into your project root folder. It is ignored by git.
      - In this file you can define custom environment variables like that: `REACT_APP_MY_API_KEY=MyKey-12345`
      - Within your component you can use it with `{process.env.REACT_APP_MY_API_KEY}`
      - After every change in this files you have to restart your project.

      For more information check out: https://create-react-app.dev/docs/adding-custom-environment-variables/.

  - If you worked in a team, link the GitHub accounts of both of you in the README.md.

2. Send us an email with the following information:
  - A link to your GitHub repository
  - A link to your GitHub repository for the BackEnd app if implemented  
  
