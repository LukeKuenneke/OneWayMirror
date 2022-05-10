# OneWayMirror
A GitLab CI way of sending your your git repo wholesale into a corporate intranet git repo/GitLab CI

### Source Repo Variables
* SOURCE_REPO_DOMAIN (github.com)
* SOURCE_REPO (git@somethingelse.com/repo.git)
* SOURCE_SSH_SECRET (Contents of your super secret SSH key)

### Destination Repo Variables
* DESTINATION_REPO_DOMAIN (gitlab.com)
* DESTINATION_REPO (git@something.com/repo.git)
* DESTINATION_SSH_SECRET (Contents of your super secret SSH key)