# vmn-tips

mvn clean install -> mvn clean package

mvn -T 4 package || mvn -T 1C package

mvn package -am    #increment build

mvn package --offline || mvn package -offline

mvn package -DskipTests			#skip tests
mvn package -Dmaven.test.skip	#skip campillation of tests


Summary

	mvn package -am -o -Dmaven.test.skip -T 1C