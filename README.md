# Exercises: Strings and Conditionals

## Metadata

### Instructor Guide

This is two exercises in one.

## Introduction

In these exercises, you will work with multiple methods to test your understanding of strings and conditionals.

<!--This needs to be separated into 2 exercises.-->

## Exercise: Conditional NUnit

### Instructions
<!-- markdownlint-disable MD029 -->
1. Open [ExercisesConditional.sln](activities/08e-ExercisesConditional.zip).
1. Click Test > Run all Tests, and this will produce red results

![Figure 2.](https://aa-online.s3.us-west-1.amazonaws.com/htd-assets/csfd/csharp-lang-fundamentals//conditional_fail.png)

1. Open ConditionalExercises.cs.
1. Complete the following methods

Complete all five Conditional methods all expected conditions.

#### Automated Testing

When you click Test > Run all Tests, you are telling your IDE to find and run all of the automated tests associated with the project.

Automated testing is a valuable tool for keeping bugs out of your code.  Briefly, they are a way of codifying the expectation that given a certain input, the program will produce an expected output.  We will dive into how they work (and how to write your own!) later in the course, but for now they're a useful way of letting you get immediate feedback on whether or not you've correctly completed the exercises below.

#### AlmostNear

Given a non-negative number, return true if the number is within range of a multiple of the target.

#### PrintDocument

Given we have power, paper and ink level is above 10 return true, when we have no power, always return false

#### AllowedToParty

Given it's the weekend we are allowed to party, however if it's not the weekend, we can only party between 0-7

#### IsAllowedWithdrawal

Given a non-negative number, return true if amount does not exceed a balance of 200. If over drafts are allowed, accept the balance withdrawal

#### RollPassGo

Given a non-negative number, return true if roll is above 7 and below 12
<!-- markdownlint-disable MD024 -->
### Instructions

1. Open Exercises.sln
1. Open Test
1. Click Run All Test

## Exercise: String Exercise NUnit
<!-- markdownlint-disable MD029 -->
## Instructions
<!-- markdownlint-enable MD024 -->
1. Open [StringExercises.sln](activities/08e-Exercises-strings-statements.zip)
1. Click Test > Run all Tests, and this will produce red results

    ![Figure 2.](https://aa-online.s3.us-west-1.amazonaws.com/htd-assets/csfd/csharp-lang-fundamentals//conditional_fail.png)

3. Open StringExercises.cs
4. Complete the following methods
<!-- markdownlint-enable MD029 -->
### Left2

    Given a string, return a "rotated left 2" version where the first 2

### Standard Greeting

    Given a string, return a formatted string with the following format. "Hello world, my name is {input}!"

### Remove Vowels

    Given a string, return a string with words without vowels.

### Hidden Message

    Given two strings, a and b, return a string of the form long + short + long,
    with the long string on the outside and the shorter string on the inside.
    The strings will not be the same length, but they may be empty (length 0).

### SectionString

    Given a string, and a number, return a string from the x number of the end.
    So "Candy", 4, returns "andy". X must be less than the length of the string.
    String length must be greater than 1
<!-- markdownlint-enable MD029 -->
