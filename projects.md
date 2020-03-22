# Class Projects

Your first pitch assignment is due next **Wednesday Feb. 26**.

This class will have four projects, and you will need to submit a pitch for each one. The requirements of each project are flexible. The goal of these projects are to create something publishable, something you can use as a clip in your portfolio. Here are some guidelines for your projects.

- The project is an original piece of journalism.
- The project is based on findings from your own data analysis.
- The project should involve learning new skills that might not be covered in class.
- The project must be published online.

### Types of projects you can do

- [Blog style](https://www.wsj.com/articles/98-6-degrees-fahrenheit-isnt-the-average-any-more-11579257001)
- [News article](https://www.texastribune.org/2019/06/20/texas-hispanic-population-pace-surpass-white-residents/)
- [Big viz](https://www.wsj.com/graphics/how-money-flowed-and-ebbed-at-ge/)
- [Charticle/Listicle](https://www.wsj.com/graphics/the-rise-of-quants-in-5-charts/)
- [Multimedia](https://www.nytimes.com/interactive/2020/02/13/climate/manila-san-francisco-sea-level-rise.html)

### Examples of successful data stories

- [The Myth of the Criminal Immigrant](https://www.themarshallproject.org/2018/03/30/the-myth-of-the-criminal-immigrant)
- [They Played Dominoes Outside Their Apartment For Decades. Then The White People Moved In And Police Started Showing Up.](https://www.buzzfeednews.com/article/lamvo/gentrification-complaints-311-new-york)
- [Changes to the Census Could Make Small Towns Disappear](https://www.nytimes.com/interactive/2020/02/06/opinion/census-algorithm-privacy.html)
- [How New York’s Elite Public Schools Lost Their Black and Hispanic Students](https://www.nytimes.com/interactive/2019/06/03/nyregion/nyc-public-schools-black-hispanic-students.html)
- [Black Workers' Wages Are Finally Rising](https://www.nytimes.com/2020/02/07/business/black-unemployment-wages.html)

### Deadlines and requirements

All projects must be submitted by publishing through GitHub Pages. I will provide a template for you to lay out your text, images, and charts, but please feel free to break out of the template if you want to experiment with HTML and CSS.

- Project 1: Data analysis using Google Sheets
  - Pitch due **Feb. 26**
  - Project due **Mar. 18**
  - Along with your published story, provide a link to the spreadsheet you used to analyze your data.
- Project 2: Data analysis using Pandas
  - Pitch due **Mar. 25**
  - Project due **Apr. 8**
  - Along with your published story, upload Pandas notebook to GitHub where I can see your analysis.
- Project 3: Scrape data using Python and analyze using Google Sheets and Pandas
  - Pitch due **Apr. 15**
  - Project due **Apr. 29**
  - Along with your published story, upload the Python script you used to scrape the data.
- Final project: combine skills you learn throughout the semester
  - Pitch due **May 6**
  - Project due **May 20**
  - Along with your published story, upload any Google Sheets, notebooks, or scripts you used to analyze the data.

### Pitch requirements

- A summary of your idea or hypothesis, which explains why it is newsworthy. This can be written as a nutgraf.
- Links to data sources, or link to a spreadsheet with the data if you've already collected it.
- Links to potential human sources. For your final project, you must do some additional reporting and talk to at least one source based on your data analysis.
- Example(s) of a publication you could pitch your idea or project to and why.

### Setting up your project

1. In your Desktop, or where you keep your projects, create a folder for this class by typing in `mkdir data-journalism`, then `cd data-journalism`.
2. Create a new folder for your project by running `mkdir google-sheets-project` and `cd google-sheets-project`.
3. Go to [GitHub](https://github.com/) and create a new repository for your project called `google-sheets-project`. Follow the prompts after you create the new repository.

```
echo "# test" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:<YOUR USERNAME HERE>/google-sheets-project.git
git push -u origin master
```

4. Open `google-sheets-project` by running `code .`
5. Write your pitch in README.md
   Here is a useful [cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) on how to use Markdown. [Dillinger](https://dillinger.io/) is a useful tool for previewing and saving your Markdown files.
6. When you are done with your pitch, push your changes to GitHub with the following steps.

##### Another way of creating a project

1. Go to [GitHub](https://github.com/) and create a new repository for your project called `google-sheets-project`, making sure to check that box that says `initialize your repository with a README`.
2. Click on clone or download, making sure that it says `Clone with SSH`. If not, click on SSH.
3. Click on the clipboard to copy the text to your clipboard.
4. In your `data-journalism` folder, run `git clone <ctrl+v here>`.

```
git add -A
git commit -m "pitch"
git push
```

7. Submit the link to your GitHub repo to me, e.g. `https://github.com/<YOUR USERNAME>/google-sheets-project`. README.md files are automatically rendered in your repo.
