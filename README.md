# ccwc-content
Content of the website for CCWC tournaments

Authoring rules:

1. MD, YML and JSON are accepted file formats and extensions.
2. Content in folders **links/**, **news/** and **schedule/** is automatically discovered by the site.
3. Other folders and files are hard-coded.
4. **links/** must be in YML format.
5. Adding a number with "." at the beginning of the link article is mandatory, for content ordering.
6. Don't forget to add **publish: true** for the article to appear.
7. The module will not handle images or other binary formats from this repo. Images in the folder **public/** can be referenced in Markdown files.
8. Pls do not alter this structure with **content/en/**.
9. When an article is added to **en**, the same article shall be added to the other locales, at least with the same content.
