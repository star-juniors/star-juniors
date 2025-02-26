---
layout: default
title: Adding Entry to The Github Page
parent: How-to's
---

Adding Entry to The Github Page
=====================================

- The UCR Github web page address is [`star-juniors.github.io`](https://star-juniors.github.io). And the corresponding Github repository is [`https://github.com/star-juniors/star-juniors.github.io`](https://github.com/star-juniors/star-juniors.github.io). You always update or modify the Github repository and the changes will be automatically applied to the Github web page within a couple of minutes.

- Any text file written in Markdown format will be translated to web pages. Markdown is a very easy/intuitive text-based format. Markdown files are generally given `.md` as extension.  Knowing the very few basic syntax will be sufficient in our case. For example, compare this current page to it's raw version [here](https://raw.githubusercontent.com/star-juniors/star-juniors.github.io/master/how-tos/adding_entry_for_ucr_page.md). Also, check [this](https://github.com/tchapi/markdown-cheatsheet) page for basic syntax.

- There are two ways you can add an entry or modify an existing entry to the UCR Github page.
The first approach does not require any prior knowledge of `git`, I will call it `non-git user's` approach. The other approach assumes you are a git user who is familiar with the `git` commands. In both cases, you need to have a Github account and the account should be added to this repository as a collaborator.

Non-git User's Approach
-------------------------

- Go to the Github repository [here](https://github.com/star-juniors/star-juniors.github.io) and login to your Github account.

**Modifying Existing File**

- The `README.md` file in the top directory is translated as the main page. If you want to modify the main page or any other existing page, follow these steps:

  - Click on the README.md file (to modify main page) or any other existing `.md` file.  
  - Click on `edit this file` icon on the top right (represented with a pen symbol).
  - Now make your changes. Check preview to ensure it looks as expected.
  - Commit changes when you are done by pressing the green button in the lower left.

**Adding New File**

- New files are added to the corresponding directory (say `meetings, how-tos` etc).
- Go to the appropriate directory.
- Add file > Create New file
- Give the file an appropriate name with `.md` extension.
- Enter the content of the file using Markdown syntax. Check preview to ensure it looks as expected.
- Commit changes by pressing the lower green button.
- Link your newly created file to the main `README.md` file in the top directory following the instruction in the previous paragraph.

Git User's Approach
---------------------

You are a `git` user if you use `git` for versioning of your analysis code, tex files, etc. In this case, you just clone the repository `https://github.com/star-juniors/star-juniors.github.io.git` like any other git repository. Now add files/directory or modify any content. Finally, push your changes to the `master` branch. Before you make changes, do `git pull` to get new updates incorporated.
