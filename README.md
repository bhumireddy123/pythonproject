# pythonproject
# function to create acronym
def fxn(stng):
   
    # get all words
    lst = stng.split()
    oupt = ""
     
    # iterate over words
    for word in lst:
       
        # get first letter of each word
        oupt += word[0]
         
    # uppercase oupt
    oupt = oupt.upper()
    return oupt
 
 
# input string
inpt1 = "Computer Science Engineering"
 
# output acronym
print(fxn(inpt1))
 
# input string
inpt1 = "geeks for geeks"
 
# output acronym
print(fxn(inpt1))
 
# input string
inpt1 = "Uttar pradesh"
 
# output acronym
print(fxn(inpt1))
