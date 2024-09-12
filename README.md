# Personal Page

## Introduction
This is a repository that contains a personal page template for Pro-AI CDT students. The repository contains a basic
[here](https://quarto.org/) aplication and a Github action to update and deploy at every successful push in your local repository.

Its recomended to hava at least an overview about Quarto and how qmd files work [here](https://quarto.org/) .

## Important Files

### _quarto.yml

The _quarto.yml file plays a crucial role in configuring and managing Quarto projects. It's a central configuration file that allows you to define global settings and options for the entire project. These settings streamline project organization, customization, and output generation across multiple documents.

## Quarto Markdown 

Quarto Markdown is an extended version of Markdown used in the Quarto framework, allowing you to write documents, presentations, websites, and reports that include text, code, and interactive elements. Quarto Markdown builds on standard Markdown syntax by adding support for more advanced features, especially in the context of data science, reproducible research, and technical writing.

More information [here](https://quarto.org/docs/authoring/markdown-basics.html)

### _variables.yml

This file is not a default quarto file. It was create to store global variables for our project. Feel free to add new ones or modify the ones we created.

## Sections

### Home

This section provides a brief introduction about yourself and the content of your webpage. Be sure to include your bio, academic background, and research interests.

You can update this page modifying the index.qmd file. The section between three dashes it's written in yml, here you can relevant information and configurations of your page.  

For more information about Quarto and how to edit qmd files click [here](https://quarto.org/)

### Projects

This is where you can share updates on the projects you're working on throughout your PhD. The structure is a Quarto listing, you can add new posts to the feed creating new .qmd files in the folder projects. 

This section is implemented as a quarto [listing](https://quarto.org/docs/websites/website-listings.html). You can generate new entries for this section adding qmd files to the projects directory. To structure your entries follow the samples in the folder.

### Research

This section is intended for you to fill in with your research interests across three distinct subtopics. To edit this page you can add information to te research.qmd file.

To add new entries to this page, fill each of the pre-populated sections with te relevant information. 

### Papers

This section contains information about the papers written during your PhD. Each entry in this listing is created adding new qmd files to the folder publications. To structure your entries follow the samples in the folder.
### Conferences

This section is designed for sharing your experiences at the conferences you attended during your PhD. As the previous one, to create new entries add new qmd files to the folder events. To structure your entries follow the samples in the folder.

### Blog

You can also create blog posts about your life as a PhD student in Pro-AI CDT. To author a new post you can add a neq qmd file to the folderblogposts .To structure your entries follow the samples in the folder.