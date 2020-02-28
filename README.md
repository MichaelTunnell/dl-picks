# Destination Linux Picks
This is the dataset for the Spotlights, Tips, and Tricks featured on the [Destination Linux](https://destinationlinux.org) podcast.

This data is publicly presented on the main website located at https://destinationlinux.org/picks

### Want to Contribute?
Anyone who'd like to help is welcome to do so by forking this repo and making modifications in the dataset for pull requests. This is a CSV dataset with Markdown syntax for organization and simplicity.

### Extra Notes
If you'd like to know how I convert the CSV/Markdown to HTML, I use the following command via the [Pandoc](https://pandoc.org) utility.

`pandoc -f markdown --wrap=preserve dl-picks.csv > dl-picks.html`
