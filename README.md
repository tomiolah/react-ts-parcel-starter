# Using this template

Based on [this](https://grant-bartlett.com/blog/react-typescript-parcel-starter-project/) tutorial.

1. Install Yarn

    ```bash
    npm i -g yarn
    ```

2. Install dependencies for development

    ```bash
    yarn install --production=false
    ```

    [More details](https://classic.yarnpkg.com/en/docs/cli/install/#toc-yarn-install-production-true-false)

3. Compile project:

    - Dev version:

        ```bash
        yarn dev
        ```

        Compiles files into the `build/debug` folder and runs a dev server ([http://localhost:1234](http://localhost:1234))

    - Prod version:

        ```bash
        yarn build
        ```

        Compiles production-ready files into the `build/release` folder

