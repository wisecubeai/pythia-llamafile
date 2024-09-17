# pythia-llamafile
Run your own OpenAI API locally. Tested to work on Mac OS X & Linux. 

:eyes: ***build***:
  - make sure you have docker installed
  - clone this repository
  - build the image
```
docker build -t pythia-llamafile .
```

:eyes: ***run***:
```
docker run -d -p 8080:8080 pythia-llamafile
```
:eyes: ***UI Test***:  
  - go to http://127.0.0.1:8080
  - say 'hello'! 

:eyes: ***API Client***:  
  - set base_url="http://localhost:8080/v1"
  - run your existing OpenAI client 

