# Docker wso2am with analytics

The goal is to be able to build a working wso2am with wso2am-analytics from the opensource version connected to oracle external database and with active directory user store.
This might include personal addition like ssl trusted certificates or other requirement that might suite only me.

## Getting Started

Use gradle to generate docker files and the needed filtered files for each wso2am and wso2am-analytics then make sure to run analytics' docker before am.

### Prerequisites

Bash, curl, docker, gradle

### Installing

Clone on the docker host
```
gradle build
wso2am-analytics/run
wso2am/run
```
## Contributing

Please propose any pull request.

## Versioning

Still 0.0.1-SNAPSHOT

## Authors

* **Eric Corenely** - *Initial work* - [ecornely](https://github.com/ecornely)

See also the list of [contributors](https://github.com/ecornely/docker-wso2am-with-analytics/contributors) who participated in this project.
