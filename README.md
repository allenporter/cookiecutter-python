# cookiecutter-python

A cookie cutter template for python projects.

```bash
$ cruft create https://github.com/allenporter/cookiecutter-python/
```

### Local Testing

When updating the template, you may want to examine the output first before
submitting.

To prepare environment with cruft:

```bash
$ uv venv
$ source .venv/bin/activate
$ uv pip install -r requirements_dev.txt
```

Creating a project with the template:

```bash
$ TMP_DIR=/tmp/x
$ cruft create --output-dir=${TMP_DIR} --no-input .
```

Updating an existing project with the template:

```bash
$ cruft update --project-dir=${TMP_DIR}/python_project_name
```
