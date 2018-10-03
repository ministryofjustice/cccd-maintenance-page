# cccd-maintenance-page

Single static html maintenance page for Claim for crown court defence service intended
for traffic redirection when actual site is undergoing maitenance work with significant
downtime.


# Usage
This static html page already exists in the `mojdsd` AWS account's s3 bucket called `maintain.dsd.io`. To 
place the site in maintenance mode see [Cloud platforms instructions](https://dsdmoj.atlassian.net/wiki/spaces/PLAT/pages/684359870/Maintenance+Mode).


# Development/modification

  - Clone/pull this repo
  - Modify the cccd-index.html
  - git commit, push, PR, merge as you would any repo.
  - upload the html page (only) to the `mojdsd` AWS account's `maintain.dsd.io` s3 bucket, replacing any existing file.
  - follow usage instructions above to put site in maintenance mode
