# Personal Page

## Introduction

This is a repository that contains a personal page template for Pro-AI CDT students. The repository contains a basic [Quarto](https://quarto.org/) web application and a GitHub action to update and deploy at every successful push in your local repository.

Its recomended to hava at least an overview about Quarto and how qmd files work [here](https://quarto.org/) .

## Quarto Markdown 

Quarto Markdown is an extended version of Markdown used in the Quarto framework, allowing you to write documents, presentations, websites, and reports that include text, code, and interactive elements. It builds on standard Markdown syntax by adding support for more advanced features, especially in the context of data science, reproducible research, and technical writing.

More information [here](https://quarto.org/docs/authoring/markdown-basics.html)

## Important Files

### _quarto.yml

The _quarto.yml file is essential for configuring and managing Quarto projects. It serves as a central configuration file where you can define global settings and options for the entire project. This simplifies project organization, customization, and the generation of outputs across multiple documents.

More information [here](https://quarto.org/docs/projects/profiles.html#profile-configuration)

### _variables.yml

This file is not a default Quarto file; it was created specifically to store global variables for our project. You are welcome to add new variables or modify the ones that have already been set up.

More information [here](https://quarto.org/docs/authoring/variables.html)

## Sections

### Home

This section offers a brief introduction about you and the content of your webpage. Be sure to include details about your bio, academic background, and research interests.

To update this page, edit the index.qmd file. The section between the three dashes is written in YAML, where you can provide key information and configure your page settings. 

For more information about Quarto and how to edit qmd files click [here](https://quarto.org/)

### Projects

Here, you can share updates on the projects you're working on during your PhD. The structure is a Quarto listing, and you can add new posts by creating .qmd files in the projects folder. 

This section is built using a Quarto  [listing](https://quarto.org/docs/websites/website-listings.html).To add new entries, simply place .qmd files in the projects directory. For guidance on structuring your entries, refer to the examples provided in the folder.

### Research

This section is designed for you to outline your research interests across three different subtopics. To update this page, simply add content to the research.qmd file.

To create new entries, complete each of the pre-populated sections with the relevant information.

### Papers

This section provides details about the papers you have written during your PhD. Each entry in the listing is created by adding new .qmd files to the publications folder. To organize your entries, refer to the examples within the folder.

### Conferences

This section is intended for sharing your experiences from conferences attended during your PhD. Similar to the previous section, you can create new entries by adding .qmd files to the events folder. Use the sample files in the folder as a guide for structuring your entries.

### Blog

You can also write blog posts about your experiences as a PhD student in the Pro-AI CDT. To create a new post, simply add a `.qmd` file to the blogposts folder. Follow the sample entries in the folder for guidance on structuring your posts.