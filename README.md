# Cheat sheet for Sonar products

[A table](/sonar-editions_cheat-sheet.md) to easily compare Sonar products features across editions.

> This is a work in progress.

## How to convert markdown to other outputs

[Pandoc](https://pandoc.org/), a universal document converter, can be used to convert [the table](/sonar-editions_cheat-sheet.md) to other formats.

### Requirements for Debian and derivatives

```
sudo apt-get install texlive-latex-base texlive-fonts-recommended texlive-fonts-extra texlive-latex-extra pandoc
```

### The command

* Use the following command to convert the markdown file to an OpenDocument text document:

```
pandoc sonar-editions_cheat-sheet.md -o sonar-editions_cheat-sheet.odt
```

> Replace *.odt* with other extension, such as *.xlsx*, *.docx*, *.pdf*, etc

* Use the following command to output to multiple formats at once:

``` 
for extensions in odt html pdf ods; do pandoc sonar-editions_cheat-sheet.md -o sonar-editions_cheat-sheet.$extensions; done;
```
