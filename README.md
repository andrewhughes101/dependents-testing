# Dependents testing

Tool to gather all dependents of a package and filter by npm weekly downloads,
github forks, stars and watchers

Example:

```sh
node bin/dependents i-should-pass 10 forks

Getting first 10 dependents of i-should-pass sorted by forks
There are a total of 1 dependents
Dependant {
  name: 'do-you-pass',
  weeklyDownloads: 44,
  forks: 0,
  stars: 0,
  watchers: 0
}

```
