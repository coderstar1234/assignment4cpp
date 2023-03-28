<h1 align="center" >Prime Number Checker:-</h1>

- This program checks whether a given number is prime or not. A prime number is a natural number greater than 1 that is not a product of two smaller natural numbers.
<hr>
<h1 align="center" >How to Use:-</h1>

- Clone the repository or download the source code.
- Open the terminal or command prompt and navigate to the directory where the source code is located.
- Compile the source code using any C++ compiler, such as g++.
- Run the executable file with the number you want to check as a command-line argument.<hr>
bash
Copy code
g++ prime.cpp -o prime
./prime 7<hr>
<h1 align="center" >Algorithm:-</h1>

- To check whether a number is prime, the program uses a brute force approach. It divides the number by every natural number smaller than the square root of the number. If the number is divisible by any of these natural numbers, then it is not prime. Otherwise, it is prime.
<hr>
<h1 align="center" >Limitations:-</h1>

- This program has a few limitations:

- It can only check whether a single number is prime.
-  It does not provide a way to check a range of numbers or generate a list of prime numbers.
- The brute force approach is not efficient for very large numbers.
-  For large numbers, a more efficient algorithm, such as the Sieve of Eratosthenes, should be used.<hr>
<h1 align="center" >Contributing:-</h1>

- If you find any issues or have suggestions for improvements, feel free to submit a pull request or open an issue.
<hr>
<h1 align="center" >License:-</h1>

- This project is licensed under the MIT License - see the LICENSE.md file for details.
<hr>



