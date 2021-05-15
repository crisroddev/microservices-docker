`create ecr`
`(aws ecr get-login --no-include-email --region us-east-1)`
``docker build -t udacity .`
`docker tag udacity: latest 438569415701.dkr.ecr.us-east-1.amazonaws.com/udacity:latest`
`docker push 438569415701.dkr.ecr.us-east-1.amazonaws.com/udacity:latest`
