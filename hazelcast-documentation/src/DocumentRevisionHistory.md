

## Document Revision History

|Chapter|Section|Description|
|:-------|:-------|:-----------|
|[Chapter 1 - Preface](#preface)||Added as a new chapter.|
|[Chapter 4 - Distributed Data Structures](#distributed-data-structures)|[IdGenerator](#idgenerator), [ICountDownLatch](#icountdownlatch), [IAtomicReference](#iatomic-reference)| Added as new sections.|
||[MultiMap](#multimap)| Section improved by adding information about how it is implemented and by providing configuration information.|
||[Map](#map)|Eviction section improved by adding the detailed policy and parameter explanations. A subsection on how to evict particular map entries added ([Evicting Specific Entries](#evicting-specific-entries)). Also [Map Overview](#map-overview) and [Backups](#backups) sections enhanced with "how it works" information. Added [Entry Listener](#entry-listener) and [Map Locks](#map-locks) as new sections. Added [Evicting All Entries](#evicting-all-entries) section to explain the method `evictAll`.|
||[Map Persistence](#map-persistence)|Added [Forcing All Keys To Be Loaded](#forcing-all-keys-to-be-loaded) section to explain the method `loadAll`. Also, added [Read-Through](#read-through), [Write-Through](#write-through) and [Write-Behind](#write-behind) sections. Section also enhanced by adding MapStore and MapLoader descriptions with a sample code. Thread information related to MapLoader interface added as a note.
||[Queue](#queue)|Section improved with new subsections. QueueStore interface explanations added. Bounded Queue section modified for a cleaner description.|
||[Lock](#lock), [ISemaphore](#isemaphore)|Sections updated by adding fairness related warnings.
|[Chapter 6 - Distributed Computing](#distributed-computing)|[Executor Service](#executor-service)|HazelcastInstanceAware related information added.
|[Chapter 7 - Distributed Query](#distributed-query)||Query section improved by adding 'how it works' information. Also, [Continuous Query](#continuous-query) section re-written and sample codes added. [Aggregators](#aggregators) added as a new section. A note related to the indexing of non-primitive types added to [Indexing](#indexing) section.|
|[Chapter 8 - User Defined Services](#user-defined-services)||Added as a new chapter explaining Hazelcast's Service Provider Interface (SPI).|
|[Chapter 9 - Transactions](#transactions)|[XA Transactions](#xa-transactions)|Added as a new section.|
||[Sample JBoss AS 7 - EAP 6 Web Application Configuration](#sample-JBoss-AS-7-EAP-6-web-application-configuration)| Added as a new section.|
|[Chapter 10 - Hazelcast JCache Implementation](#hazelcast-jcache-implementation)||Added as a new chapter.|
|[Chapter 11 - Integrated Clustering](#integrated-clustering)|[Tomcat Based Web Session Replication](#tomcat-based-web-session-replication)|Added as a new section (Enterprise Only feature).|
||[Filter Based Web Session Replication](#filter-based-web-session-replication)|Updated by adding SpringAwareWebFilter related information.
|[Chapter 13 - Clients](#clients)|[Java Client](#java-client)|Client configuration related to AWS added and the whole section enhanced. Also, Load Balancer related configuration information added.|
|[Chapter 14 - Serialization](#serialization)||All sections under this chapter re-written and enhanced. Also added HazelcastInstanceAware, Stream & ByteArray Serializer, Serializable & Externalizable sections. Chapter introduction enhanced by adding an overview, a section explaining serialization interfaces and a comparison table for these interfaces.|
||[Null Portable Serialization](#null-portable-serialization)| Added as a new section.|
|[Chapter 15 - Management](#management)|[Clustered JMX](#clustered-jmx)|Added as a new section explaining how to monitor the statistics of distributed objects from a JMX interface (Enterprise Only feature).|
||[Cluster Utilities](#cluster-utilities)|[Member Attributes](#member-attributes) added as a new section. Also, [Cluster-Member Safety Check](#cluster-member-safety-check) section added explaining the PartitionService interface of Hazelcast.|
||[Clustered REST](#clustered-rest)|Added as a new section (Enterprise Only feature).|
|[Chapter 17 - Performance](#performance)|[Threading Model](#threading-model)| Added as a new section.|
|[Chapter 18 - WAN](#wan)|[WAN Replication Queue Size](#wan-replication-queue-size)| Added as a new section (Enterprise only feature).|
|[Chapter 19 - Configuration](#configuration)|[Configuring TCP/IP Cluster](#configuring-tcp-ip-cluster)| Section improved by adding more detailed configuration options.|
||[EC2 Auto Discovery](#ec2-auto-discovery)|Section improved by adding AWSClient Class description, Debugging information and more detailed tag explanations.|
||[Ports](#ports)|Added as a new section explaining how to configure ports which Hazelcast uses to communicate between nodes. Also existing "Restricting Outbound Ports" moved under this new section with the heading "Outbound Ports".|
||[System Property](#system-property)|Updated by adding the descriptions of missing system properties.|
|[Chapter 20 - Network Partitioning](#network-partitioning-split-brain-syndrome)||Added as a new chapter.|
|[Chapter 21 - FAQ](#frequently-asked-questions)||Updated with new questions.|
|[Chapter 22 - Glossary](#glossary)||Added as a new chapter.|





<br> </br>


