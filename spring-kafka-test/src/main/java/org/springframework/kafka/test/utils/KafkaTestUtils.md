* TODO:
* `ConsumerRecords<K, V> getRecords(Consumer<K, V> consumer, Duration timeout, int minRecords) {}`
  * consumer -- polls -- records 
  * `Duration timeout`
    * MAX time / wait for records
  * `int minRecords`
    * 👁️consumer is polling till `timeout` or `minRecords` received 👁️
* TODO: