# Your Blog — free starter

A minimal Jekyll blog with a browser-based Decap CMS editor.

## Fastest setup

1. Create a free GitHub account.
2. Create a **public** repository, e.g. `my-blog`.
3. Upload this entire folder to the repository and commit to `main`.
4. In GitHub: **Settings → Pages → Source → GitHub Actions**.
5. Your public site will build from the included workflow.
6. To enable the `/admin/` browser editor, connect the repo/site to Netlify and enable **Identity** + **Git Gateway**. The site can remain free; this is only the authentication bridge used by Decap CMS.
7. Visit `/admin/` and log in.

## Changing the name

Edit `_config.yml`:

    title: "Your Blog"
    description: "A place for notes, ideas and stories."

## Writing

Open `/admin/`, click **New Post**, write, add photos, and publish. The CMS commits the post into `_posts/`, after which the site rebuilds automatically.
