# Keeping People & Pets Together Consortium website

This is a small static website. The page layout lives in `index.html`; website copy and the three News & Events cards live in `content/site.json`. The consortium team can edit the content through Pages CMS after the files are in this GitHub repository.

## First setup

1. In the repository, open **Settings → Pages** and set the publishing source to **GitHub Actions**.
2. Sign in to [Pages CMS](https://app.pagescms.org/) with a GitHub account and install the Pages CMS GitHub App on this account. Give it access only to this website repository.
3. Open the repository in Pages CMS. The `.pages.yml` configuration provides editing panels for the homepage, about section, members, good practice resources, exactly three News & Events cards, get involved copy, and contact details.
4. Add consortium editors as collaborators with write access to this repository, then ask them to sign in to Pages CMS. They can update copy and upload images there; their saved changes are committed to GitHub and the Pages workflow publishes them.

The source repository contains the editable content and design files. The publish workflow copies only the website, content data, logo and media into the public site. Keep the repository free of private information because collaborators and anyone with repository access can read its contents.

For a local preview, serve the project folder with a local web server so the browser can load `content/site.json`.
