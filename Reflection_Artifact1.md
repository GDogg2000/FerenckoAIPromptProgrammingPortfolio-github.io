# Artifact 1 Reflection

## Initial Set-Up:

**Prompt:**  Asked Google how to create a simple programming portfolio website in Github pages.

**Result:**  
To create a simple, free website using GitHub Pages, you need to create a public repository named username.github.io and add an index.html file. [1] (https://docs.github.com/pages/quickstart), [2] (https://github.com/orgs/community/discussions/160361)
You can complete this process entirely within your web browser in just a few minutes by following the steps below.
Step 1: Create a New Repository
1. Log into your account on GitHub.
2. In the upper-right corner of the page, click the + dropdown menu and select New repository. [1] (https://docs.github.com/articles/creating-project-pages-manually)
3. Under Repository name, type exactly: yourusername.github.io (Replace yourusername with your actual GitHub username in lowercase). [1] (https://docs.github.com/articles/creating-project-pages-manually), [2] (https://docs.github.com/pages/quickstart)
4. Set the visibility to Public. [1] (https://www.youtube.com/watch?v=ZwG9jwit2Ho&t=40)
5. Check the box to Add a README file. [1] (https://docs.github.com/articles/creating-project-pages-manually)
6. Click Create repository. [1] (https://docs.github.com/articles/creating-project-pages-manually)
Step 2: Create Your Website Homepage
Your site requires a main file to serve as the homepage, which must be named index.html. [1] (https://github.com/orgs/community/discussions/160361)
1. Inside your new repository, click the Add file dropdown and choose Create new file. [1] (https://www.youtube.com/watch?v=Awnsuyq80xY&vl=en&t=52)
2. Name the file index.html. [1] (https://www.youtube.com/watch?v=QyFcl_Fba-k&t=39)
3. In the file editor, paste this basic HTML structure: [1] (https://www.khanacademy.org/computing/computer-programming/html-css/web-development-tools/a/hosting-your-website-on-github), [2] (https://www.youtube.com/watch?v=QyFcl_Fba-k&t=39)
html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My GitHub Pages Website</title>
</head>
<body>
    <h1>Welcome to My Website!</h1>
    <p>This simple site is successfully hosted on GitHub Pages.</p>
</body>
</html>
Use code with caution.
4. Scroll down to the bottom, write a short commit message (e.g., “Create index.html”), and click Commit changes. [1] (https://www.khanacademy.org/computing/computer-programming/html-css/web-development-tools/a/hosting-your-website-on-github)
Step 3: Enable GitHub Pages
1. Near the top of your repository page, click the Settings tab.
2. Look at the left sidebar menu under the "Code, planning, and automation" section and click Pages.
3. Under Build and deployment, find the Source setting and select Deploy from a branch.
4. Under Branch, change the dropdown selection from None to main (or master), leave the folder as /root, and click Save. [1] (https://docs.github.com/pages/quickstart), [2] (https://github.com/orgs/community/discussions/160361)
Step 4: Visit Your Live Site
Give GitHub a minute or two to build and deploy your files. You can track the progress by going to the Actions tab at the top of your repository. [1] (https://www.youtube.com/watch?v=M_x2r36WC4s&t=11), [2] (https://github.com/orgs/community/discussions/160361)
Once complete, open a new browser tab and navigate to:
https://yourusername.github.io [1] (https://www.youtube.com/watch?v=M_x2r36WC4s&t=11)
💡 Tips for Customization
• Adding Styles: You can add custom formatting by creating a style.css file in the same repository and linking it inside your index.html header.
• Updating Content: Any time you commit edits to your files directly on GitHub (or push them from your local computer), GitHub Pages will automatically rebuild and update your live site within a few minutes.
• Deep Dive: If you want to expand your site into a larger blog or portfolio, you can learn more about configuring settings via the Quickstart for GitHub Pages or explore building with Markdown tools like Jekyll on Medium. [1] (https://www.youtube.com/watch?v=dcql0BItibs), [2] (https://medium.com/@gerkElznik/creating-a-personal-website-using-github-pages-9dd04b9ab4b7), [3] (https://docs.github.com/pages/quickstart)

**Reflection:**  I noticed that it wanted me to name my website with my Github username.  Wasn't sure if that was required -- thought that would be problematic if I wanted to create a 2nd page, so I asked the AI if that was required.

**Reprompt:**
Does the repository name need to be my username?  What if I want to create a 2nd website?

**Reply**

No, the repository name does not have to be your username. You only use your username for your primary User site.
To create a second website, you create a Project site by naming the repository whatever you want (e.g., my-portfolio or recipe-blog).
Here is how the two types of sites work and how your URLs will look:
1. User Site (Your 1st Site)
• Repository Name: yourusername.github.io
• Live URL: https://github.io
• Limit: You are strictly limited to one User site per GitHub account.
2. Project Sites (Your 2nd, 3rd, or 50th Site)
• Repository Name: Any custom name you want (e.g., project-two).
• Live URL: https://github.io
• Limit: You can create unlimited Project sites.
How to Set Up Your 2nd Website
1. Create a new public repository with any name you like (e.g., fitness-tracker).
2. Add your index.html file to that repository.
3. Go to the repository's Settings > Pages.
4. Change the deployment branch from None to main and click Save.
5. Your second website will go live at: https://github.io
(Note: If you want completely distinct domain names for your different websites, you can buy unique domains from a registrar and link a separate Custom Domain to each individual repository's GitHub Pages settings page.)
If you want, tell me:
• What kind of website you are building next?
• If you plan to use a custom domain (like .com)?
I can show you how to configure the site settings or adjust your internal file links so your images and styles load correctly on a project site.

**Result:**
I created a Github pages project using the name:  `FerenckoAIPromptProgrammingPortfolio-github.io`

## Creating the Website Using Claude AI

**Prompt:**

**Response:**

**Result:**