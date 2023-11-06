# digitari
Solution for Digitari ML / Python Developer Tech Test

### How to set up environment and run application
- Please make sure to install all required packages using the requirements.txt file.
- Additionally, unzip the stanford-ner-4.2.0.zip file into the outermost directory. You can download this zip file from https://nlp.stanford.edu/software/CRF-NER.html by clicking on 'Download Stanford Named Entity Recognizer version 4.2.0'.
- Lastly please ensure Java installed on your machine and JAVAHOME is set in your environment variables. Change the java_path in line 12 of solution/utils.py if need be to ensure the Stanford model runs
- Run by activating the virtual environment, run 'python solution/api.py' in your terminal from the digitari_ directory (outmost directory) and send a GET request to http://127.0.0.1:5000/process_text along with your posted json (I used the postman app). 
- Feel free to take a look at my experiments folder where I code through some other methods before deciding on my solution.


To Note:
- The code does take a few moments to run.
- I am aware that there are improvements to be made and would appreciate the chance to discuss these during a meeting as well as go over my solution with you.
