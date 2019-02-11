# Spark---Delta
Find delta between two large data sets (more than 200 Gig each) using Spark - Scala.

spark-submit --master yarn --driver-memory 2g --num-executors 10 --executor-memory 4g --queue production --class com.corporate.sub_corporate.delta_scala.App ./delta-scala-0.0.1-snapshot.jar spark_delta stg_sap_qqq10 sap_test /edw/stging/sap1/qqq10/


