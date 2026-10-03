# Madison DeLoach — Personal Website

This is my personal portfolio website, built for ISDS 3100 using Google Antigravity IDE and hosted on GitHub Pages. It includes a home page with my profile, skills, experience, and contact info, plus separate pages for my resume and a featured project.

Live site: http://papellapaper.com/madisonre_/

## Reflection

After I pushed my site, I noticed the first line of my styles.css file started with "* ====" instead of "/* ====". I didn't understand why one missing slash mattered, so I asked about it and learned that "/*" is what starts a comment in CSS. Without it, the browser read the comment text as broken code and threw out everything up to the first curly brace, which included my font import and all of my color and spacing variables. One missing character was quietly breaking the styling of my whole site.
