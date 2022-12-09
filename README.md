# Pyspark

### To support Python with Spark, Apache Spark community released a tool, PySpark. PySpark is a Python API for Apache Spark.

Apache spark is designed as a high performance general-purpose competition engine, it works by distributing its work load across different nodes in a cluster. It provides high level APIs in Java Scala Python and R, and an optimized engine that supports general execution graphs. It also supports a rich set of high level tools, including *SPARK SQL* for sql and structured data processing, MLlib for machine learning, GraphX for graph processing and spark streaming.

Apache Spark is an analytical processing engine for large scale powerful distributed data processing and machine learning applications. 
Apache Spark is written in Scala programming language, PySpark lets us work with RDDs in Python programming language, thanks to a library called Py4j that they are able to achieve this. Py4J is a Java library that is integrated within PySpark and allows python to dynamically interface with JVM (Java virtual machine) objects, hence to run PySpark you also need Java to be installed along with Python, and Apache Spark.
PySpark supports most of Spark’s features such as Spark SQL, DataFrame, Streaming, MLlib (Machine Learning) and Spark Core.

PySpark is very well used in Data Science and Machine Learning community due to its efficient processing of large datasets.


### Pyspark installation

PySpark provides pip installation from PyPI. This is usually for local usage or as a client to connect to a cluster instead of setting up a cluster itself.

Pyspark supports Python 3.7 and above.

pip install pyspark

If you want to install extra dependencies for a specific component, you can install it as below: 
# Spark SQL
pip install pyspark[sql]
# pandas API on Spark
pip install pyspark[pandas_on_spark] plotly  # to plot your data, you can install plotly together.


check the pyspark [installation page](https://spark.apache.org/docs/latest/api/python/getting_started/install.html) for other ways to install pyspark
