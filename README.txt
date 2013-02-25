Escala-lib
==========

Only the EScala library (without compiler) 

This library can be extended by other libraries, without the
need to include this code when there are no changes needed.



if not specified set SCALA_HOME

example: 
$ find /opt/local/share -name 'scala-compiler.jar'
/opt/local/share/scala-2.10/lib/scala-compiler.jar
/opt/local/share/scala-2.8/lib/scala-compiler.jar

export SCALA_HOME=/opt/local/share/scala-2.10

complete build:
ant  -Dscala.home=${SCALA_HOME}