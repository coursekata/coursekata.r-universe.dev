# coursekata.r-universe.dev

The registry for CourseKata's R-universe, <https://coursekata.r-universe.dev>. R-universe reads `packages.json` and builds every package it lists, from source and as binaries for macOS, Windows and Linux.

To install a package from it:

```r
install.packages("coursekata", repos = c("https://coursekata.r-universe.dev", "https://cloud.r-project.org"))
```
