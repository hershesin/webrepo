
<h1><b>GitHub Actions Website Deployment</b></h1>

This project demonstrates how to create a website and deploy it automatically to GitHub Pages using GitHub Actions.
<h2><b>1. Create the Project Files</b></h2>

Start by creating the required files for your website in your local folder:
<ul>
  <li>index.html</li>
  <li>style.css</li>
  <li>script.js</li>
</ul>
<b> Structure </b>
my-website/
│
├── index.html
├── style.css
├── script.js
└── .github/
    └── workflows/
        └── deploy.yml

<h2><b>2. Initialize Git and Push to GitHub</b></h2>
<ul>
<li>Initialized a local Git repository.</li>
<li>Committed the project files.</li>
<li>Created a new repository on GitHub.</li>
<li>Pushed the local project to the remote repository.</li>
</ul>

<h2><b> 3. Enable GitHub Pages</b></h2>
<ul>
<li>Went to the repository settings on GitHub.</li>
<li>Enabled GitHub Pages and selected the branch to deploy from (usually main or gh-pages).</li>
<li>Verified that a static deployment works.</li>
</ul>

<h2><b>4. Create a GitHub Actions Workflow</b></h2>
<ul>
<li>Added a workflow file inside the .github/workflows/ directory.</li>
<li>Configured it to automatically build and deploy the project to GitHub Pages whenever code is pushed to the repository.</li>
<li>Ensured the workflow successfully runs after every update.</li>
</ul>

<h2><b>5. Deploy and Verify</b></h2>
<ul>
<li>Made changes to the code and pushed updates.</li>
<li>Checked the Actions tab to confirm the workflow ran successfully.</li>
<li>Opened the live GitHub Pages link to verify that the website was updated.</li>
</ul>

<h2><b>6. Outcome</b></h2>
<ul>
<li>The website is now automatically deployed with every commit.</li>
<li>No manual deployment steps are required — the workflow handles everything.</li>
</ul>

<h2><b>Key Learnings</b></h2>
<ul>
<li>How to structure a front-end project.</li>
<li>Using Git to manage version control.</li>
<li>Automating deployment with GitHub Actions.</li>
<li>Hosting a site for free with GitHub Pages.</li>

</ul>
