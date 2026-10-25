# Meme Video Maker Guides

An English editorial site for practical AI video trend guides, original prompt examples, short-form editing workflows, and review checklists. The public blog runs on GitHub Pages. Articles link to the owned [Meme Video Maker site](https://memevideomaker.com/) when a creation workflow is relevant; the blog does not publish its posts into that site's blog database.

## Published guides

- [WYW My Sweetie AI Dance Video: A Photo Guide](https://gpt-img-2.github.io/meme-video-maker-blog/posts/wyw-my-sweetie-ai-dance-video/)
- [Middle Finger Dunk AI Video: Complete Guide](https://gpt-img-2.github.io/meme-video-maker-blog/posts/middle-finger-dunk-ai-video/)

## Add an article

Create `posts/<slug>/index.md` with YAML front matter and the complete English article. Set a unique title and description, `layout: post`, a publication date, a `/posts/<slug>/` permalink, a cover image URL from the owned CDN, descriptive `image_alt` text, the author, and a keyword list. Put useful body images near the section they explain. For video guides, use an HTML `<video controls>` element so readers can play the storyboard in-page.

Use Markdown headings to structure the answer, add original examples and troubleshooting, and link naturally to relevant pages on `memevideomaker.com`. Link related GitHub-hosted guides to each other. Do not add links to third-party websites, copy another publisher's media, or claim that a prompt guarantees a particular result. Keep images and video on the owned CDN and confirm their public URLs and MIME types before publishing.

## Deploy

Pushing to `main` builds the site with Jekyll and deploys it through the GitHub Pages workflow in `.github/workflows/pages.yml`. The project Pages URL is `https://gpt-img-2.github.io/meme-video-maker-blog/`. The build creates the sitemap, RSS feed, page metadata, canonicals, and article structured data from the article front matter.

For local preview, install a current Ruby version and Jekyll, then run `jekyll serve`. The generated site is written to `_site/`, which is ignored by Git.

## Review before each release

- Check factual statements against current primary or first-hand evidence; keep uncertain trend details qualified.
- Review title, description, headings, search intent, accessibility text, and the first-screen answer.
- Confirm all article links go to this blog or `memevideomaker.com`.
- Confirm every image and video URL loads from the owned CDN.
- Verify the rendered page, canonical, BlogPosting JSON-LD, sitemap entry, mobile layout, and GitHub Pages deployment.

Public availability does not grant a reuse license. Media rights remain with their respective owners.
