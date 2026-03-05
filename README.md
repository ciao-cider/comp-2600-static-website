# Resume hosted on a static website
This repository is an example of a webpage using Pelican, a static site generator that compiles Markdown into HTML.

# Prerequisites
The following instructions require use of the following prerequisites:
1. Access to a Linux terminal. The resources here are possible to install on Windows, but the instructions here do not describe installation on any platform other than a Linux distribution that uses ``apt``.

# Build and Preview Instructions

1. Install Pelican, through the [pelican quickstart guide](https://docs.getpelican.com/en/3.6.2/quickstart.html).

2. Navigate to a folder through your terminal, which is wherever you want the repository to be located.

3. Run ``git clone https://code.cs.umanitoba.ca/santiara/comp-2600-static-website.git .`` in your terminal.

4. Run ``pelican content`` to compile the website into HTML, which will be stored in ``/output``.

5. Run ``pelican --listen`` to start a local web server to preview your website.

6. Navigate to ``localhost:8000`` in your web browser, or *ctrl + click* on the local site link in your terminal.

# External Resources
- [The Markdown Guide](https://www.markdownguide.org/) is an excellent resource as a reference guide for Markdown.

- [The Pelican quickstart page](https://docs.getpelican.com/en/3.6.2/quickstart.html) provides a fast guide to get your static site easily up and running.

- [Pelican Themes](https://pelicanthemes.com/) is a great repository of themes that you can install for your website. Each theme has a separate license, so make sure to check and comply with it if you intend to use a theme.

- [Awesome Static Site Generators](https://github.com/myles/awesome-static-generators) has a massive list of SSGs if you are interested in using an SSG other than Pelican.

# Frequently asked questions (FAQ)
## Why is Markdown better than writing raw HTML?
Raw HTML is harder to read compared to Markdown. See this small snippet of the resume in HTML:
```html
todo
```
and compare it to its equivalent in Markdown:
```md
todo
```

You can see that the Markdown snippet is much easier to parse by a human. Of course writing in Raw HTML is possible to do, but at least for myself Markdown has proven to be an easier way of writing content to serve on a website.

## I changed the Markdown version of my resume, so why don’t I see the changes when I refresh the website in my browser?
Update the website by running ``pelican .`` in your website directory before refreshing the website. If you are hosting a local web server with ``pelican --listen``, end the server by pressing ``ctrl+c`` in the terminal before updating the website.

# Credits
## Contributors
I would like to thank the following:
- Ashley, who helped review the formatting and contents of this README and the resume.
- Andrew Etter, whose book *Modern Technical Writing* helped to improve the prose of this README.
- Tristan Miller, the professor of COMP 2600, who taught me how to use Pelican.
- Peter Vu, the teaching assistant of COMP 2600, who helped me in class during the workshop.

## Resources used
The website uses the [waterspill-en](https://github.com/getpelican/pelican-themes/tree/master/waterspill-en) theme, which uses the MIT license.