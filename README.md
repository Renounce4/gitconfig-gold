# gitconfig-gold

### Overview
This repository acts as an encyclopedia of .gitconfig aliases and external bash commands.\
Each alias and command has the following sections:
* **Short description** which provides enough information for you to decide if you want the alias.
* **Credidations** to both the original authors of this alias (ordered by earliest authoring date for multiple possible authors) and the individuals that partook in the distribution of this knowledge (as we should credit and incentivize knowledge sharing just as we do knowledge generation).
* **Breakdown** of how each component of the alias' command works. This section is designed to be fairly self contained, requiring only a basic understanding of *git* and *bash*. Not only will this section act as a tutorial for understanding how your tools work, but it will also enable users to customize and tailor the alias as they need to meet their use cases.

Each alias is layed out in the following template:

```gitconfig
[alias]

    ...
    
    #####
    # Short description on a single line.
    aliasName = "command"
    ###
    # Authors:       Earliest author(s), Second ealiest author(s), ...
    # Distributors:  Distributer 1, Distributer 2, ...
    ###
    # Breakdown extending over
    # as many comment lines
    # as needed.
    #####
    
    ...
  
```
