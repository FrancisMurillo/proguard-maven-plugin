ProGuard Maven Plugin - Nobody's Version
---------------------

This is just my fork of the original proguard-maven-plugin to fix some issues with the obfuscation.

See the original proguard plugin at [Github](https://github.com/wvengen/proguard-maven-plugin).
Thanks for the plugin dood.

Usage
-----

To use this, just install the plugin by building it with Maven and just change the proguard artifactId and groupID like so instead of ...

```XML
<groupID>com.github.wvengen</groupID>
<artifactID>proguard-maven-plugin</artifactID>
```

Do...

```XML
<groupID>com.github.nobody</groupID>
<artifactID>proguard-nobody</artifactID>
```

And you're good to go. 
