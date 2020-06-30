# How to use:
1. Clone the repo in your home directory.
2. Rename the resulting folder from 'zshmodules' to '.zshmodules'.
3. Copy this code blob into your .zshrc:
```
for file in ~/.zshmodules/*.zshmodule;
do
    source $file
done
```
