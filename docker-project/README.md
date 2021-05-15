`chmod +x app.py`
`wget -O /bin/hadolint https://github.com/hadolint/hadolint/releases/download/v1.16.3/hadolint-Linux-x86_64`
`sudo chmod +x /bin/hadolint`
`python3 -m venv dockerproj`
`docker build --tag=app .`
`docker run -it app bash`
`mkdir .circleci`
`touch config.yml`

# CircleCI Local mode
`wget https://github.com/CircleCI-Public/circleci-cli/releases/download/v0.1.15224/circleci-cli_0.1.15224_linux_amd64.tar.gz`
`tar zxvf circleci-cli_0.1.15224_linux_amd64.tar.gz`
`mv circleci to root`
`./circleci local execute`

# Go to circleci