# Static Websites

You can make free websites for yourself or your projects. There are so many tools for generating and hosting static websites. Take a look at some of the tools here: [staticgen.com](https://www.staticgen.com/).

To learn more about making websites on GitHub, you can check these resources:
* [GitHub pages](https://pages.github.com/)
* [GitHub pages with Jekyll](https://jekyllrb.com/docs/github-pages/)
* [GitHub pages with Hugo](https://gohugo.io/hosting-and-deployment/hosting-on-github/)
* [GitHub pages with Gatsby](https://www.gatsbyjs.org/docs/how-gatsby-works-with-github-pages/)

There are two types of GitHub pages: profile and project. For a personal or organization GitHub profile, the source of the website is in the master branch of a repository with the name: `yourprofilename.github.io`. For the projects, the source is, by default, in the `gh-pages` branch of your project's repository.

If you are in a hurry to make a website, you can [fork](https://help.github.com/en/github/getting-started-with-github/fork-a-repo) one the following repositories:
* [Static-Website-Hugo-Docsy](https://github.com/eLearningHub/Static-Website-Hugo-Docsy) ([website](https://elearninghub.github.io/Static-Website-Hugo-Docsy/))

You may want to change the name of the repository. Make sure to check the GitHub Pages section of the settings of your repository. Choose the `gh-pages` branch from the source menu. If everything goes well, you will see the address of your GitHub page. It should be something like: `yourprofilename.github.io/your-repo-name`.

There is one more thing you need to do. Change the URL in the first line of the `config.toml` file with the address of your GitHub page.

The above repositories include [GitHub Actions](https://github.com/features/actions) to build the website and store the results in the `gh-pages` branch automatically. 

Check if your GitHub page is available. To edit the website, you just need to edit the source files. The GitHub Action updates your website automatically.
