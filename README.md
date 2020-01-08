# Actions Resources

## Documentation
1. [Core concepts for GitHub Actions](https://help.github.com/en/actions/automating-your-workflow-with-github-actions/core-concepts-for-github-actions)
2. [Automating your workflow](https://help.github.com/en/actions/automating-your-workflow-with-github-actions)
3. [Events that trigger workflows](https://help.github.com/en/actions/automating-your-workflow-with-github-actions/events-that-trigger-workflows)

## Self-paced Learning
* [Hello, GitHub Actions!](https://lab.github.com/github/hello-github-actions!)
* [GitHub Actions: Continues Integration](https://lab.github.com/githubtraining/github-actions:-continuous-integration)
* [GitHub Actions:Publish to GitHub Packages](https://lab.github.com/githubtraining/github-actions:-publish-to-github-packages)
* [GitHub Actions: Continuous Delivery](https://lab.github.com/githubtraining/github-actions:-continuous-delivery)

## Resource
https://github.com/actions
https://github.com/actions/starter-workflows

### Cloud providers

- [AWS](https://github.com/aws-actions/)
- [Google Cloud](https://github.com/googlecloudplatform/github-actions/)
- [Azure](https://github.com/Azure/actions/)

### Other popular tools

- [Atlassian JIRA](https://github.com/marketplace?utf8=%E2%9C%93&type=actions&query=jira)
- [SonarCloud](https://github.com/marketplace/actions/sonarcloud-scan)
- [JFrog CLI](https://github.com/marketplace/actions/setup-jfrog-cli)
- [Vault Secrets](https://github.com/marketplace/actions/vault-secrets)
- [Run mabl tests](https://github.com/marketplace/actions/run-mabl-tests)
- [Close Stale Issues](https://github.com/marketplace/actions/close-stale-issues)
- [GitHub Actions](https://github.com/actions)



# fib-tools

![](https://github.com/bbq-beets/fib-tools/workflows/CI/badge.svg)



## Get the nth Number

```javascript
const {getNumber} = require('@bbq-beets/fib-tools')
assert.strictEqual(getNumber(8), 21)
```asdfasdfadsf

## Get a List of Numbers

```javascript
const {getList} = require('@bbq-beets/fib-tools')
assert.strictDeepEqual(getList(8), [0, 1, 1, 2, 3, 5, 8, 13, 21])
```

## Get a Sequence of Numbers

```javascript
const {getSequence} = require('@bbq-beets/fib-tools')

const seq = getSequence()

for (const n of seq) {
  console.log(n) // The next Fibonacci number in the sequence
}
```
