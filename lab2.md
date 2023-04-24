# **Lab Report 2 - Servers and Bugs (Week 3)**

## Part 1
Code for `StringServer.java`:
![Image](StringServer.png)

![Image](labreport2first.png)
- The methods in the code that were called are 
![Image](labreport2second.png)



## Part 2
The method I used for this part was reverseInPlace in the `ArrayExamples.java` and tested in `ArrayTests.java`

Failure-inducing input for buggy program
```
@Test 
public void testReverseInPlaceManyInts() {
  int[] input1 = {0,1,2,3,4,5};
  ArrayExamples.reverseInPlace(input1);
  assertArrayEquals(new int[]{5,4,3,2,1,0}, input1);
}
```

```
@Test 
public void testReverseInPlace() {
  int[] input1 = {99};
  ArrayExamples.reverseInPlace(input1);
  assertArrayEquals(new int[]{99}, input1);
}
```

![Image](ArrayExamplesTest.png)

## Part 3
Something that I learned in week 2 was how to use Github Desktop and the different uses for it. I did not know that GitHub had a feature like this. Because of this, it allows me to work on the lap reports I put on the GitHub from my laptop and desktop at home without having to transfer over files since it is all saved in my GitHub repository. After this class, I can see myself using this a lot.
