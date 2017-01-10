# docker-vue-cli

Automated builds are setup on dockerhub for this repo.

## Why?
So I could make use of the vue-cli without having to install node on my system.

## Useful

Add this to your `~/.bashrc` file to use this image:

`alias vue='docker run -it --rm -v "$PWD:$PWD" -w "$PWD" amurf/vue-cli vue'`
