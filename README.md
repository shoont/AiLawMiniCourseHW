# AiLawMiniCourseHW
SUPREME COURT TOPIC MODELING

> Step 1: This step imports the plug ins necessary to manipulate the data. Then it downloads the data to be analyzed to the program. It then redifines the data in to strings that allow teh cases to be more easily categorized by the program. Finally, it moves all of the new data into a easily manipulated data set known as a pickle. 

> Step 2: This step begins Manipulating the Data with teh tensorflow program in order for the data to be categorized. 

> Step 3: This step then takes the previously manipulated data, and begins imposing perameters on the data sets in order to output the data into a readable format. It does this by identifying which justices decided which decision. 

> Step 4: This step takes steps 2 and 3 and begins calculating which perameters are important in the data set. It uses a graphical data model in order to output the data into a readable graph which is done in step 5. 

> Step 5: This step graphically organizes the data for output. It uses the parameters from the previous program inputs and then uses the perameteres to output the data using the tensorflow program. 

Word2Vec Analysis

> Step 1: This step downloads the data necessary to run the tensorflow program through the data set. In this case the data set is an explanation of data compression programs. In this step the python program first identifies that there is data to be downloaded. It then places the files in a local path so the machine can find the data after it is downloaded. The program then reports the statistics of that data set to the machine. The program then reads the data into strings to make it more usable to the program. When doing this, it also compresses the data in order to run the program more efficiently. 

> Step 2: This step then takes the string data and replaces rare words with tokens, here defined as UNK, in order to make the program run more efficiently. This allows the machine to then create a dictionary of the words that are most common. This allows the machine to calculate how frequently words are most used. It then counts the words in each string and returns the count to the data set that is dictated. The program then deletes the vocabulary, which is the read out data file, in order to reduce space on the machine. The program then prints out counts of the most common words, as well as, the words that were identified. 

> Step 3: The program then uses the data collected from these strings the create a batch, or model, to create a model which will later be used to train the algorithm. It does this by identifying the count of each word, then calculating the words that are most frequently used near each other in order to calculate the frequency of the words usage together. The program does this calculation by identify how many skips, or words, are between the use of the word identified limited at 2. This allows the machine to identify that a word used at most two words before or after the word which the program has identified as being used together. 

> Step 4: This step builds and trains the machine learning algorithm. It identifies the size of the batch, as well as identifies how many skips, windows, and samples the machine should use before drawing its conclusion. The skip_window identifies how many skips the machine should calculate at one time. The num_skips identifies how many times the machine should repeat the calculation. The num_sampled identifies to total number of samples the machine should use before ending the program. Finally, the code calls for the out put to be placed into a graphical output. The code also calls for a calculation of the number of loss, or the number of words that were tokenized out of the program at each level to help the user identify the accuracy of the programs output. The code then inputs the data used into the tensorflow program in order for it to being running. 

> Step 5: This step begins the running the tensorflow program through the data set, and identifies minimum values for all the outputs. It then places calculations of each step into a variable which can be outputted by the program. Finally, this step then identifies how many times the program will be computed before the program ends. 

> Step 6: This step identifies how the calculation should be outputted. This allows the program to visually output the calculations into a graphical format. In order for my program to output the calculations into a graphical format, I needed to run the magic key %matplotlib in a kernel before running the tensorflow program.
 
