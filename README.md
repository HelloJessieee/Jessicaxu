# Jessica Xu 徐子悦 · Personal Site

A minimal personal website for Jessica Xu (徐子悦). The site lives in [`docs/`](./docs/) and uses plain HTML and CSS, so it can be hosted without a build step.

## Preview locally

```bash
python3 -m http.server 4173 --directory docs
```

Open <http://localhost:4173>.

## Publish with GitHub Pages

After pushing to `main`, open the repository's **Settings → Pages** and choose **Deploy from a branch**, **main**, **/docs**. GitHub Pages will publish the site at `https://hellojessieee.github.io/Jessicaxu/` after deployment finishes.

All asset paths are relative, so the site works under the repository path.
