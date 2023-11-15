# template_bundle

On a Mac, install [brew](https://brew.sh/). Then in a Terminal, run `brew install gcc`.

Download the appropriate .zip file, unzip it somewhere. If you're unsure if your Mac is has an arm64 or Intel(x86_64) chip, run `uname -m` in a Terminal. 

After uncompressing, e.g. `unzip`, the .zip file, `cd` into the relevant folder and try to run the model, e.g., if you're on a Mac arm64 machine:

```
$ cd template_mac_arm64
$ ./project
```

If you have a Mac Intel (x86_64), unzip the template_mac_x86.zip and use its `project` instead. The Terminal command `file project` will tell you which flavor it is.
