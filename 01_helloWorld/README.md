# Setup Default Elm Project


1. Setup basic elm project
    ```bash
    > elm init
    
    Hello! Elm projects always start with an elm.json file. I can create them!

    Now you may be wondering, what will be in this file? How do I add Elm files to
    my project? How do I see it in the browser? How will my code grow? Do I need
    more directories? What about tests? Etc.

    Check out <https://elm-lang.org/0.19.1/init> for all the answers!

    Knowing all that, would you like me to create an elm.json file now? [Y/n]: Y
    Okay, I created it. Now read that link!
    ```
2. Create Main.elm in src directory
3. Write Main.elm file
    ```elm
    module Main exposing (main)

    import Html exposing (h1, text)

    main = h1 [] [text "hello world"]
    ```
4. Run code
    ```bash
    > elm reactor

    Go to http://localhost:8000 to see your project dashboard.
    ```
5. Open browser and enter `http://localhost:8000`
6. Click `Main.elm` from your navigator