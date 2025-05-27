* == `ConsumerRecordRecoverer` / failed record -- is published to a -- dead-letter

* `ProducerRecord<> createProducerRecord(){}`
  * TODO: Subclasses can override this method to customize the producer record to send to the
    	 * DLQ. The default implementation simply copies the key and value from the consumer
    	 * record and adds the headers. The timestamp is not set (the original timestamp is in
    	 * one of the headers). IMPORTANT: if the partition in the {@link TopicPartition} is
    	 * less than 0, it must be set to null in the {@link ProducerRecord}.