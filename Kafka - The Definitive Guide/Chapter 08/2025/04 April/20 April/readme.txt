chapter gave basic info of idempotent producer , how enable.idempotence = true , 
will now attach pid(partitionId) , seqId  -> to a message to ensure exactly once processing , 
state maintained by broker , and periodically flushes state to disk 
