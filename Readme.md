# DevOps course

This repo contains a reveal.js presentation about DevOps.
To visualize this presentation, go here: [https://arthurmauvezin.github.io/presentation-template](https://arthurmauvezin.github.io/presentation-template)
You can also clone this repo and expose static pages through your favorite web server.

> This course was originally created for ECE engineering course. You can use it freely.

## See this course locally with docker
```bash
docker build -t presentation-template .
docker run -d --rm -p 80:8080 --name=presentation-template presentation-template
```
* After a few seconds, you can see the slides on [http://localhost](http://localhost)
* When you want to stop the instance, run:
```bash
docker stop presentation-template
```

## Print this course to pdf (only in chrome and chromium)
* Click on [this link](https://arthurmauvezin.github.io/presentation-template/?print-pdf&pdfSeparateFragments=false)
* Then `CTRL+P` on the generated page
* Change the following settings

Setting | Value
--- | ---
Destination | Save as PDF
Pages | All
Pages per sheet | 1
Margins | Default
Options | Background graphics

* Click on save
~                 
