JC =javac  -classpath .:../machine:../filesys:../userprog:../threads:/usr/java/lib/rt.jar -deprecation

all:  MemManager.class
	${JC} -g ../threads/Nachos.java

cleanclass:
	(find .. -name "*.class" -print | xargs rm)

cleanbackup:
	(find .. -name "*~" -print | xargs rm)

MemManager.class: MemManager.java
	$(JC) -g MemManager.java

