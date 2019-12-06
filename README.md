# MavenFAQ
maven常见问题与解决方案
--------------
# 1
[ERROR] The goal you specified requires a project to execute but there is no POM in this directory (D:\myapplication). Please verify you invoked Maven from the correct directory. -> [Help 1]
[ERROR]
[ERROR] To see the full stack trace of the errors, re-run Maven with the -e switch.
[ERROR] Re-run Maven using the -X switch to enable full debug logging.
[ERROR]
[ERROR] For more information about the errors and possible solutions, please read the following articles:
[ERROR] [Help 1] http://cwiki.apache.org/confluence/display/MAVEN/MissingProjectException
解决办法
--------------------------------------------------------------
给参数加引号
mvn install:install-file "-DgroupId=li" "-DartifactId=hutool-all" "-Dversion=5.0.7" "-Dfile=hutool-all-5.0.7.jar" "-Dpackaging=jar"
执行结果
BUILD SUCCESS
---------------------------------------------------------------
