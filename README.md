# GenericCheckPointing

1) Uses Reflection, Dynamic Proxy, and Strategy pattern
2) This system allows conversion of objects into wire format. Uses Reflection concept to get the class information dynamically. 
3) The system works for new objects and serialization formats with minimal changes. 
4) Used Java, design patterns and ANT build tool.

Steps to execute:
1) To compile : ant -buildfile src/build.xml all

2) To execute: ant -buildfile src/build.xml run -Darg0=firstarg -Darg1=SECOND -Darg2=THIRD
