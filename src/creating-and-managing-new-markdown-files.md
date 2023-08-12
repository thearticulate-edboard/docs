# Creating and managing markdown files

There are several softwares available for markdown file management across platforms. At the time of writing, the following ones are worthy of mention
- [markor](https://f-droid.org/en/packages/net.gsantner.markor/): Android
	- NOTE: The author of markor, who is an open source activist, has removed markor from google play store and made it available only in Fdroid(essentially a playstore for open source android apps) and [Markor's Github Repo](https://github.com/gsantner/markor/releases/tag/v2.10.9). You may download latest apk file from either of these and install markor. 
- [obsidian](https://play.google.com/store/apps/details?id=md.obsidian&hl=en_US): Android, Linux, Mac, Windows
- [Visual Studio Code/Vscodium](https://vscodium.com/): Linux, Mac, Windows


Markdown files in hugo is divided to 2 parts. The first part lies on top between 2 `---` and is called "frontmatter". The remaining part forms the content.

The frontmatter follows rules of YAML markup language. While it is not necessary to learn the details of YAML, a few points should be remembered
1. YAML is a strict about blank spaces. Adding an extra blank space or forgetting to place a blank space can mess up the file. Hugo will refuse to run if the frontmatter of even a single file is inappropriate.
1. Blank lines should be strictly avoided.

The content part follows the Markdown formatting rules. It is necessary for an editor to be familiar with rules of markdown. You may familiarize yourselves with markdown here: [Markdown Basic Syntax](https://www.markdownguide.org/basic-syntax/). These rules are supplemented in a few areas by hugo specific markup. These are explained wherever necessary in this document.