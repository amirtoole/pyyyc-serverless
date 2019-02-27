# Setup
1. Install Node (LTS) - https://nodejs.org/en/download/
2. Install Python (3.7.x) - https://www.python.org/downloads/
3. Globally install serverless
`npm i -g serverless`


(`sls` is shorthand for `serverless` below)

# Hello World
### Create
`sls create --template aws-python3 --path 1-helloWorld`
### Run
`sls invoke local -f hello`

