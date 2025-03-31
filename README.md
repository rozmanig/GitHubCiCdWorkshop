# Setting up CI/CD on GitHub

GitHub Actions can be a great choice for building and deploying code from GitHub repositories. This workshop should help you get started using GitHub Actions for your projects. You will start from a workflow template, learn to understand and modify workflow files, search for the actions available in the GitHub Marketplace, and create a simple custom action yourself.

## Prerequisites

To actively participate in the workshop, you need at least a free GitHub account with which you are logged into GitHub in your browser.

Although you can do everything in [GitHub's web based editor](https://docs.github.com/en/codespaces/the-githubdev-web-based-editor), it's easier to work with a locally installed Git client and text editor. You will need to [authenticate with GitHub from your Git client](https://docs.github.com/en/get-started/git-basics/set-up-git#authenticating-with-github-from-git).

For best experience, you should have the following software installed on your computer:

- [Visual Studio Code](https://code.visualstudio.com) as the code editor.
- [Git command line client](https://git-scm.com/downloads) to [work with Git and GitHub in Visual Studio Code](https://code.visualstudio.com/docs/sourcecontrol/intro-to-git).
- [GitHub Actions for VS Code](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-github-actions) extension for easier workflow authoring and management of workflows from within the Visual Studio Code.
- A recent version of [Node.js](https://nodejs.org/en/download) for building and running JavaScript code locally.
- [.NET 8 SDK](https://dotnet.microsoft.com/en-us/download) for building and running .NET code locally.

## Exercises

Detailed step-by-step instructions are available for each hands-on exercise:

- [Exercise 1: Apply a workflow template to a repository](exercises/e1.md)
- [Exercise 2: Modify the workflow in an editor](exercises/e2.md)
- [Exercise 3: Upload workflow artifacts](exercises/e3.md)
- [Exercise 4: Generate test report](exercises/e4.md)
- [Exercise 5: Generate code coverage report](exercises/e5.md)
- [Exercise 6: Custom action for uploading job summaries](exercises/e6.md)

## Next steps

By completing the exercises in this workshop you will have learned about some of the GitHub Actions basic concepts. But there is much more to learn:

- [Caching dependencies](https://docs.github.com/en/actions/writing-workflows/choosing-what-your-workflow-does/caching-dependencies-to-speed-up-workflows)
- [Storing sensitive information in secrets](https://docs.github.com/en/actions/security-for-github-actions/security-guides/about-secrets)
- [Deploying applications](https://docs.github.com/en/actions/use-cases-and-examples/deploying/deploying-with-github-actions)
- [Self-hosted runners](https://docs.github.com/en/actions/hosting-your-own-runners/managing-self-hosted-runners/about-self-hosted-runners)
- [Job configurations](https://docs.github.com/en/actions/writing-workflows/choosing-what-your-workflow-does/running-variations-of-jobs-in-a-workflow)

You can also check my blog for [posts about GitHub Actions](https://www.damirscorner.com/blog/tags/github.html), many of them accompanied by standalone sample projects.
