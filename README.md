# The Little Cloud Foundry Book

A short yet informative introduction to Cloud Foundry, an open source
polyglot Platform-as-a-service that is Apache 2.0 licensed.

# Building A PDF

You want to build the PDF from scratch? You will need a recent pandoc (1.9) and a few deps.

On Debian-ish systems

    sudo apt-get install texlive-metapost texlive-fonts-extra cabal

You should install pandoc with cabal.

    cabal update
    cabal install cabal-install # get the latest cabal
    cabal install json-0.4.4    # get around dependency conflicts
    cabal install pandoc        # install cabal

# Author

Jonathan "Duke" Leto

# Inspiration

Inspired by ["The Little MongoDB Book"](https://github.com/karlseguin/the-little-mongodb-book) by Karl Seguin.

# Copyright

Leto Labs LLC, 2012

# License

<a href="http://creativecommons.org/licenses/by-nc-sa/3.0/legalcode">
<img src="http://i.creativecommons.org/l/by-nc-sa/3.0/88x31.png">
</a>
