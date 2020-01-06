# Use boilerplate


1. install [`create-elm-app`](https://github.com/halfzebra/create-elm-app)
    ```bash
    > npm install -g create-elm-app
    ```
2. Create a new project
    ```bash
    > create-elm-app helloWorld

    Creating helloWorld project...

    Dependencies ready!         
    Success! Compiled 1 module.

    Project is successfully created in `/Users/ggomma/Dev/elm-tutorial/02_boilerplage/helloWorld`.

    Inside that directory, you can run several commands:

        elm-app start
            Starts the development server.

        elm-app build
            Bundles the app into static files for production.

        elm-app test
            Starts the test runner.

        elm-app eject
            Removes this tool and copies build dependencies, configuration files
            and scripts into the app directory. If you do this, you can’t go back!

    We suggest that you begin by typing:

        cd helloWorld
        elm-app start
    ```
3. Run app
    ```bash
    > cd helloWorld
    > elm-app start
    ```