# Reusable GitHub Actions Workflow

+ [buildimage.yaml](buildimage.yaml)
   This workflow builds the dockerimages and pushes them to the GHCR.
+ [buildpackages.yaml](buildpackages.yaml)
   This workflows builds the python and debian packages. It also uploads them to the workflow.
+ [lint.yaml](lint.yaml)
   This workflow runs the linting with flake8.
+ [publish_artifacts.yaml](publish_artifacts.yaml)
   This workflow uploads the packages to PYPI and Artifactory.