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
  - # Write your first Markdown blog post - https://docs.astro.build/en/tutorial/2-pages/2/
    > create file: posts/post-1.md, post-2, post-3
  - # Resourses:
  - https://www.markdownguide.org/cheat-sheet/
  - https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Tools_and_setup/What_are_browser_developer_tools
  - https://assemble.io/docs/YAML-front-matter.html
  - # Add dynamic content about you - https://docs.astro.build/en/tutorial/2-pages/3/
  - Define and use a variable
  - Write JavaScript expressions in Astro
  - Conditionally render elements
  - Analyze the Pattern
  - # Resourses:
  - https://docs.astro.build/en/core-concepts/astro-syntax/#jsx-like-expressions
  - # Style your About page - https://docs.astro.build/en/tutorial/2-pages/4/
  - Using Astro’s own <style></style> tags
  - # Resourses:
  - https://docs.astro.build/en/core-concepts/astro-syntax/#differences-between-astro-and-jsx
  - https://docs.astro.build/en/guides/styling/#styling-in-astro
  - https://docs.astro.build/en/guides/styling/#css-variables
  - # Add site⁠-⁠wide styling - https://docs.astro.build/en/tutorial/2-pages/5/
  - Add a global stylesheet
    - create file: src/styles/global.css
  - # Check in: Unit 3 ⁠-⁠ Components - https://docs.astro.build/en/tutorial/3-components/
  - # Build:
  - A Navigation component that presents a menu of links to your pages
  - A Footer component to include at the bottom of each page
  - A Social Media component, used in the Footer, that links to profile pages
  - An interactive Hamburger component to toggle the Navigation on mobile
  - # Make a reusable Navigation component - https://docs.astro.build/en/tutorial/3-components/1/
  - Create a new src/components/ folder
  - Create a new file: src/components/Navigation.astro.
  - # Resourses:
  - https://docs.astro.build/en/core-concepts/astro-components/#component-structure
  - https://refactoring.com/
  - # Create a social media footer - https://docs.astro.build/en/tutorial/3-components/2/
  - Create src/components/Footer.astro.
  - Create a Social Media component: src/components/Social.astro
  - Import and use Social.astro in Footer
  - # Resourses:
  - https://docs.astro.build/en/core-concepts/astro-components/#component-props
  - # Build it yourself ⁠-⁠ Header - https://docs.astro.build/en/tutorial/3-components/3/
  - Add responsive styles
  - # Resourses:
  - https://www.droptica.com/blog/component-based-design/
  - https://www.dofactory.com/html/semantics
  - https://www.mobileapps.com/blog/mobile-first-design
  - # Send your first script to the browser - https://docs.astro.build/en/tutorial/3-components/4/
  - Build a Hamburger component - src/components/Hamburger.astro
  - Write your first script tag
  - Importing a .js file - Create src/scripts/menu.js
  - # Resourses:
  - https://docs.astro.build/en/guides/client-side-scripts/
  - # Using <script> in Astro - https://docs.astro.build/en/guides/client-side-scripts/
  - # Check in: Unit 4 ⁠-⁠ Layouts - https://docs.astro.build/en/tutorial/4-layouts/
  - In this unit, you’ll build layouts to share common elements and styles across your pages and blog posts.
    - Create reusable layout components
    - Pass content to your layouts with <slot />
    - Pass data from Markdown frontmatter to your layouts
    - Nest multiple layouts
  - Create your first layout component - src/layouts/BaseLayout.astro
  - Use your layout on a page - The <slot /> allows you to inject (or “slot in”) child content written between opening and closing <Component></Component> tags to any Component.astro file.
  - Pass page-specific values as props
  - # Resourses:
  - https://docs.astro.build/en/core-concepts/layouts/
  - https://docs.astro.build/en/core-concepts/astro-components/#slots
  - # Create and pass data to a custom blog layout - https://docs.astro.build/en/tutorial/4-layouts/2/
  - Now that you have a layout for your pages, let’s add a layout for blog posts!
    - Create a new blog post layout for your Markdown files
    - Pass YAML frontmatter values as props to layout component
  - Add a layout to your blog posts
  - When you include the layout frontmatter property in an .md file, all of your frontmatter YAML values are available to the layout file.
  - create src/layouts/MarkdownPostLayout.astro
  - # Resourses:
  - https://docs.astro.build/en/guides/markdown-content/#frontmatter-layout
  - https://docs.astro.build/en/core-concepts/layouts/#markdown-layout-props
  - https://dev.to/paulasantamaria/introduction-to-yaml-125f
  - # Combine layouts to get the best of both worlds - https://docs.astro.build/en/tutorial/4-layouts/3/
  - Nest your two layouts - Nest your blog post layout inside your main page layout
  - # Resourses:
  - https://docs.astro.build/en/core-concepts/layouts/#nesting-layouts
  - # Migrate an existing project to Astro - https://docs.astro.build/en/guides/migrate-to-astro/
  - # Use a CMS with Astro - https://docs.astro.build/en/guides/cms/
  - # Use a backend service with Astro - https://docs.astro.build/en/guides/backend/
  - # Add Integrations - https://docs.astro.build/en/guides/integrations-guide/
  - Astro includes an astro add command to automate the setup of integrations.
  - Astro integrations are always added through the integrations property in your astro.config.mjs file.
  - # Deploy your Astro Site - https://docs.astro.build/en/guides/deploy/
  - # More Recipes - https://docs.astro.build/en/recipes/
  - ...
