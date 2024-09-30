[![Check Latex Compilation](https://github.com/zhiruiluo/my_cv/actions/workflows/check_latex.yml/badge.svg)](https://github.com/zhiruiluo/my_cv/actions/workflows/check_latex.yml)
[![Deploy static content to Pages](https://github.com/zhiruiluo/my_cv/actions/workflows/publish_static.yml/badge.svg)](https://github.com/zhiruiluo/my_cv/actions/workflows/publish_static.yml)

# Share your CV online in several steps for ***FREE***

If you would like to share your CV through Internet quickly and free, this repo will go through steps to publish your CV online via Github hosted server for free.

# Personal academic curriculum vitae (CV) latex templates

Click `use this template` and replace the content to your information.

Enabling github actions and Github pages will make your CV available online at ```https://{your_github_username}.github.io/{repo_name}/main_cv.pdf```.

# High-lighted Features

- Provided CV template for your fast adpotion
- Bold the name of specific author in all bib entries
- Automatic build pdf and publish to github pages when merge to main branch

# Knowledge Prerequisites

- LaTex
- Basic Github commands

# Steps of publishing CV

- Click ```Use this template``` and choose ```Create a new repository```
    - This will create a new repository in your Github account
- Enable GitHub Actions (This step may be skipped when using template)
    - Go to Actions (On the top menu)
    - Click Enable GitHub Actions
- Setup GitHub Pages
    - Go to ```Settings``` (On the top menu)
    - Click ```Pages``` (On the left side menu)
    - Choose ```GitHub Actions``` in ```Build and deployment``` section (Keep other setting the same unless you know their meaning)
- Replace your own content
    - Clone repo or edit in codespaces
    - Replace your information in ```main_cv.tex``` (You can copy it to [Overleaf](https://www.overleaf.com/learn) editing and checking the compiled PDF, then copy back to your repo)
    - Replace your publications in ```biblio.bib``` (This is enabled by ```biblatex``` package)
    - Replace your ```README.md``` if you want ([Markdown Basic Syntax](https://www.markdownguide.org/basic-syntax/))
    - You can customize the ```index.html```
    - Push your changes to main branch
- Check your live pdf and gh-pages after all actions done
    - This step may take several minutes
    - PDF url: ```https://{your_github_username}.github.io/{repo_name}/main_cv.pdf```
    - GH-Pages: ```https://{your_github_username}.github.io/{repo_name}```
    
# Demo

My username is ```zhiruiluo``` and repo name is ```my_cv```. Then, the PDF url and GH-Pages are:
- Check live PDF [[https://zhiruiluo.github.io/my_cv/main_cv.pdf]](https://zhiruiluo.github.io/my_cv/main_cv.pdf)
- Check live GH-Pages [[https://zhiruiluo.github.io/my_cv]](https://zhiruiluo.github.io/my_cv)

# My Personal Website

Visit my personal website at [zhiruiluo.github.io](https://zhiruiluo.github.io)

# Credits

Geoff Boeing's LaTeX academic CV: [https://github.com/gboeing/cv](https://github.com/gboeing/cv)
