
This is the publication repository for *Humanizing the Digital: Unproceedings from the MCN 2018 Conference*. The publications is built using [Quire](https://gettypubs.github.io/quire/)™, a digital publishing platform created by Getty Publications and owned by the J. Paul Getty Trust. Paperback and e-book editions of the book are currently [available at Amazon](https://www.amazon.com/dp/1091360332). A free edition will be released at the MCN 2019 conference in San Diego. All proceeds from the sale of the book go to support the [MCN Scholarship Program](https://conference.mcn.edu/2019/scholarship.cfm).

## Dev Notes

There was a bug in the version of the theme used that prevented proper PDF output. Running `quire preview` and outputting manually with the following command works:

```
prince http://localhost:1313/ http://localhost:1313/dedication/ http://localhost:1313/contents/ http://localhost:1313/intro/ http://localhost:1313/chapters/1/ http://localhost:1313/chapters/2/ http://localhost:1313/chapters/3/ http://localhost:1313/chapters/4/ http://localhost:1313/chapters/5/ http://localhost:1313/chapters/6/ http://localhost:1313/chapters/7/ http://localhost:1313/chapters/8/ http://localhost:1313/chapters/9/ http://localhost:1313/chapters/10/ http://localhost:1313/chapters/11/ http://localhost:1313/chapters/12/ http://localhost:1313/chapters/13/ http://localhost:1313/chapters/14/ http://localhost:1313/chapters/15/ http://localhost:1313/chapters/16/ http://localhost:1313/chapters/17/ http://localhost:1313/contributors/ http://localhost:1313/colophon/ -o static/downloads/output.pdf --no-warn-css-unsupported --no-warn-css-unknown --no-warn-css
```

## License 

Edition © 2019 Ad Hoc Museum Collective<br />
Text © The Authors<br />
Cover © Ad Hoc Museum Collective/Isabella Bruno<br />

Except where otherwise noted, this work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
