# seating-chart-algorithm

Command to run algorithm (at least on Windows, but it's most likely similar in other environments. I'm not an expert):

  java -jar Algorithm.jar chartFile.json employeeFile.json similarityFile.json DesiredOutputFile.json

If the program runs successfully, the output file specified by the fourth argument will be created. 

Test files:

  c32.json, c64.json, and c250.json are chart files for offices with 32, 64, and 250 desks, respectively.

  e32.json, e64.json, and e250.json are employee files with 32, 64, and 250 employees, respectively.

  s32.json, s64.json, and s250.json are similarity files with 32, 64, and 250 employees, respectively.

DisplayChart.jar can be used to display JSON files that Algorithm.jar outputs:

  java -jar DisplayChart.jar OutputFile.json
