# ss 
screen -s mcs java -Xmx16G -XX:PermSize=256m -XX:MaxPermSize=256m -XX:NewSize=1024m -XX:MaxNewSize=1024m -XX:+UseParNewGC -XX:+CMSIncrementalPacing -XX:+UseFastAccessorMethods -XX:+UseConcMarkSweepGC -XX:MaxGCPauseMillis=100 -XX:+CMSParallelRemarkEnabled -XX:ParallelGCThreads=20 -jar server.jar
