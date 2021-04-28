# code-20210428-PradiptaSarkar

1 ) If the file is a large JSON data then divide the file as per acceptibility by the system using - 

    split -l <line number> <json-file-name>
  
    and divide large JSON data into number of chunks.
    
 2 ) Processing should be done on each chunks of JSON using iteration and save each chunk output in temporary file using "Pickle"
 
 3 ) After processing of each chunks of JSON , concatenate those temporary "Pickle" file into a dataframe
 
 4 ) Convert these data frame into JSON file and save it as final output file. 

