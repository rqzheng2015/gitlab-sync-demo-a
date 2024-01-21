# gitlab-sync-demo-a

This is a demo project to show how to sync code between two gitlab repositories.

This repo is repo A.

Repo B can be found [here](https://github.com/rqzheng2015/gitlab-sync-demo-b).

## Prequisites

Run `pnpm install` to install dependencies.

## How to use

1. Make sure you are using gitlab.
2. Check the .gitlab-ci.yml file in this repo, and migrate it to your project with necessary changes.
   > Be sure to migrate repo B as well, which can be found [here](https://github.com/rqzheng2015/gitlab-sync-demo-b).
3. Run the ci on your gitlab repo to see if the code is synced to repo B successfully.
