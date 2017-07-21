## Reproduce Problem

 1. Clone repository

    ```
    $ git clone https://github.com/maoueh/yarn-workspace-already-exist-bug.git /tmp/yarn-workspace-already-exist-bug
    ```

 1. Yarn install once

    ```
    $ cd /tmp/yarn-workspace-already-exist-bug
    $ yarn install
    ```

 1. Yarn install a second time to see the error:

    ```
    $ yarn install
    yarn install v0.28.1
    error There are more than one workspace with name "ramda"
    info Visit https://yarnpkg.com/en/docs/cli/install for documentation about this command.
    ```
