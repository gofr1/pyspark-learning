# Installation

Download and install python

Download spark + hadoop from https://spark.apache.org/downloads.html  
Unpack it somewhere  

Download Java from https://www.java.com/download/ie_manual.jsp and install  

Download winutils from https://github.com/steveloughran/winutils for particular version you downloaded from Spark site and put it into `\bin\` folder of your Spark installation  

Add environmental variables (better System) example given:

| name | value |
|-|-|
| HADOOP_HOME | D:\spark-3.3.1-bin-hadoop3 |
| JAVA_HOME | D:\java |
| SPARK_HOME | D:\spark-3.3.1-bin-hadoop3 |
| PATH | %PATH%;D:\spark-3.3.1-bin-hadoop3\bin;D:\java\bin; |

Then run `pip install pyspark`

After that you can test if everything is installed and working:

```PS C:\WINDOWS\system32> pyspark --version
Welcome to
      ____              __
     / __/__  ___ _____/ /__
    _\ \/ _ \/ _ `/ __/  '_/
   /___/ .__/\_,_/_/ /_/\_\   version 3.3.1
      /_/

Using Scala version 2.12.15, Java HotSpot(TM) Client VM, 1.8.0_351
Branch HEAD
Compiled by user yumwang on 2022-10-15T09:47:01Z
Revision fbbcf9434ac070dd4ced4fb9efe32899c6db12a9
Url https://github.com/apache/spark
Type --help for more information.
PS C:\WINDOWS\system32>```