# Common Sense Epidemiology

## Okay, so what numbers should I use to make decisions?

Active cases / population

Why?

This metric has a number of useful properties:

- It reflects what the situation is right now
- It gives you a practical answer to the most important question: "What is the percent chance that a random person I pass on the street is sick?"
- You can make valid comparisons between areas of different size
- By looking at the history of this metric, you can see if things are getting better or worse

## A hypothetical town

Let's imagine a hypothetical (large) town called Smithville. This town very conveniently has _exactly_ **100,000** residents. This will be our testing ground for most of the following scenarios

## Why 'active cases' matters more than 'total cases'

**Total cases** is the number of people who have _ever_ been sick. This includes currently active cases, people who have recovered, and people have died. It is not a very useful number for decision-making of any kind. Here's why:

Let's take Smithville, and its neighbor Jonesville, also with a population of _exactly_ **100,000** residents. You need to go food shopping, so you look up the towns' total case numbers. Smithville has had 20,000 total cases, and Jonesville has had 80,000 total cases. Which one is safer right now? The answer is "it depends".

We could imagine the following timeline of new cases:

| Town        | Week 1 | Week 2 | Week 3 | Week 4 | Week 5 | Week 6 | Week 7 | Week 8 (present) |
| :---------- | :----- | :----- | :----- | :----- | :----- | :----- | :----- | :--------------- |
| Smithsville | 100    | 100    | 100    | 200    | 400    | 1,000  | 2,000  | 16,000           |
| Jonesville  | 4,000  | 8,000  | 16,000 | 32,000 | 14,000 | 1,500  | 1,000  | 500              |

So Smithsville actually has **32 times** the number of active cases, while having only **1/4** the total case numbers.

## Why dividing by population size matters

Smithsville has a neighboring town Tinyville. This town has a population of only 10,000, and an area one-tenth the area of Smithsville. We look up the active case numbers, and both Smithsville and Tinyville have 2,000 active cases. Is each town equally dangerous? **No.** 2% of Smithsville residents are sick, but 20% of Tinyville residents are sick. So if you

## Why the ratio of positive test results to negative test results doesn't really matter

There is a lot of talk in the news of what percentage of tests are coming back positive. But this at best a distraction, and at worst misleading. Here's why.

### Increased testing decreases this percentage

Let's imagine that in Smithville, there are 2,000 people actively sick. It is important to note this is a number we "magically" know. In reality, we never actually know this real number. But we can use testing and statistics to make better and better guesses at it.

So there are 2,000 people actively sick. We are running 10,000 tests. We happen to test all 2,000 actively sick people, and an additional 8,000 healthy people. What percentage of tests come back positive? **20%**

100,000 citizens
10,000 tests
2,000 positive results

100,000 citizens
50,000 tests
2,000 positive results

### Sick people receive follow-up tests

There are other factors that can impact this number. In general, people who test positive will be tested again, and people who test negative will not. So that skews the number higher. To use a simple example, let's imagine we are running a testing center. 10 people come to be tested. 2 of them are sick. We follow up with the positive results, to see how long they remain active cases. Let's imagine both of those people return four more times with positive results, followed by one more time with a negative result. So the complete timeline is this:

| Patient | Test 1 | Test 2 | Test 3 | Test 4 | Test 5 | Test 6 |
| :------ | :----- | :----- | :----- | :----- | :----- | :----- |
| 1       | -      |        |        |        |        |        |
| 2       | -      |        |        |        |        |        |
| 3       | -      |        |        |        |        |        |
| 4       | -      |        |        |        |        |        |
| 5       | -      |        |        |        |        |        |
| 6       | -      |        |        |        |        |        |
| 7       | -      |        |        |        |        |        |
| 8       | -      |        |        |        |        |        |
| 9       | +      | +      | +      | +      | +      | -      |
| 10      | +      | +      | +      | +      | +      | -      |

Notice the huge rectangle of blank space here. These are tests that _would_ have happened if patients 1-8 had tested positive during Test 1, but they didn't, so those tests didn't need to be run.

Now we have a total of 10 tests with negative results, and 10 tests with positive results. So now our percentage of tests that come back positive is 10/(10+10), or 50%. But the true number of active cases was only 20% of the active population.

If the active cases had received more tests (remaining sick for longer, and/or being tested more frequently), the percentage of tests coming back positive would have increased, and vice versa with receiving fewer tests.

## Why the death rate looks low while things are growing rapidly

## What surveillance testing is

## How testing works: a hypothetical
