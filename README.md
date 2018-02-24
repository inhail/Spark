# Spark
Spark install and basic computing operation  
See hadoop_2 to install hadoop 2 first  
  
Step 1: install Spark
1.go to 'spark apache' website and copy the download link's location  
below is on 'master' hadoop(here we down spark-2.2.1-bin.hadoop2.7.tgz)  
2.type "wget http://apache.stu.edu.tw/spark/spark-2.2.1/spark-2.2.1-bin-hadoop2.7.tgz"  
3.type "tar zxf spark-2.2.1-bin-hadoop2.7.tgz"  
4.type "sudo mv spark-2.2.1-bin-hadoop2.7 /usr/local/spark"  
5.type "sudo gedit ~/.bashrc" (the content can be found in this repository)  
6.type "source ~/.bashrc"  
7.type "spark-shell" to test the installation. If installation succeeded, you will see "scala>"
8.type ":quit" to exit scala  
9.type "cp /usr/local/spark/conf/spark-env.sh.template /usr/local/spark/conf/spark-env.sh"    
10.type "sudo gedit /usr/local/spark/conf/spark-env.sh"(the content can be found in this repository)   
