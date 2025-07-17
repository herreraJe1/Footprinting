# 🕵️‍♀️ Information Gathering – Supermaxi

## 1. Introduction

This report presents a passive footprinting analysis of the Supermaxi website to identify potential data exposures.

## 2. Web Navigation

- Site: https://www.supermaxi.com  
- Tools: F12, DeadLinkChecker  
- Findings: 15 broken links (404, 403, 401)

## 3. robots.txt

- URL: https://www.supermaxi.com/robots.txt  
- Blocked paths: `/wp-content/uploads/wpforms/`  
- Sitemap: `/sitemap_index.xml`

## 4. Site Download

- Tool: HTTrack  
- Files reviewed: HTML, JS  
- Comments found: no critical data

## 5. Metadata

- Tool: FOCA  
- PDF documents from 2019, 2022, 2023  
- Sizes: 53.57 KB – 12.68 MB

## 6. Google Dorks

- Operators: `site:`, `inurl:`, `filetype:`, `cache:`  
- Public files found: PDFs, forms

## 7. Emails and Leaks

- Example: `gerencias@favorita.com`  
- No leaks found in Have I Been Pwned

## 8. Conclusion

Public information can be used to map attack vectors. While no critical flaws were found, exposure of paths and metadata was evident.
