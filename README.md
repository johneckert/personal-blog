# Blog

## Editing the site
To edit the site, you need to install Jekyll and its dependencies. You can do this by running:

```bash
$ bundle install
```
This will install all the required gems specified in the `Gemfile`.

## Running the site
To run the site locally, you can use the following command:

```bash
$ bundle exec jekyll serve
```
This will start a local server at `http://localhost:4000`, and you can view your site in your web browser.


## Creating New Content
To create new content for your site, you can use the following commands:

Create your new page using:
```bash
$ bundle exec jekyll page "My New Page"
```
Create your new post using:
```bash
$ bundle exec jekyll post "My New Post"
```

Create your new draft using:
```bash
$ bundle exec jekyll draft "My new draft"
```
Rename a post or draft using:
```bash
#rename a draft
$ bundle exec jekyll rename _drafts/my-new-draft.md "My Renamed Draft"
# rename a post
$ bundle exec jekyll rename _posts/2014-01-24-my-new-draft.md "My New Post"
```

Publish your draft using:
```bash
$ bundle exec jekyll publish _drafts/my-new-draft.md
```

Unpublish your post using:
```bash
$ bundle exec jekyll unpublish _posts/2014-01-24-my-new-draft.md
```

Create your new file in a collection using:
```bash
$ bundle exec jekyll compose "My New Thing" --collection "things"
```
