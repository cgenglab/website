

We use Wowchemy template (https://github.com/wowchemy/starter-hugo-research-group) for our website.

Look at the document at (https://wowchemy.com/docs/)


## Quick Preview

```bash
$ hugo server
```

Then, look at http://localhost:1313


## Updating Publication

To add publication, make a new folder under `content/en/publication` and put a markdown document `index.md`.


## Updating Members

To add members, make new folders under `content/en/authors` and `content/jp/authors`and put markdown a document `_index.md` in each folder. 


## Upload the Webpage

Upload the webpage by pushing to the github remote repository

```bash
$ git add .
$ git commit -m "explain about the update here"
$ git push
```


## Notes	 

- Please don't put a large file in the repository (e.g., PDF and video of the paper). It will significantly slow the git down. Also GitHub doesn't allow large files in the repository (Don't use "Git Large File"). 