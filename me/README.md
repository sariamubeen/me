# Ghulam Murtaza's Mathematician and Python Skills Portfolio

Welcome to my GitHub repository, where I showcase my skills as a mathematician and Python programmer. I hold a Ph.D. in [Your Field of Mathematics], and I'm passionate about using Python to solve complex mathematical problems.

## About Me

- **Name:** Ghulam Murtaza
- **Email:** you@me.com
- **LinkedIn:** [LinkedIn Profile](https://www.linkedin.com/in/ghulam-murtaza)
- **Website:** [Personal Website](https://www.ghulammurtaza.com)

## Academic Background

- **Ph.D. in [Your Field of Mathematics]**
  - [Name of University]
  - [Year of Graduation]
  
## Skills

### Mathematical Expertise

- [List your mathematical expertise, e.g., Number Theory, Linear Algebra, Differential Equations]
- Describe your research interests and notable contributions, if any.

### Programming Skills

- **Python**: I have a strong foundation in Python and have used it for a wide range of mathematical applications, including but not limited to:
  - Numerical simulations
  - Data analysis
  - Machine learning
  - Optimization

### Projects

- [List any significant projects you've worked on. Include links to the project repositories or relevant articles/blog posts.]
- For example: [Project Title](link-to-project)

## Code Examples

Here are a few code snippets showcasing my Python skills:

```python
# Example 1: Solving a quadratic equation
import math

def solve_quadratic(a, b, c):
    discriminant = b**2 - 4*a*c
    if discriminant > 0:
        root1 = (-b + math.sqrt(discriminant)) / (2*a)
        root2 = (-b - math.sqrt(discriminant)) / (2*a)
        return root1, root2
    elif discriminant == 0:
        root = -b / (2*a)
        return root
    else:
        return "Complex roots"

# Example 2: Calculate the Fibonacci sequence
def fibonacci(n):
    if n <= 0:
        return []
    elif n == 1:
        return [0]
    elif n == 2:
        return [0, 1]
    else:
        sequence = [0, 1]
        while len sequence) < n:
            next_value = sequence[-1] + sequence[-2]
            sequence.append(next_value)
        return sequence
