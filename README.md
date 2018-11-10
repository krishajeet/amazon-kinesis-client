## Purpose
This repo is forked from amazon-kinesis-client (https://github.com/awslabs/amazon-kinesis-client) to provide fix for proto issue which is mentioned here -> 
https://github.com/qubole/kinesis-sql/issues/23 


###### amazon-kinesis-client 1.8.10 
	git clone https://github.com/krishajeet/amazon-kinesis-client.git
	cd amazon-kinesis-client
	git checkout ak/shaded-proto
	mvn install -DskipTests
	
	
## Developer Setup
After building the repo, just do **mvn install -DskipTests** on https://github.com/tteats/kinesis-sql and 
protobuf issue should get resolved.