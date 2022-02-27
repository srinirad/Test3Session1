<br> 1.	Write a program to find sum of two fractions
	<br> void input(int \*num1, int \*den1, int \*num2, int \*den2);
	<br> void add(int num1,int den1, int num2, int den2, int \*num3, int \*den3);
	<br> void output(int num1, int den1, int num2, int den2, int num3, int den3);
	<br> input:
	<br> 1 4
	<br> 1 2
	<br> output:
	<br> 1/2 + 1/4 = 3/4

<br> 2.	Write a program to find the smallest of three fractions.
	<br> struct _fraction 
	<br> {
	<br>    int num,den;
	<br> };
	<br> typedef _fraction Fraction
	<br> Fraction input_fraction();
	<br> Fraction Largest_fraction(Fraction f1, Fraction f2, Fraction f3)
	<br> void output(Fraction f1, Fraction f2, Fraction f3, Fraction largest)


<br> 3.	Write a program find the nCr given n and r. 
	<br> int input_n_and_r(int \*n, int \*r)
	<br> int ncr(int n, int r);
	<br> void output(int n, int r, int result);

<br> 4. Write a program to evaluate a polynomial at a given point using horners method.
	<br> int input_degree();
	<br> float input_x();
	<br> void input_coefficients(int n, float a[n]);
	<br> float evaluate_polynomial(int float a[n], float x);
	<br> void out_put(int n, int a[n], float x, float result);
	<br> input:
	<br> 1 1 1
	<br> output:
	<br> 1+1\*x + 1\*x^2 at 1.000000 is 1.000000

	
<br> 5. write a program to find the index of the largest number in an array.
	<br> int input_size();
	<br> void input_array(int n, int a[n]);
	<br> int find_largest(int n, int a[n]);
	<br> void out_put(int n, int a[n], int largest);


<br> 6. Write a program to count the number of words in a string using strtok ( string.h)
	<br> void input_string(char *a);
	<br> int count_words(char \*string);
	<br> void output(char \*string, int no_words);
	<br> input:
	<br> hello world hello
	<br> 
	<br> output:
	<br> 3
	
<br> 7. Write a program to add two fractions.
	<br> struct _fraction 
	<br> {
	<br>    int num,den;
	<br> };
	<br> typedef _fraction Fraction;
	<br> int find_gcd(int a, int b);
	<br> Fraction input_fraction();
	<br> Fraction add_fractions(Fraction f1, Fraction f2)
	<br> void output(Fraction f1, Fraction f2, Fraction f3, Fraction sum)
	
<br> 8. Write program to add n fractions
	<br> struct _fraction 
	<br> {
	<br>    int num,den;
	<br> };
	<br> typedef _fraction Fraction;
	<br> int find_gcd(int a, int b);
	<br> Fraction input_fraction();
	<br> void input_in_fractions(int n, Fraction f[n]);
	<br> Fraction add_fractions(Fraction f1, Fraction f2);
	<br> Fraction add_n_fractions(int n,Fraction f[n]);
	<br> void output(int n, Fraction f[n], Fraction sum);

