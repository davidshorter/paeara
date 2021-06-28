# Paeara

# source code

Source code is setup into two branches
* `master` : The master branch with the generated hugo website (No changes to be made here)
* `source` : The source branch which is used to generate the [static site] using [hugo](https://gohugo.io/)

# getting started

* [install choco] (https://github.com/chocolatey/choco/wiki/Installation)
* run command `choco install hugo`
* clone source with git `git clone https://github.com/davidshorter/paeara.git`
* run `hugo serve`
* browse to `http://localhost:1313/`

# build

As changes are commited to the source branch we automatically re generate the hugo site and commit into the master branch over writing the previously deployed site.