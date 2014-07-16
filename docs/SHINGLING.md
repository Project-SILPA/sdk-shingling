Usage
=====

### Note :
This module is still under development and this document presently shows only currently available utilities.

This module is dependent on Ngram module so please add project `https://github.com/Project-SILPA/sdk-ngram`
to the dependencies. 

#### Get shingling
```
        Shingling shingling = new Shingling();
        List<String> lst1 = shingling.wshingling("a rose is a rose is a rose", 2);  // W - default -> 2
        List<String> lst2 = shingling.wshingling("The quick brown fox jumps over the lazy dog");

```
The above function `shingling.wshingling` returns a list `List<String>` of shingles of given text.

#### Get module name and information
```
        Shingling shingling = new Shingling();
        String moduleName = obj.getModuleName();
        String moduleInforamtion = obj.getModuleInformation();
```

#### To run tests
Tests present at `/src/test/java/`

  - Select test to run
  - Right Click -> Run Test -> Run as Android Test

