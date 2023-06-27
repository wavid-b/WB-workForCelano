MakeDictCSVs - notebook with code to create the dataframes for functions
    Requires XML files in folder named "Raw_XML"
DictFunctions - has funcitonality of the data

In progress -
    Split the parses between greek and latin: they do not have a lang_id tag, so originally files created with them together
    
    Parse the part of speech information tags in parses

    Create better output than a list of words associated. Discuss options w/Celano
        make a "words" class with children for each part of speech. Have each word object have the complete parse and dictionary entry, as well as gender. Create the word objects for each ID, then fetch them from a table when a user needs it

        Create functions that do transformations using prexisting objects in python. This is a more simple approach, but may be more efficent as well. Encapsulation may be unnecessary here. 

    Create other functionalities as need (i.e. gender of input word, only output if certain part of speech)

