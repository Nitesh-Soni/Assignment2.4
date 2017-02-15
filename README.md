
1. Explain hadoop in layman's term

Hadoop is a complete eco-system of open source projects that provide us the framework to deal with big data. Let’s start by brainstorming the possible challenges of dealing with big data (on traditional systems) and then look at the capability of Hadoop solution.

Following are the challenges I can think of in dealing with big data :

1. High capital investment in procuring a server with high processing capacity.

2. Enormous time taken

3. In case of long query, imagine an error happens on the last step. You will waste so much time making these iterations.

4. Difficulty in program query building

Here is how Hadoop solves all of these issues :

1. High capital investment in procuring a server with high processing capacity: Hadoop clusters work on normal commodity hardware and keep multiple copies to ensure reliability of data. A maximum of 4500 machines can be connected together using Hadoop.

2. Enormous time taken : The process is broken down into pieces and executed in parallel, hence saving time. A maximum of 25 Petabyte (1 PB = 1000 TB) data can be processed using Hadoop.

3. In case of long query, imagine an error happens on the last step. You will waste so much time making these iterations : Hadoop builds back up data-sets at every level. It also executes query on duplicate datasets to avoid process loss in case of individual failure. These steps makes Hadoop processing more precise and accurate.

4. Difficulty in program query building  : Queries in Hadoop are as simple as coding in any language. You just need to change the way of thinking around building a query to enable parallel processing.



    2. Explain the components of Hadoop framework

At its core, Hadoop is comprised of four things:

Hadoop The Components You Need to Know Essentials

- Hadoop Common- A set of common libraries and utilities used by other Hadoop modules.
- HDFS- The default storage layer for Hadoop.
- MapReduce- Executes a wide range of analytic functions by analysing datasets in parallel before ‘reducing’ the results. The “Map” job distributes a query to different nodes, and the “Reduce” gathers the results and resolves them into a single value.
- YARN- Present in version 2.0 onwards, YARN is the cluster management layer of Hadoop. Prior to 2.0, MapReduce was responsible for cluster management as well as processing. The inclusion of YARN means you can run multiple applications in Hadoop (so you’re no longer limited to MapReduce), which all share common cluster management.
- These four components form the basic Hadoop framework. However, a vast array of other components have emerged, aiming to ameliorate Hadoop in some way- whether that be making Hadoop faster, better integrating it with other database solutions or building in new capabilities. Some the more well-known components include:

Spark- Used on top of HDFS, Spark promises speeds up to 100 times faster than the two-step MapReduce function in certain applications. Allows data to loaded in-memory and queried repeatedly, making it particularly apt for machine learning algorithms

- Hive- Originally developed by Facebook, Hive is a data warehouse infrastructure built on top of Hadoop. Hive provides a simple, SQL-like language called HiveQL, whilst maintaining full support for MapReduce. This means SQL programmers with little former experience with Hadoop can use the system easier, and provides better integration with certain analytics packages like Tableau. Hive also provides indexes, making querying faster.
- HBase- Is a NoSQL columnar database which is designed to run on top of HDFS. It is modelled after Google’s BigTable and written in Java. It was designed to provide BigTable-like capabilities to Hadoop, such as the columnar data storage model and storage for sparse data.
- Flume- Flume collects (typically log) data from ‘agents’ which it then aggregates and moves into Hadoop. In essence, Flume is what takes the data from the source (say a server or mobile device) and delivers it to Hadoop.
- Mahout- Mahout is a machine learning library. It collects key algorithms for clustering, classification and collaborative filtering and implements them on top of distributed data systems, like MapReduce. Mahout primarily set out to collect algorithms for implementation on the MapReduce model, but has begun implementing on other systems which were more efficient for data mining, such as Spark.
- Sqoop- Sqoop is a tool which aids in transitioning data from other database systems (such as relational databases) into Hadoop.


3. Explain the reasons to learn Big data technologies

As the volume of data continues to grow, its potential for business seems to be growing exponentially as
Big Data management solutions evolve allowing companies to turn raw data into relevant trends, predictions, 
and projections with unprecedented accuracy. Companies that use comprehensive Big Data analytics solutions reap the benefits, 
gaining even more insights that drive intelligent decision-making. Some of the benefits of Big Data analytics include…

- Identifying the root causes of failures and issues in real time
- Fully understanding the potential of data-driven marketing
- Generating customer offers based on their buying habits
- Improving customer engagement and increasing customer loyalty
- Reevaluating risk portfolios quickly
- Personalizing the customer experience
- Adding value to online and offline customer interactions

Advantages of Big Data Management Solutions:

The best Big Data management solutions give companies the ability to aggregate a variety of data from hundreds of sources in real time. 
This results in better customer engagement through more effective inbound interactions and marketing programs, which ultimately leads to greater customer 
lifetime value. Big Data analytics powered by advanced Big Data management solutions gives organizations comprehensive customer profiles, 
enabling the delivery of more personalized customer experiences at every touchpoint throughout the buyer’s journey.
And, these top Big Data management solutions eliminate data silos so that organizations get a single, 360-degree customer view 
that includes countless descriptive, calculated, 
and industry-specific metrics for building detailed records of individual customer’s behavior. 
These profiles, or what NGDATA calls “customer DNA,” give organizations a comprehensive understanding of their customers through 
deep customer insights and operationalized analytics, which allow for omni-channel impact.

Big Data may seem daunting, but with the right Big Data management solution, your organization can tackle the data you need to get actionable insights and increase your customer lifetime value.
