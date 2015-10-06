### SFPC: Generative Text - UNIX shell text-processing 

Transform a text to a poem utilizing UNIX command line processing tools.  
The text from https://abc.xyz/ was used with this chain of commands:

```
cat abc.xyc.txt | grep 'Alphabet' | cut -d' ' -f 1-4 | sort -r > poem.txt
```

Generating this frightening poem:

#####What is Alphabet? Alphabet  
#####What could be better?  
####äSergey and I are  
#####Our company is operating  
#####For Sergey and me  
#####Alphabet is about businesses  
#####Alphabet Inc. will replace  
