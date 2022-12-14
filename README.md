# Courtbot-VT-Project
[![CircleCI](https://dl.circleci.com/status-badge/img/gh/NathanWEdwards/courtbot-vt-project/tree/test.svg?style=shield)](https://dl.circleci.com/status-badge/redirect/gh/NathanWEdwards/courtbot-vt-project/tree/test)
## Details
This project's manifest file contains all Courtbot-VT related project repositories.

Install repo, initialize, and sync the project in a new directory:
```
# Install repo.
mkdir ~/.bin
PATH="~/.bin:${PATH}"
wget --https-only --secure-protocol=TLSv1_2 https://storage.googleapis.com/git-repo-downloads/repo -O ~/.bin/repo
chmod a+rx ~/.bin/repo

# Initialize and sync the project.
mkdir ~/courtbot-vt
cd ~/courtbot-vt
repo init -u "https://github.com/NathanWEdwards/courtbot-vt-project" -m default.xml
repo sync
```