# Assignment 2 - Improving The LFSR using classes

## Introduction

In this exercise, you will reimplement the LFSR using classes.

## Instruction

1. Use `gradle init` in order to create a new Gradle Java project
2. Implement all the required methods such that the `testLFSR` will work properly using the following two classes
  1. `LFSR.java` represents a single LFSR register and should contain all the required methods
  2. `Exercise2.java` which represents the encoding itself and contains static and the main methods
3. The algorithm should use a combination of 10 LFSRs. Make sure to use an array of LFSR objects intend of a two-dimensional array
4. The LFSR class should have a constructor accepting a seed and coefs
5. The Exercise2 class should contain a constructor accepting an array of LFSRs.
6. Make sure to assign the correct visibility modifiers to all methods and fields of the two classes
7. Add a default constructor to the Lfsr class which initializes the seed and coefs using the Random class
8. Create a main method in Exercise2 which uses an init method which returns a new Exercise2 instance, which uses 10 Lfsrs initialized by their default constructors. The main method should use the init
   and run `testLFSR` correctly
