# ChatGPT: An Incapability for Generating Random Numbers


# Program Overview
This program generates random numbers in Python and attempts to measure their accuracy through three tests:

1. Uniform distribution test
2. Poker test with Chi-square test
3. Consecutive runs test

This program uses Python libraries such as NumPy, collections, Matplotlib, and scipy.stats.

# Test Descriptions

## Uniform Distribution Test
In the uniform distribution test, we use NumPy's random function to generate integer values between 0 and 9. We then use Matplotlib's histogram to determine whether the random integer values follow a uniform distribution.

## Poker Test with Chi-Square Test
The poker test involves dividing a long bit string into sub-sequences and checking whether each sub-sequence is random. In this program, we count sub-sequences of length 5 using the poker test and check whether their frequency matches the expected frequency using a Chi-square test.

## Consecutive Runs Test
In the consecutive runs test, we count the number of consecutive increasing and decreasing sequences in the random number array. Specifically, we count "up runs" when the next number is greater than the previous number, and "down runs" when the next number is less than the previous number.

# Usage
To run this program, please click 'Open in Colab' and run all cells.

This program uses threading to generate a sequence of random integers using the OpenAI GPT-3 API. The generated sequence is then used to perform three tests:

1. Uniform distribution test
2. Poker test with Chi-square test
3. Consecutive runs test

To use this program, follow these steps:

1. Set the `array_length` variable to the desired length of the sequence.
2. Replace `***` in `openai.api_key = "***"` with your own OpenAI API key.
3. Run the program.
4. The program will generate a sequence of random integers using the GPT-3 API, and then perform the three tests on the generated sequence.
5. The program will output the generated sequence, its length, and the results of the three tests.

Note: Please make sure to click "open in Colab" and run all cells to use this program.
