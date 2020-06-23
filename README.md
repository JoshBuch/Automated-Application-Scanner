# Important Instructions regarding this image

1. Add the urls which you want to test in the urls_to_test.txt file. (A sample URL has been already given for demonstration)
   (Copy and paste the whole url including the protocol)
2. ### Remove the '/' at the end of the url. 
3. Run the following commands in the directory where the given files are downloaded:  
   **docker build -t security_testing .**  
   **docker run -it -v $(pwd):/app "name of the docker build image"**