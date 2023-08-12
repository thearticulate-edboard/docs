# Adding a new painting

1. If it is a new author, create an author file for her/him. See [Adding a new author](./adding-a-new-author.md)
2. If it is an existing author, ensure that her/his author file has `multiple` field set to `true`
3. All paintings should follow size specifications mentioned in [Image specifications and dimensions](../image-dimensions.md)
4. Duplicate each painting to create a thumbnail. Thumbnails should also follow size specifications mentioned in [Image specifications and dimensions](../image-dimensions.md).
5. Upload photos and thumbnails to image host (See [Uploading images](../uploading-images.md)) and collect their direct links.
6. Create a new markdown file (See [Create a new markdown file](../creating-and-managing-new-markdown-files.md)) with the following content, replacing relevant parts as necessary

```markdown
---
title: "Appropriate title"
authid: ug-2023-sachin-tendulkar
img: 
tags: []
date: 2023-03-25T06:00:00
---

{{< art "https://link-to-painting-here" >}}

{{< quote >}}

Appropriate quote here

{{< /quote >}}
```
1. Upload it (See [Upload new file](../uploading-new-file.md)) to `content/painting`

## Checklist

- Author's name, avatar, bio
- Appropriately resized image, thumnail
- Title for the post
- Accompanying quote.

