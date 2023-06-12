# Approximation-of-Area-under-the-cuve-
Numerical integration is a commonly used technique in applied mathematics and engineering for approximating the value of a definite integral using a numerical method. The Newton-Cotes formula is a family of numerical integration methods that use equally spaced points to approximate the integral of a function. Mostly Trapezoidal rule, Simpson's 1/3 rule, and Simpson's 3/8 rule are widely used due to their simplicity and effectiveness.
The Trapezoidal rule approximates the area under a curve by dividing it into trapezoids. Simpson's 1/3 rule is a more accurate method that approximates the area under a curve by dividing it into parabolic segments, while Simpson's 3/8 rule approximates it by dividing the curve into cubic segments. Although Simpson's 3/8 rule is more accurate than Simpson's 1/3 rule, it requires the evaluation of the function at more points, making it computationally more expensive.
Simpson's 1/3 rule strikes a balance between accuracy and computational efficiency, making it the most widely used method for numerical integration. It requires the evaluation of the function at fewer points than Simpson's 3/8 rule while providing higher accuracy than the Trapezoidal rule. Hence, Simpson's 1/3 rule is considered the best of accuracy and efficiency over other methods, making it a popular choice in various fields of science and engineering.

# Trapezoidal Rule
The trapezoidal rule is a numerical integration method that approximates definite integrals. It divides the interval into trapezoids and sums their areas to estimate the integral. By approximating the function with straight line segments, it calculates the area of each trapezoid. The rule states that the integral is approximately equal to the interval width multiplied by the average of the function values at the endpoints. The accuracy depends on the number of trapezoids used. Although it has limitations with highly curved functions, the trapezoidal rule is widely used for its simplicity and reasonable accuracy in many applications.

# Simsons 1/3 Rule
Simpson's 1/3 rule is a numerical integration method used to estimate definite integrals with higher accuracy compared to the trapezoidal rule. It utilizes quadratic polynomials to approximate the function being integrated.
The rule divides the interval into subintervals and fits a quadratic polynomial to three points within each subinterval - the endpoints and the midpoint. The area under the quadratic polynomial represents the estimated integral for that subinterval.
Mathematically, for a function f(x) to be integrated over an interval [a, b], Simpson's 1/3 rule can be expressed as:
∫[a,b] f(x) dx ≈ (b - a) * [(f(a) + 4f((a+b)/2) + f(b)) / 6]
The formula calculates the average of the function values at the endpoints and the midpoint, multiplied by the width of the interval divided by 6.
Simpson's 1/3 rule is particularly useful when the function being integrated is relatively smooth or has an even degree. However, it requires an even number of subintervals to be applicable. It provides a more accurate approximation of definite integrals and is commonly employed in numerical analysis and scientific computing for its improved precision over the trapezoidal rule.

# Simpsons 3/8 Rule
Simpson's 3/8 rule is a numerical integration method used to estimate definite integrals with even higher accuracy compared to Simpson's 1/3 rule. It extends the quadratic polynomial approximation to cubic polynomials.
Similar to Simpson's 1/3 rule, the 3/8 rule divides the interval into subintervals. However, instead of using three points, it uses four points within each subinterval - the endpoints and two additional points evenly spaced between them. These four points are used to fit a cubic polynomial, which represents the estimated integral for that subinterval.
Mathematically, for a function f(x) to be integrated over an interval [a, b], Simpson's 3/8 rule can be expressed as:
∫[a,b] f(x) dx ≈ (b - a) * [(f(a) + 3f((2a+b)/3) + 3f((a+2b)/3) + f(b)) / 8]
The formula calculates the weighted average of the function values at the endpoints and the two additional points, multiplied by the width of the interval divided by 8. Simpson's 3/8 rule provides even higher accuracy, especially for functions with smooth curves or higher-degree polynomials. It is widely used in numerical analysis and scientific computing when more precision is required for definite integration approximations.

