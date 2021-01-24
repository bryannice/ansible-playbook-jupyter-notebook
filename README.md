# Ansible Playbook Jupyter Notebook

Playbook for installing and configuring Jupyter Notebook on a server or image.

## ToDo's

1. Build logic for building a debian container.

## Docker Tags:

- `bryannice/jupyter-notebook:centos8-2-1.0.0`

## Sample Commands:

### Jupyter Notebook No Token

```
jupyter notebook \
    --no-browser \
    --allow-root \
    --NotebookApp.token='' \
    --ip=0.0.0.0
```

## License

[GPLv3](LICENSE)

## References

* [Markdownlint](https://dlaa.me/markdownlint/)
