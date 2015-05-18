# machine-learning
Machine Learning using spark and python

# Installation instructions

## Mac

    brew install apache-spark
    
    
test to make sure that the install has worked run the following

    run-example org.apache.spark.examples.SparkPi
    
If you hunt through the output you should see "Pi is roughly 3.14026"

You can increase the parallelism by doing the following

    MASTER=local[2] run-example org.apache.spark.examples.SparkPi        

To run the python spark shell run
    
    pyspark
    
it will give you a shell similar to the python one. 

## Spark Programming model

## background reading
[http://spark.apache.org/docs/latest/quick-start.html](http://spark.apache.org/docs/latest/quick-start.html)
[http://spark.apache.org/docs/latest/programming-guide.html](http://spark.apache.org/docs/latest/programming-guide.html)

   
    







