Udacity project using Apache Spark to analyze San Francisco crime data.


Increasing the trigger `processingTime` from 1 second to 10 seconds improved performance.
I could detect this from the Spark console alone: Spark no longer printed warnings
that the job was falling behind the stream.
