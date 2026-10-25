# Meme Video Maker Editorial Library

Public source archive for English editorial guides published on [Meme Video Maker](https://memevideomaker.com). The repository is content-only so articles and original media can be maintained without exposing the private application source.

## Article layout

Each article has its own folder:

```text
posts/<slug>/
├── article.mdx
├── article.json
└── media/
    ├── cover.webp
    ├── body-01.webp
    └── storyboard.mp4
```

Keep published article links on the owned domain. Research URLs, evidence notes, and review logs belong in the private release workspace rather than the public article body. Use only owned/licensed inputs; for generated visuals, record the tool and permission basis in the release notes.

## Publishing workflow

1. Add or revise `posts/<slug>/article.mdx` and its media directory.
2. Review factual claims, title/description, five useful body illustrations, media MIME and CDN availability, internal links, and accessibility text.
3. Update the private Meme Video Maker app repository’s release snapshot and run its manual Cloudflare deployment workflow. That workflow reads the current `main` branch of this public repository and publishes its article content to the site database.
4. Confirm the live article, metadata, sitemap, internal links, and CDN assets before treating a release as complete.

This repository does not contain the private site application, credentials, or a standalone publishing secret. No reuse license is granted by the repository’s public visibility; all rights remain with their respective authors.

## Articles

- [WYW My Sweetie AI Dance Video](posts/wyw-my-sweetie-ai-dance-video/article.mdx)
- [Middle Finger Dunk AI Video](posts/middle-finger-dunk-ai-video/article.mdx)
