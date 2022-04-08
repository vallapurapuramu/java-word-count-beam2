# java-word-count-beam2

```
Step1: Get into the folder where we want create the project and run the following command
 ```       
         mvn archetype:generate `
 -D archetypeGroupId=org.apache.beam `
 -D archetypeArtifactId=beam-sdks-java-maven-archetypes-examples `
 -D archetypeVersion=2.36.0 `
 -D groupId=org.example `
 -D artifactId=word-count-beam `
 -D version="0.1" `
 -D package=org.apache.beam.examples `
 -D interactiveMode=false
 ```
 It will create the project folder the run the following command "cd .\word-count-beam"
 
 Step2: If we are using maven run the follwoing command 
 ```
 mvn compile exec:java -D exec.mainClass=org.apache.beam.examples.WordCount `
 -D exec.args="--inputFile=sample.txt --output=counts" -P direct-runner
 ```
 Step3: once we complile the code we are able to produce the results successfully

```
![image1](https://github.com/vallapurapuramu/java-word-count-beam2/blob/main/Screenshot%20(110).png)
