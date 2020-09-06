# Github scraping for fun and not-for-profit

I was inspired by the work done during [Oceanhackweek2020](https://oceanhackweek.github.io/) (OHW20) to investigate the github API. This started as an idea to count the github commits made by participants during OHW20 and the weeks on either side.

I could not find a good tutorial on scraping commits from a list of Github usernames (though this out of date one by [kb22](https://github.com/kb22/GitHub-User-Insights-using-API) set me on the right track) so I've written a fairly rough one here.

Check it out on binder from your browser [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/callumrollo/github-scraper/main).

You won't be able to run much of the scraping notebook on binder though, as it requires a GitHub API token

### How to 

All the instructions for carrying out this scraping are found in the notebook `ohw_github_scrape.ipynb`. 

If you don't fancy the scraping yourself, but are interested in the results, you will find a csv of anonymised data in this repo along with some very basic analysis in `ohw_analysis.ipynb`

If you found this work interesting, please feel free to fork it and consider submitting a PR. Or contact me on [twitter](https://twitter.com/callum_rollo)

### Aims
- [x] Scrape github for OHW20 participant public information
- [x] Total the number of commits during hack week and the weeks either side
- [ ] Investigate deeper including file types used and wording of commit messages
- [ ] Plot and analyse this info in a blog post
- [x] Provide a how-to, with anonymised data
- [x] Write a tutorial for anyone else curious about scraping Github data
