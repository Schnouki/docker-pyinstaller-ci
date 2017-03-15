# docker-pyinstaller-ci
PyInstaller for Windows inside Docker (using Wine). Usable for GitLab CI.

This is a very simple image built on top of the amazing [cdrx/pyinstaller-windows](https://hub.docker.com/r/cdrx/pyinstaller-windows/) ([source](https://github.com/cdrx/docker-pyinstaller)). It only removes the entrypoint script, making it possible (and very easy) to use this image in [GitLab CI](https://about.gitlab.com/gitlab-ci/).
