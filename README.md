Flying saucer fork with the following changes:

Demo Browser jar with dependencies can be build with Maven (added into parent pom as module) and allows to skip the most time conusming javadoc creation:

mvn package -Djavadoc.skip

Demo Browser jar can accept parameters:

java -jar flying-saucer-demos/target/flying-saucer-demos-9.0.1-SNAPSHOT-jar-with-dependencies.jar [open-file-on-start.html [export-to-pdf-file.pdf]]

