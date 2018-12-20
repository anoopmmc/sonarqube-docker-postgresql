## Let’s see how we can quickly setup a SonarQube environment using Docker container to run a code analysis

To start the services just `docker-compose up`


> Open SonarQube in Your Browser
Go to localhost:9000 in your browser, To access the Administration area - you see the login button in the top right of page. by default you can login with username: admin and password: admin.



# Analyse Your Code to SonarQube Maven Projects
in your root of your project
mvn sonar:sonar -Dsonar.host.url=http://localhost:9000


Analysis Parameters - visit [SonarQube Documentation](https://docs.sonarqube.org/latest/analysis/analysis-parameters/).


#NPM module to run SonarQube/SonarCloud analyses

sonarqube-scanner makes it very easy to trigger SonarQube / SonarCloud analyses on a JavaScript code base, without needing to install any specific tool or (Java) runtime. https://www.npmjs.com/package/sonarqube-scanner