`chmod +x app.py`
`wget -O /bin/hadolint https://github.com/hadolint/hadolint/releases/download/v1.16.3/hadolint-Linux-x86_64`
`sudo chmod +x /bin/hadolint`
`python3 -m venv dockerproj`
`docker build --tag=app .`