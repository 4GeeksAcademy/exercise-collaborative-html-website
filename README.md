# Making a website as a team (Git collaboration)

Practice your skills in Git while developing a typical website.

Each student works on a different file, for a different part of the website, and the most senior can work as Team Leader (for integration and deployment), unless the teacher prefers to be the team leader of the whole class. The Html-Template-Engine library will take care of putting all the pieces together.

## 📝 Instructions

1. The Team Leader should fork this repository on github.com and [invite other collaborators to the repo](https://github.com/breatheco-de/exercise-git-collaboration/blob/master/iOBmU5zYqA.gif). Give access to the other team members on the newly forked GitHub repository, and make sure they are cloning from this new repository, not the original!

2. We are going to be building [this design](https://raw.githubusercontent.com/breatheco-de/exercise-collaborative-html-website/master/website/designs/thumb.jpg), and [this is how you can split it with the students](https://github.com/breatheco-de/exercise-collaborative-html-website/blob/master/website/designs/guide.jpg?raw=true).

3. Each contributor will have to clone the new forked repository and develop a part of the website that is coordinated with the group; each project is divided into pieces inside the `website/templates/` directory. Once everyone has their editor open, run the project in the terminal with this command:

```bash
$ npx http-server --yes -c-1
You will be given an option to open in the browser and have options to view the new site, what it should look like, and a reference to each part of the page. If you receive an error, wait a moment and refresh.
To start, each member should put their name in the file they have been assigned, push back to the repository, and pull to see the others' changes. Maintaining clear communication about the files being used will make the project run smoothly 🙂

Once everyone understands how to modify their part of the project and push, use the search feature and examples within https://getbootstrap.com/ to quickly build using Bootstrap components, then modify accordingly.

🌱 How to start this project
If you are a student:

Wait for your instructor to advise you on how to start the project!

If you are an instructor or team leader:

This project comes with the necessary files to start working, which can be found in the following GitHub repository:

text
Copy code
https://github.com/breatheco-de/exercise-collaborative-html-website
a) Navigate to and fork the repository on GitHub.

b) Invite your students or team members as collaborators to your forked repository (see the gif manual in it).

c) Have your students or team members clone your forked repository (not the original above).

Both students and instructors:

To load and watch the website live, run the following command:

bash
Copy code
$ npx http-server --yes -c-1
Deploy the website
Use Vercel, Netlify, or GitHub pages to deploy the website and get a URL where anyone can see the results (for example: https://mysuperteam.zeit.sh).

Delivery
Each student must deliver their team's leader repo as a solution.

Complementary info
The Html-Template-Engine library is being used as the template engine for building the landing page.

This and many other projects are built by students as part of the 4Geeks Academy Coding Bootcamp by Alejandro Sanchez and many other contributors. Find out more about our Full Stack Developer Course and Data Science Bootcamp.

