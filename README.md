# Apache Spark
Simple files to learn the power of Apache Spark

# Installation
These have been tried on MacOS Sierra 10.12.6. I followed [this](https://medium.freecodecamp.org/installing-scala-and-apache-spark-on-mac-os-837ae57d283f). Already had Java 1.8 on my system and available on PATH. And intend to use python (vs. scala) for client side programming, so `skipped installing scala`

- `brew install apache-spark` - That was it. It got installed to `/usr/local/Cellar/apache-spark/2.2.0`
- `$ which pyspark` -> `/usr/local/bin/pyspark` -> `/usr/local/Cellar/apache-spark/2.2.0/bin/pyspark`
- Add `export SPARK_HOME=/usr/local/Cellar/apache-spark/2.2.0` to ~/.bash_profile

# Execution

- `pyspark` will start an IDLE in which all the required pyspark libraries are load and can start programming
- Execute using spark-submit - `spark-submit streaming.py localhost 9999` as an example