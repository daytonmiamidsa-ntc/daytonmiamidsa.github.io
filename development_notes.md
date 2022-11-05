# Notes During First Site Development

* I copied the peninsula repo. There are definitely pages to delete, but I don't immediately know which they are. I'm going to look at the jekyll documentation to get a better idea.
* Should the CNAME file be deleted or emptied or updated to the assumed domain name?
* I added the gitignore from github (<https://github.com/jekyll/jekyll/blob/master/.gitignore>). The `_site` directory and `Gemfile.lock` should not be in the repository. When using github, the site pages are built automatically.
* What should be in a chapter's README.md? Instructions for adding new posts and common edits that chapters need to make. The common edits could grow over time as more chapters ask the NTC questions.
* Should there be a separate repository that is just a template so that you don't have to delete stuff or are the peninsula pages nice to have as reference?
* The changelog seems to be for the theme and not the site.
* There has to be a way to define the social media links once and then reference them in pages.
  * The correct solution seems to be adding a single source of social media info to a `_data/social.yml` and then have everything reference that. Unfortunately, changing the references would require changing the theme. Maybe that is something we could do in the future.
* There are probably a bunch of DSA website pages that could be included as site variables for easy use in chapter websites.
