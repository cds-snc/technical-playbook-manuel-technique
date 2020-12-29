## Technical Details

The Playbook is compiled from [Markdown](https://help.github.com/articles/github-flavored-markdown "Link to More Information About Markdown") files using [Jekyll](https://github.com/jekyll/jekyll "Link to More Information about Jekyll"). To propose a specific change, you can submit a [pull request](https://help.github.com/articles/creating-a-pull-request "More Information on Submitting Pull Requests") with your change to one of these source Markdown files. The Plays from the Playbook are [available in the `_plays` folder](#).

You can also use Github's in-browser editing feature to make an edit to one of these Markdown files and submit your change for consideration without needing to install any additional software.

### Running the Site Locally

To run the site locally on your own computer (most helpful for previewing your own changes), you will need to install Jekyll and other dependencies:

1. If you don't already have Ruby and Bundler installed, follow [the first two steps in these Jekyll installation instructions](https://help.github.com/articles/using-jekyll-with-pages#installing-jekyll "Installation instructions for Jekyll").
2. Next, [fork this repository](https://help.github.com/articles/fork-a-repo/ "Instructions for Forking Your Repository") and clone it on your computer.
3. Navigate to the folder on your computer, and run the command `bundle install` at the command line prompt.

To run the site locally, run `jekyll serve --watch`, then visit `http://localhost:4000/` in your browser to preview the site.

### Editing the Stylesheets

This project uses [Sass](http://sass-lang.com/ "Link to Learn More About Sass") for managing its style sheets. These styles are defined in the [`styles.scss` file](assets/_sass/styles.scss). We use [Jekyll's native SASS support](https://jekyllrb.com/docs/assets/) to auto-generate the required CSS when you run the site locally, as described above.
