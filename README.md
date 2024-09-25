# Image Analysis Tutorial Instructional Usage


## Installation and Usage Instructions Locally
1. Clone this repository in a new folder 
2. Install Jupyter books to your environment - ```pip install -U jupyter-book``` (ideally should have an envrionment.yml file)
3. Render books: Navigate to the book's parent directory and run the following command to build the book: ```jupyter-book build ImageAnalysisTutorial```. This will create a new _build directory under your ImageAnalysisTutorial folder.
4. If you want to add or delete a file/notebook, make sure to reflect those changes in the toc file and rebuild your book


## Tips
- Important files - configuration file (_config.yml) and table of contents file (_toc.yml)
    - If you add or delete a file or notebook, make sure to reflect those changes in the toc file
- If you notice your table of contents is not functioning or updating correctly, clear the cache by running this command in your terminal from your parent directory of where the tutorial is hosted: ```jupyter-book clean ImageAnalysisTutorial``` and build again using ```jupyter-book build ImageAnalysisTutorial```
- Formatting is the standard Sphyinx Jupyter template, but if you face issues, start a fresh notebook. You should not have to deal with CSS styling.
- If you don't see a nice GUI and instead a janky HTML website, clean and build again. That might be because it stayed stagnant too long.
- Limitations
    - Interactivity within graphs isn't easily possible
    - Can't edit and view dynamically
  


## For future deployment without hosting locally
- Can deploy to GitHub pages by setting up GitHub Pages to serve the ```_build/html``` folder as a website.
- Navigate to the repository settings in GitHub, scroll to the "Pages" section, and choose the branch that contains the book’s HTML files (usually main or gh-pages but have not tested it). 


## Other from Template
There is a lot more that you can do with outputs (such as including interactive outputs)
with your book. For more information about this, see [the Jupyter Book documentation](https://jupyterbook.org)


