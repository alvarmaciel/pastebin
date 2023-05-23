`shbin` turns a Github repo into a pastebin. 

It's a tiny command-line tool we've built at
[Shiphero](http://shiphero.com) that lets you easily upload code
snippets, notebooks, images, or any other file to a Github repository
that acts as your internal pastebin, and returns the URL to share it
with your team. If possible, this URL is automatically copied to the
clipboard.

# Why? 

You want to share code snippets, images, notebooks, etc. with your team,
probably privately. Gist is great, but it has some limitations:

- The content may be secret but it is not private: if you have the url
  you have the access (and to err is human). 
- The ownership of the shared content is in the user's namespace, not
  the organization's.  What happens if the user leaves the organization? 
- You can't find some secret content shared by a teammate if the URL is
  lost. Only the person who created it can find it, and even that isn't
  easy if the content doesn't have a good name and description. 
- Content organization is difficult: you can upload multiple files to
  a gist, but you can't create folders.
- The default gist interface does not allow you to "paste" an image (you
  can paste it as part of a comment, but not as part of the gist content
  itself). Sharing screenshots is a common use case on computers. 
