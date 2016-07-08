## Steps for working with a new data set

### 1. Make sure files are in the same directory that the code is referencing
* Look at raw file if possible
** Are there numbers that should be read as character values, such as zip code?

### 2. Read in and Examine file
* object.size() If file is large, can read in limited rows with argument nrows =
* str()
* summary()
* look for how missing values are noted (blankes, "N/AV", etc.)
* Note if character columns should be converted into logical when reading in file.
* making scatter plots using plot() can help.

### 3. Decide on process

### 4. Examine formulas separate from function to make sure they work the way anticipated and if not, figure out how to make them do what is desired.

### 5. Check at every line of code to make sure to make sure it is doing what is wanted....Just because it runs does not mean it is running the intended way.


### 6. See if it can be optimized.