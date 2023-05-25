# mattermost-ai-site

## Running it locally
You can run the site locally by just doing `hugo server`.

## Adding blog posts
Any blog pages can be added by creating a file in the `content/posts` folder.
You can duplicate any of the original posts to create the new one.

Once done, you can just run the command

The css can be modified in `static/styles.css`

## Publishing changes
Before pushing to the github repo, you need to run `hugo -d docs`. This will generate the static files for the site that are being used by the live site.
