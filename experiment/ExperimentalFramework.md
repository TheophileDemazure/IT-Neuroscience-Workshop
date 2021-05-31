# Experimental Framework
## Paradigm
![image](https://user-images.githubusercontent.com/85118151/120214441-7e52a280-c202-11eb-8980-d08753c36b7e.png)
## Configuration
This framework support basic a stimuli presentation + behavioral measure within-subject:
-> Instruction
-> Fixation cross -> Image -> Question

It handles multiple paradigms:
2 conditions: oddball (distribution), random binomial conditions, balanced conditions
3 and more conditions: random conditions, balanced conditions

### Keys
It use left and right arrow to answer
Space bar to accept the answer 

### Installation
Add the script to the folder with your other experimentations
The stimuli should be in a folder stim like the N170 face and houses 

## Configuration:
  First, adjust the parameters in the 'Parameters dictionary'.
    Follow the comments. 
    Configure the conditions and number of trials
    Add the relative path to the stimuli folders (1 folder per condition)
    Set stimulus presentation parameters
    Enable/disable fixation cross, and configure if necessary
    Enable/Disable training trials 
      Add a folder with the stimuli used for the training
      
![image](https://user-images.githubusercontent.com/85118151/120214650-c7a2f200-c202-11eb-9fb5-3b0da908bf25.png)
![image](https://user-images.githubusercontent.com/85118151/120214662-cb367900-c202-11eb-83c7-ad734f6b3d59.png)

  Second, configure the scale 
    set item, range, choices...

![image](https://user-images.githubusercontent.com/85118151/120214694-d4bfe100-c202-11eb-9734-d5c5c771e055.png)

  Third, write the instructions
    write the instructions for the main experiment in the function 'show_instruction'

![image](https://user-images.githubusercontent.com/85118151/120214730-e1443980-c202-11eb-916f-663e7a4d8efb.png)

  if enabled write the instruction in the function 'show_instructions_training'
  
![image](https://user-images.githubusercontent.com/85118151/120214800-f3be7300-c202-11eb-92c7-9f7024508e58.png)


