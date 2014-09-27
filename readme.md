# Build trees for bash packages for lenny and etch

We needed to build these packages to counter the shellshock issue.

## Why o why?

While it will be seen by some as a wrong thing to still have these systems
running, we can't migrate or upgrade these due to client restrictions.
And it's better to patch these, and help others by providing the work
we did to the community, as to be ashamed and keep this for ourselfs.

## What is there?

The binary packages are only provided as a help for those too lazy to 
build the packages themself. I made them to the best of my knowledge.

I encourage everyone to double check our changes against the original 
debian source trees for bash, and only recompile them once you've verified
our work.

## How to build?

Transfer the correct tree (3.1 for etch and 3.2 for lenny) to a etch or
lenny system with the debian buildtools and packaging tools.

Enter the directory and do a 'dpkg-buildpackage'. Install the needed
build dependencies (if any), and redo the dpkg-buildpackage.

Cheers & happy ops'ing,

Openminds Ops Team