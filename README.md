typesafe-config-examples
========================

A few, straightforward examples which shows hot to use Typesafe's Config library and HOCON.
Currently examples include the following use-cases:
  * basic reading,
  * value replacements,
  * creating new HOCON objects,
  * rendering HOCON

#### Feedback
Don't hesitate yourself to share your suggestions & reflections.
You can post comment at http://marcinkubala.wordpress.com/2013/10/09/typesace-config-hocon/

### How to run examples
You can run this examples using Maven or SBT:

1. SBT
  ```
  sbt run
  ```
  And then choose appropriate main class (with Scala or Java examples)

2. Maven
  * Scala examples
  ```
  mvn scala:compile scala:run
  ```
  * Java examples
  ```
  mvn compile exec:java
  ```
