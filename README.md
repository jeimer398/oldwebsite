# [BUDataScienceandAnalytics.Github.io](https://budatascienceandanalytics.github.io)
Information and resources for a new student organization
### Please read before making changes to the website (or anything on GitHub for that matter)
It is considered very bad practice to make changes directly to production code. The code for this website is on the _master branch_ and any changes to it (or _commits_) will be immediately published to the website, possibly breaking it.  So you want to be careful not to "commit to master."

### A simplified workflow for GitHub - [GitHub Flow](https://guides.github.com/introduction/flow/)
1. Open a "New issue" ("Issues" tab) to document the changes you wish to make
2. Create a new branch ("Branch:" button) and enter a _short and descriptive_ name (issue-_nn_ works well)
3. Switch to the new branch ("Branch:" button) and make your edits (see below for more info)
4. When finished with all your edits (and while still in your branch) open a "New pull request"
5. Show it to others if needed and when satisfied _merge_ the pull request into the master branch
6. If the website breaks, _revert_ the merge while you fix the problem
7. Close the issue

## How to make changes to the website
* The website content is in the `md` files above (except for README.md which is this file)
* Index.md has the content for the main page
* Click on the name of the file to see the formatted content
* Then click on the pencil icon to edit the content with markdown formatting
* You can click "Preview changes" to see the formatted content without saving
* When finished, click "Commit changes" at the bottom to save changes

### Markdown formatting
* Headings start with #, ##, and ###
* Paragraphs are separated by a blank line, line breaks by two spaces at the end of a line
* Character formatting is: \_italic\_=_italic_, \*\*bold\*\*=**bold**, and \`monospace\`=`monospace`
* Bullet lists start with a "\*" on each line, numbered lists start with "1." etc.
* Links are created with `[link](http://example.com)`=[link](http://example.com)

### Creating a new page
* Clink on `Create new file`
* Give it a short name (no spaces) ending with `.md`
* Add your content
* Make sure there is a link back to `https://budatascienceandanalytics.github.io`
* Save the new page by clicking "Commit changes"
* Add a link from the main page to `newpage.html`
* Note that changing the `.md` page causes the `.html` page to be updated

### Changing the website style
* Click on the settings tab at the top of the page
* Scroll down to "Github Pages" and "Theme chooser"
* Click on "Change theme"
* You can choose from 12 themes and see them previewed below
* Click on "Select theme" to save your selection
* Refresh the webpage to see the results

### Changing the webpage headers
* The text for the headers (title and description) are in the `_config.yml` file
