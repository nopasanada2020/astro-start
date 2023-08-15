#### \_Building a Blog.md

- ## ped - Use Astro doc to build/learn a blog
- ## ped - Used following YT Video as a guide:
  - [**Getting Started with the Astro Framework - Building a Blog 03/2023 1:02:03**](https://www.youtube.com/watch?v=v7ovCJ_oizI)
  - Learn all the essential steps for setting up a powerful and engaging blog with the Astro Framework. From creating custom content and integrating social media to maximizing your reach with SEO, you'll be armed with everything you need to get started. This tutorial is perfect for any blogger looking for an easy and efficient way to build their dream blog.
    Software & Applications Used in this Video:
    🔗Astro Blog Guide: https://docs.astro.build/en/tutorial/0-introduction/
    🔗GitHub: https://github.com/
    🔗 Netlify: https://netlify.com/
- # PED Notes:
  > goto > https://astro.build/
  > Get Started > https://docs.astro.build/en/getting-started/
  > -> Why use Astro > https://docs.astro.build/en/concepts/why-astro/
- ***
  > Get Started > Tutorials > Build a blog > https://docs.astro.build/en/tutorial/0-introduction/
- # Steps
  - Set up your development environment
  - Create pages and blog posts for your website
  - Build with Astro components
  - Query and work with local files
  - Add interactivity to your site
  - Deploy your site to the web
- # StackBlitz example: https://stackblitz.com/github/withastro/blog-tutorial-demo/tree/complete?file=src%2Fpages%2Findex.astro
- # https://astro.new - pre-built Astro sites > https://astro.new/latest/
- # Get needed Dev Tools ...
- Terminal command line
  -> VS Code > cntl + ` > open close terminal
- Node.js > node -v
- code Editor > VS Code
- # >>>>>>> Create 1st Astro Project - https://docs.astro.build/en/tutorial/1-setup/2/
  -> # create a new project with npm
  > cd C:\Users\Pablo\Desktop\astro-start
  > npm create astro@latest .... ./
  > use Empty template, no typescript, yes git
  > cd astro-blog
  > npm dun dev > http://127.0.0.1:3000/
- # Open Astro project
  -> stop the dev server at any time and return to the command prompt by typing Ctrl + C in the terminal.
  -> help: https://astro.build/chat
  -> clear > clear terminal ...
- # Write your first line of Astro - https://docs.astro.build/en/tutorial/1-setup/3/
- src/pages/index.astro
- # Store your repository online - https://docs.astro.build/en/tutorial/1-setup/4/
- https://github.com/ ped/gitgitgit2020
- - > create new respository > astro-start
- url > https://github.com/nopasanada2020/astro-start.git
- SCM control pallet > shft + cntl + p
  ped ex: create branch
- commit local code to GitHub
  - ped - I prefer to you the command line?
  - ped - Resources: https://code.visualstudio.com/docs/sourcecontrol/overview#_git-support
- # Deploy your site to the web - https://docs.astro.build/en/tutorial/1-setup/5/
- https://app.netlify.com
- login with email not github
- Sites > Add new site > import an existing prj > deploy ...
- https://dapper-axolotl-9ecd3a.netlify.app/
- Site config > Site info > change site name: https://astro-startt.netlify.app/
- # Check in - Unit 2 - Pages - https://docs.astro.build/en/tutorial/2-pages/
- # In this unit:
  - Create your first Astro pages with the .astro syntax
  - Add blog posts with Markdown (.md) files
  - Style an individual page with <style>
  - Apply global styles across pages
- # Create your first Astro page - https://docs.astro.build/en/tutorial/2-pages/1/
  > Create src/pages/about.astro - http://localhost:3000/about
  > Create src/pages/blog.astro - http://localhost:3000/blog
  > Add navigation links to /index & /about
  > 🎫 Unlike many frameworks, Astro uses standard HTML <a> elements to navigate between pages (also called routes), with traditional page refreshes.
  > Commit changes to github & Netlify - need to wait a few minutes
  - # Resources:
  - https://docs.astro.build/en/core-concepts/astro-pages/#file-based-routing
  - https://docs.astro.build/en/core-concepts/astro-pages/#astro-pages
