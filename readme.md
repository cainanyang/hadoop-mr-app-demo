Demo of writing and packaging Hadoop MapReduce app
==================================================

The example if a updated version of WordCount with MMSeg4j to segment Chinese sentence.

with command `mvn package`, a single jar with all the dependencies (here the mmseg4j-core-1.10.0.jar ) is assembled.

Packaging:
    
    mvn package

Running:
    
    mvn package
    hadoop jar target/hadoop-mr-app-demo-1.0-job.jar org.cainanyang.hadoop.demo.WordCount input-path output-path
