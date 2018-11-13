# GroupMessenger
A group messenger which multicasts messages to the group and maintains Total-FIFO ordering even in the case of failure using ISIS algorithm.

## Aim
• Implement a FIFO total ordering algorithm.  
• Detect and handle failure of a single messenger instance.

## Running and Testing the Project
• The grading script is used to test the correctness of the program  
• Create avds: create_avd.py <number of avds to create>  
• Run the avds: run_avd.py <number of avds to run>  
• start the emulator network by running set_redir.py 10000  
• Test the application by running the grading script and pass the apk file to it.  
  
Refer to the GroupMessenger.pdf for any details and further implementation  
  
