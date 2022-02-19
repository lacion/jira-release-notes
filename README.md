# Jira Release Notes Action

this actions generates release notes from jira tickets in commit messages

## Inputs

## `jiraHost`

**Required** url of jira server.

## `jiraCode`

**Required** jira project code.

## `jiraUsername`

**Required** jira username.

## `jiraPassword`

**Required** jira username password.

## Example usage

```
uses: actions/jira-release-notes-action@v0.1.0
with:
jiraHost: 'httos://jira.example.com'
jiraCode: 'XYZ'
jiraUsername: 'johndoe'
jiraPassword: 'foobar'
```
