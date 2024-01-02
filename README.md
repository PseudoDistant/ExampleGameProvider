# ExampleGameProvider

A template that people can use for their own GameProviders, or mod Infinite Tux if you'd like.

If you desperately want to use it for Infinite Tux, get the jar here:
https://github.com/qbancoffee/infinite-tux/releases/tag/1.1sfx
Then rename it to 'game.jar', and launch Knot from the same directory that 'game.jar' is in, with the provider and Fabric's dependencies in the classpath.

## License

This template is available under the CC0 license. Feel free to learn from it and incorporate it in your own projects.

Example Game is Infinite Tux, which is licensed under several different licenses, which can be read here:
https://github.com/qbancoffee/infinite-tux/blob/master/copyright
I do not own Infinite Tux, nor do I actively work on it.

# How it works
https://github.com/PseudoDistant/ExampleGameProvider/blob/master/src/main/resources/META-INF/services/net.fabricmc.loader.impl.game.GameProvider \
This file is used by Fabric Loader to determine where your GameProvider class actually is. It's important that the file is in META-INF/services, 
and is named `net.fabricmc.loader.impl.game.GameProvider` exactly.\
The contents of the file should be the full classname of your GameProvider class.




