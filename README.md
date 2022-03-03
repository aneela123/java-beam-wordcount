# java-word-count-beam
## My Name: Jahna Sri Aneela Ankam

## Commands and links I have used

## Links: Java Quickstart : - <https://beam.apache.org/get-started/quickstart-java/>

## Steps:

1. From the 44517 folder in my system I have created the folder(java-word-count-beam) as mentioned in the instructions.
2. Executed the commands in ps as Admin from the quickstart link mentioned above.
3. Commands I have used in the Ps are:
4. To run the pipeline:
   - mvn compile exec:java -D exec.mainClass=org.apache.beam.examples.WordCount `
 -D exec.args="--inputFile=inputfile.txt --output=counts" -P direct-runner
   
   -To inspect the results:  ls counts*
5. Output will be generated in the words-count-beam root folder.
