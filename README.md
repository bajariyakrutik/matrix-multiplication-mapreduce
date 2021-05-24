# matrix-multiplication-mapreduce
Here Matrix Multiplication using Hadoop MapReduce is implemented

### Steps for Execution ###

1. Start Hadoop System on your machine<br />
    *check if all the daemons have started using 'JPS' command*
2. Make Directory “MatrixMultiplication”. Make a directory “Input” in it. Add “M & N” File in the “Input” Directory that was created before.
3. Create a directory 'Classes' for storing the class files. Execute commands shown Below.
4. Create a Jar file using following commands:<br />
    *jar cvf MatrixMultiply.jar '/Classes/ '*
6. Now run the program using Hadoop<br />
    *hadoop jar 'your jar file path' MatrixMultiply /MatrixMultiplication/Input /MatrixMultiplication/Output*
7. Run cat command to view results stored in “/WordCountProgram/Output”<br />
    *hadoop dfs -cat /MatrixMultiplication/Output*
