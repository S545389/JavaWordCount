# JavaWordCount
JavaWordCount

Steps:

1. mvn archetype:generate -D archetypeGroupId=org.apache.beam -D archetypeArtifactId=beam-sdks-java-maven-archetypes-examples -D archetypeVersion=2.42.0 -D groupId=org.example -D artifactId=word-count-beam -D version="0.1" -D package=org.apache.beam.examples -D interactiveMode=false

2. cd .\word-count-beam

3. dir .\src\main\java\org\apache\beam\examples

4. $ mvn compile exec:java -Dexec.mainClass=org.apache.beam.examples.WordCount -Dexec.args="--inputFile=sample.txt --output=counts" -Pdirect-runner

[Repository Link](https://github.com/S545389/JavaWordCount.git)
