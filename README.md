# interview-question-basic-
#To find the Occurence of a character in a string
from collections import Counter 
  
# initializing string  
test_str = "hello world"
  
# using collections.Counter() to get count  
# counting e  
count = Counter(test_str) 
  
# printing result  
print ("Count of e in hello is : "
                       +  str(count['e'])) 
