# debug
getAddend: Originally checked if object did not exist and then used it if it did not exist, changed it to work as intended where object must exist
times: products were not being added to the productList, changed so they are
main: generic vars could return errors if not typecast correctly, changed vars to be the correct type
Using the test document and by reading the given code I was able to figure out the what the purpose of each method was.
From there I read line by line to pick up on any errors in syntax or order, which is where I found the error in getAddend, which just had two statements in opposite order.
Then, I looked for any missing functionality, which is how I found the error in times, which is missing a step that is referenced in the method code.
Finally, I checked for function dependencies(?), which is how I found that the variables in main were not typecast correctly.
