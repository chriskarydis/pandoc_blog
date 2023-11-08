# pandoc_blog
In this repository I will upload my first try for a pandoc blog 


# Description
In order to make this static blog I folloed the folloing steps:
- Create and write in the "Pandoc_Example.txt"
- Run the command "sudo pacman -S pandoc"
- Run the command "pandoc Pandoc_Example.txt -s -o Pandoc_Example.html"
- Create the file "style.css" with some font and some other information for better view of the text (alignment, etc.).
- Run the command "pandoc Pandoc_Example.txt -s -o Pandoc_Example.html"
- Create the file "footer.html". It contains a copyright notice.
- Run the command "pandoc -c style.css -A footer.html Pandoc_Example.txt -s -o Pandoc_Example.html"

Just by creating the files for the text, the styling and the footer and then run the last command (if you have the pandoc package installed), you will have the same output. I did those steps in order to spot the differences in the static blog, as I was making the changes.
