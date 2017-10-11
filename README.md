# Distributed Noracle

## Participate in our Network of Knowledge Sharing Nodes
The easiest way to access the Distributed Noracle is to browse to [http://dbis.rwth-aachen.de/noracle/](http://dbis.rwth-aachen.de/noracle/) and use our preconfigured Noracle las2peer network, which is ready to use for you without the need to start your own instance.  

But if you really want to experience the whole capabilities of our distributed Noracle, please follow these instructions to

## Start Your Own Noracle and Join the Network

### 1. Download our Noracle Bundle at [TODO](TODO)

### 2. Install Java and the JCE
Since the Noralce depends on las2peer, which uses strong encryption, this has to be enabled in your Java Runtime Environment (JRE).
If you use an Oracle Java version, you have to enable strong encryption by replacing a set of policy files in subdirectory ./lib/security/ of your JRE installation.
Policy files for strong encryption can be downloaded via Oracle:
[JCE for Java 8](http://www.oracle.com/technetwork/java/javase/downloads/jce8-download-2133166.html "JCE-8")

### 3. Execute the start script located in the main folder of the Noracle Bundle

### 4. Browse to [http://localhost:9082/fileservice/v2.2.0/files/noracle/index.html](http://localhost:9082/fileservice/v2.2.0/files/noracle/index.html)
And you should be able to use your own noracle instance

