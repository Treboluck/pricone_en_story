# Priconne EN Story Archive

[See the webpage here](https://treboluck.github.io/pricone_en_story/)

This page contains the whole story text(nicely organized) from Pricone EN before it ended service.

I used [this repo](https://github.com/Expugn/priconne-en_db-fetch) to extract the database, mainly to create jsons to map out the raw filenames to the characters/chapters they correspond to.

I used [this other repo](https://github.com/Andu2/priconne-cdn-extract) to download the data and extract assets. (I did this long time ago, one day before the service ended, because I wanted to save it just in case, my only regret is not downloading ALL the data, but hopefully someone actually did that and has it stored somewhere)

However even the extracted data is not in a readable format so then I used a php script from the [Estertion's repo](https://github.com/esterTion/unity-texture-toolkit) to deserialize the EN story into html(the same htmls you can see in his [webpage](https://redive.estertion.win/story/data/), but like, in english).

Then I wrote some Python and Powershell scripts to parse and organize everything into .md files that'd look nice in this page.

The story CGs are linked directly from [Estertion's webpage](redive.estertion.win).

The videos that play in the main story aren't included.

You'll also see some stories in Japanese. These were probably meant to be translated for future versions, but well, we know what happened.