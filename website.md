---
layout: default
title: Commercial Due Diligence
---

##### Tools

This website was built using Materizialize and Jekyll. Materialize is a responsive front-end
framework based on Material Design. Jekyll can transform text into static websites, but was  
was primarily used to enable the re-use of headers, footers and navigation.

##### Technical Notes

To create the html filea:
jekyll build --verbose

git add .
git commit -m "website update"
git push -u origin main

To compile the scss files to css:
npm run sass-prod

