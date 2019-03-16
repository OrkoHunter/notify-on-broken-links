# notify-on-broken-links

A GitHub app that keeps watching your repositories for broken links and creates an issue if any are found

# What is it?

- Install this GitHub app on your repositories and then forget about it.
- Configure what you want to be scanned
  - All of the source code in the repository
  - Maybe the pages on GitHub wiki as well
  - Use glob patterns for excluding some directories or files
- The app will daily look for all the URLs listed in the repository
- It will create an issue on your repository with the links and their status code
- If an issue is already open, the app would not open another open. It will modify the existing one instead.
- Additional configurations of ignoring some specific domains or links can be added.
- The behavior logic of the app can also be configured.

# Development

The project will be a wrapper for a CLI tool designed to do the same job. Currently, this project is not under development.
