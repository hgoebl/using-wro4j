# Example Project using wro4j

This is a small example project which uses the build-time optimizations for a Java web project.

  * Use JSHint and CSSLint to ensure code quality for JS and CSS
  * Exclude JSHint and CSSLint for vendor code (e.g. jQuery)
  * Use lesscss <http://lesscss.org> as a CSS meta framework
  * concatenate und minify JavaScript and CSS

## TODO

  * Find a way to use uncompressed JavaScript and less source files in DEVELOPMENT mode (especially in JSF)
  * Explain options and configurations (why I use lesscss maven plugin in and not wro4j, ...)

## Further reading

  * <http://code.google.com/p/wro4j/wiki/MavenPlugin>
  * <http://stackoverflow.com/questions/7348717/wro4j-maven-plugin-and-jshint>
  * <http://stackoverflow.com/questions/8312969/wro4j-maven-plugin-how-do-i-exclude-files-for-jshint>
  * <http://www.thecodejet.de/blog/2011/09/24/jshint-im-build-prozess/> (German)
  * <https://github.com/marceloverdijk/lesscss-maven-plugin>

## Licence

  * Copyright by Heinrich Göbl (2012)
  * MIT License (do what you wanna; no guarantee; no support)
