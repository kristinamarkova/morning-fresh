# Cucumber-java

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

In order to execute tests in this project and get a full report of the resutls, do the steps

## Windows

- Register on https://reports.cucumber.io/ with your GitHub account and you will be given a secret token
- Set Environment Variable for cucumber publish token `CUCUMBER_PUBLISH_TOKEN` using the secret token you've been given from the step above, or open cmd and run `setx /M CUCUMBER_PUBLISH_TOKEN "some-secret-token"`
- On the Run/Debug Confirguration for Maven, make sure you have `cucumber.publish.enabled=true` before running your tests

## Mac
- Register on https://reports.cucumber.io/ with your GitHub account and you will be given a secret token
- Open your `.bash_profile` file and add `export CUCUMBER_PUBLISH_TOKEN=some-secret-token` using the token you've been given from the step above
- On the Run/Debug Confirguration for Maven, make sure you have `cucumber.publish.enabled=true` before running your tests

The report will be generated instantly, and you will be given the link of the results report in the output.

[dill]: <https://github.com/joemccann/dillinger>
[git-repo-url]: <https://github.com/joemccann/dillinger.git>
[john gruber]: <http://daringfireball.net>
[df1]: <http://daringfireball.net/projects/markdown/>
[markdown-it]: <https://github.com/markdown-it/markdown-it>
[Ace Editor]: <http://ace.ajax.org>
[node.js]: <http://nodejs.org>
[Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
[jQuery]: <http://jquery.com>
[@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
[express]: <http://expressjs.com>
[AngularJS]: <http://angularjs.org>
[Gulp]: <http://gulpjs.com>

[PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
[PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
[PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
[PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
[PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
[PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>