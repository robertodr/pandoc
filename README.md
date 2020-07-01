

# Singularity recipe for Pandoc

https://singularity-hub.org/collections/4516

```
$ singularity pull --name pandoc.sif shub://bast/pandoc
$ singularity run pandoc.sif --from=markdown --to=rst --output=README.rst README.md
```
