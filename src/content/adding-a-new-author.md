# Adding a new author


1. [Create a new markdown file](../creating-and-managing-new-markdown-files.md) with the following content, replacing relevant parts as necessary

```markdown
---
title: "Sachin Tendulkar"
biosmall: "A phenomenon with a willow"
biolarge:
avatar: https://link/to/image
multiple: false
---
```

2. [Upload it](../uploading-new-file.md) to `content/authors`

## Points to remember
1. The file name should follow the pattern `prefix`-`hypenated-name-in-small-case`.md.
    - Prefix of UG students will be `ug`-`batch-year`. eg: ug-2018
	- Prefix of PG Residents will be `pg`-`dept`-`batch-year`. eg: pg-psm-2020
	- Prefix of anonymous contributors will be `anon`
	- Prefix of any other staff/nursing students should reflect their department, batch year etc. eg: `nursing-2020`
	- Prefix of contributors from outside campus may be decided by respective chief editors.
	- Some prefixes is set aside for special authors. eg: 00-edboard, 01-batch-2018 etc

| Correct | Wrong |
|---|---|
|ug-2020-sachin-tendulkar.md|ug-2020-Sachin Tendulkar.md|
||ug-2020-Sachin-Tendulkar|
||UG-2020 Sachin Tendulkar.md|

2. The file names you set becomes part of URL. In the above example, the URL for the author page of Sachin Tendulkar will be <br>
`https://thearticulatemagazine.github.io/authors/ug-2020-sachin-tendulkar/`

3. If there are more than one contributions from the same person, the `multiple` field should be set to `true`. This is the switch that decides whether the `See more works from xxxx` appears below their works. 

![Alt text](image-3.png)

4. `biolarge` field is not mandatory. If there is content in it, it will appear in the author page, instead on `biosmall`.

5. Blank lines should be strictly avoided.