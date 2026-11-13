# Keeping People & Pets Together Consortium website

This is a small static website. The page layout lives in `index.html`; website copy and the three News & Events cards live in `content/site.json`. The consortium team can edit the content through Pages CMS after the files are in a GitHub repository.

**Publishing note:** the repository is private. GitHub Pages is available for private repositories only on eligible paid plans, and a Pages site is public by default even when its source repository is private. Enable publishing only when the consortium is ready for the site content to be public. Private Pages access requires GitHub Enterprise Cloud.

## First setup

1. In the repository, open **Settings → Pages** and set the publishing source to **GitHub Actions** when the consortium is ready to publish.
2. Sign in to [Pages CMS](https://app.pagescms.org/) with a GitHub account and install the Pages CMS GitHub App on the account or organisation that owns the repository. Give it access only to this website repository.
3. Open the repository in Pages CMS. The `.pages.yml` configuration provides editing panels for the homepage, about section, members, good practice resources, exactly three News & Events cards, get involved copy, and contact details.
4. Add consortium editors as collaborators with write access to the repository, then ask them to sign in to Pages CMS. They can update the site copy and upload images there; their saved changes are committed to GitHub and the Pages workflow publishes them.

The source repository contains the editable content and design files. The publish workflow copies only the website, content data, logo and media into the public site. Keep the repository free of private information because collaborators and anyone with repository access can read its contents.

For a local preview, serve the project folder with a local web server so the browser can load `content/site.json`.
