# My Personal Website

This repository hosts the source code for my personal website, built with the [Dumbarton theme](https://github.com/tcbutler320/Jekyll-Theme-Dumbarton). I've made some custom modifications to better suit my preferences and requirements. A huge thanks to the original developer of the Dumbarton theme for providing a solid foundation for this project.

## Custom Modifications

I have made several modifications to the original Dumbarton theme to tailor it to my needs. 

## GitHub Actions Workflow

I have set up a GitHub Actions workflow to build and deploy my website to GitHub Pages. This setup resolves the issues with using Jekyll-scholar, making it compatible with GitHub Pages.

The workflow is triggered on every push to the `dev` branch, builds the Jekyll site, and deploys it to the `main` branch, from where GitHub Pages serves the website.

You can find the workflow file in the `.github/workflows` directory of this repository, named `jekyll.yml`.

## Building Locally

If you wish to build the website locally.You should prepare the Ruby enviormentfirstly, then follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/kang-hong-29/kang-hong-29.github.io.git
2. Navigate to the repository directory:
   ```bash 
   cd kang-hong-29.github.io
3. Install the necessary Ruby gems:
   ```bash
   bundle install
4. Build the Jekyll site:
   ```bash
   bundle exec jekyll serve
Now, you can access the website locally at http://127.0.0.1:4000.

## Acknowledgements

Thanks to the original developer of the Dumbarton theme for creating a great starting point for this website.
Thanks to the Jekyll community for the support and resources that made this project possible.
  