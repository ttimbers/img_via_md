## Demo on using markdown syntax to make images in `.pdf`, `.html` and `.markdown`

To get the `.html` and `.markdown` files in the `results` directory. I ran the
following command from the project root directory in R:
```
ezknit("src/img_via_md.Rmd", out_dir = "results")
```

To get the `.pdf` files in the `results` directory. I ran the
following command from the project root directory in R:
```
rmarkdown::render("src/img_via_md.Rmd", output_dir = "results")
```
