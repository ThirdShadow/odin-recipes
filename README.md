# odin-recipes
Before working on the project: 

This project is supposed to put the basic HTML knowledge which I have accumulated to use, by creating a website with multiple recipes. It will probably require text, lists, links, images and all of the other basics. I expect to consolidate my knowledge by completing it.

After working on the project:

A few notes come to mind. Firstly, sometimes it is necessary to use characters that aren't common in English. For these, it is probably best to use the HTML symbols rather than typing them directly. Also, images found on the internet can be slightly awkward. They can be in not only JPG format, but saved as WebP files. These can be converted to JPGs using online web converters or software. Remembering WebP as a format is still probably worthwhile. Images downloaded off the internet should usually be resized when included in a website.

On returning to the Odin Project in 2024 I simply wanted to finish this project quickly and move on, only doing so because I knew that it would be needed for the CSS work later on. In the process, I refreshed my memory on HTML links, the structure of project directories, how to download a repository on Github to your local machine, how to update these files on Github after making local changes and on commit messages, though some revision about that would likely still be useful. The website is simple and regardless of the actual content, fully functional.

02.08.24 note:
When I returned to this project to style it, the intention was mostly just to practice applying some CSS knowledge. In the process a few things became relevant. I found that for specific headings that are styled in a unique way, using an id may be acceptable. Also, if there are multiple such headings (or different elements) that can share certain properties, then having a selector that targets each is also useful. In the stylesheet, this could be after the selectors that target the individual ids.

Sometimes you can style a specific type, such as paragraphs or h2 in this case, and when you want to break from the convention in specific cases, give those elements a class. This is done here in the case of the unordered list type and the ingredlist class.

I have yet to put much thought into fonts. The ones I chose were applied universally and I believe that sans-serif is seen as a safe fallback font to use for browsers.

The links at the bottom of the recipes were a slight nuisance. I gave them a class so that each could be aligned and coloured at the bottom of the page, but this only worked after I put the text inside the link inside a paragraph element, which feels slightly too complex. However, this might be mitigated by using indents, rather than having it all in one line as I have done here. Images could be used similarly.

The main thing that sticks out to me at the moment is that I individually had to link to the stylesheet for all of the subpages in the project, and all of the relevant code was in that one sheet. Though it would require more files, would it be more efficient to give each recipe page its own stylesheet? It might have made it easier to style each page in a unique way. Otherwise, is there a way to simply apply the stylesheet to the subpages with it only being linked in the index?