* == admin /
  * to create topics defined | application context -> delegates to an `AdminClient`
* TODO:
* `boolean initialize() {}`
  * allows
    * checking topics
    * adding topics
  * 👀if broker NOT available | initializing the application context & (`fatalIfBrokerNotAvailable=false` or `autoCreate=false` ) -> might be needed to invoke this method 👀
* TODO: