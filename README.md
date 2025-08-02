# Personal blog 

To publish an update:
1. `quarto render`
1. `quarto publish gh-pages`

To push the changes to the upstream repo:
1. `jj describe -m "<message>"`
1. `jj bookmark set main -r @`
1. `jj git push --bookmark main`
