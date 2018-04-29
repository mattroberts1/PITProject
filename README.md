# PITProject
Augmenting PIT mutation tester with new mutators

Added mutators: 

  ABS: switches sign of variables

  AOD: replaces arithmetic operation with each of its variables

  AOR: replaces each arithmetic operation with every other one

  OBBN: replaces bitwise operations (or, and, xor) with other ones

  ROR: replaces each relational operator with every other one

-To install, go to pitest folder and run mvn clean install -DskipTests -Dmaven.javadoc.skip=true -Dcheckstyle.skip

-mutator notes+tests contains basic test cases for each of the added mutators (to show that they're working, these don't test ever function of each mutator)
