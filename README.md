Project Description:

In the world of programming, abstraction allows us to encapsulate shared characteristics while enabling unique behavior among different classes. 
This code snippet demonstrates a simple system to model various animals and their distinct attributes, focusing on their sounds and natural habitats. 
The code defines an abstract base class Animal with common properties for all animals, including name and species. 
This class also contains methods to define sound, habitat, and a general info method to represent the animal’s basic details. 
From Animal, three subclasses are derived: Mammal, Bird, and Reptile. These subclasses extend the Animal class and implement their unique sounds and habitats, reflecting the common characteristics of these broader categories. 
Further, specific animal classes are created to represent individual species: Elephant for mammals, Parrot for birds, and Snake for reptiles. 
Each of these classes overrides the sound and habitat methods to reflect their unique traits. For instance, elephants are known for trumpeting and inhabit savannahs or forests, while parrots mimic sounds and are found in tropical rainforests. 
To bring it all together, the show_animal_info function takes a list of animal instances and prints their information, including name, species, sound, and habitat. The code snippet then creates instances of these specific animal classes and demonstrates the use of the show_animal_info function to display their characteristics. 
This simple yet robust structure allows you to easily add more animal species by extending the appropriate subclass and defining the unique behaviors of each. It serves as a great starting point for modeling various animal behaviors and their natural habitats in a structured way.

