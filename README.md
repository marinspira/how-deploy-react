### 🚀 Deploying a React.js App on GitHub with GitHub Pages in 10 minutes!

How I love talking about React and to see projects on GitHub, today I'm going to guide you through deploying your application on GitHub, making it accessible on the web in just 10 minutes, at no cost!

### On your GitHub account:
1. Create a Repository for Your Project:
After signing in, head to GitHub, click on "New" to create a new repository. Name your project and click "Create repository".

2. Create a new remote branch named "gh-pages":
You can do this directly on the GitHub platform or cmd.

3. Activate GitHub Pages for your repository:
Go to your repository's settings on GitHub, scroll down to find the "GitHub Pages" section, and select the gh-pages branch as the source.

### In your application:
1. Install the gh-pages package in your project:
Make sure you have the gh-pages package installed in your React project. 

'npm install gh-pages --save-dev'
 
2. Update the package.json:
In your React project's package.json file, add the following lines:

"homepage": "https: //github. com/marinspira/how-deploy-react", 
"scripts": { "pre-deploy": "npm run build", "deploy": "gh-pages -d build" } 

Don't forget to replace your username with your GitHub username and repository-name with the name of your repository.

3. Connect your local repository with the remote one following GitHub's steps if you haven't done it yet. 

4. Deploy Your App:
Now, to deploy your React application, run:

'npm run deploy'

With these simple steps, you can share your React application with the world quickly and easily using GitHub Pages! ✨ 

I hope this helps you in your projects! If you have any questions, feel free to reach out.
