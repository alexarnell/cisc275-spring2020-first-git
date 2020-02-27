# cisc275-fall2019-first-git
1. Create java files to make this code compile and run.

2. What five objects are created in the main?
  1. new ArrayList<Dog>
  2. new Dog("Fido", 4)
  3. new Dog("Fido", 3)
  4. new Dog("Alfie", 4)
  5. new Comparator<Animal>
  

3. Can you spot the Comparator constructor call? Where is the class definition for the Comparator?
The compator construtor is overridden in the Collections.sort call, and the definition is defined in java.util.Comparator