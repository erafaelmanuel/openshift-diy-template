# openshift-diy-template

OpenShift action_hooks

"OpenShift executes action hooks script files at specific points during the deployment process.
All hooks are placed in the .openshift/action_hooks directory in the application repository.
Files must have be executable". In Windows, in Git Bash, the following command can be used:
 
git update-index --chmod=+x .openshift/action_hooks/*

References and tutorials
	https://www.youtube.com/watch?v=0jj8fLiO1Bs
	https://www.youtube.com/watch?v=I8bcoIjDPDA
	http://blog.codeleak.pl/2014/10/spring-boot-java-8-tomcat-8-on-openshift.html
	https://www.ivankrizsan.se/2016/12/06/jersey-and-spring-boot-standalone-jar-files/
	