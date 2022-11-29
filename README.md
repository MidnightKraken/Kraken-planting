# Kraken-planting




This program will consist of multiple parts to solidify my understanding of ruby.

Overall goal - create a program that consist of a watering schedule for different plants. This will have a real time date associate with it that you can check and is will check if any of the plants in your list need to be watered that day. 

Example 
  - check schedule 
     - looks over list of current plants that are active in directory.
      Check unwatered plants  
      - list off plants that need to be watered. 
       - checks current date and previous  14 days of plants needing a status update. (watered yes/no?)
        - if plant is not watered, request user input
- if plant is dead retire to graveyard. 

This will require a directory of plants
 - each plant will have a set interval of days that it needs to be watered. Once the amount of days hits it is added to a unwatered category. 


Expert goals 
  - have an age/water amount factor that can change the watering schedule based on plant ages. A sapling may require more frequent but less water for example. 
  
  


Questions for self
 - What happens when you are behind schedule? Should I reset the interval of days between water or always water that specific plant on the 15th and 25th instead of 10 days between watering. 
 - how to implement growth factors within the plant watering application 
     - this plan grows 2 inches every week?
 - Should The user have the  "ability" to create a plant? Type : succulent, ivy, orchid, tree. age = weeks/ years. required watering = varies
