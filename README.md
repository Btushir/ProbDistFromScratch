
# Probability Distributions from Scratch

This repository contains custom implementations of various probability distributions built entirely from scratch. The goal is to provide fundamental, step-by-step implementations to understand how these distributions work at a lower level without relying on statistical libraries.

## Table of Contents
- [About](#about)
- [Distributions Implemented](#distributions-implemented)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)

## About

Probability distributions play a crucial role in statistics and machine learning. This project provides a hands-on way to explore the mathematical underpinnings of probability distributions through Python. Each implementation covers the essential properties and methods (such as PDF, CDF, mean, variance, etc.) of each distribution.

## Distributions Implemented

- **Uniform Distribution**: Constant probability over a given interval.
- **Normal (Gaussian) Distribution**: Bell-shaped distribution that’s symmetric around the mean.
- **Binomial Distribution**: Models the number of successes in a sequence of independent experiments.
- **Poisson Distribution**: Describes the probability of a given number of events happening in a fixed interval.
- **Exponential Distribution**: Models the time between events in a Poisson process.
- **Beta Distribution**: A family of continuous probability distributions defined on [0, 1].
- **Gamma Distribution**: Generalization of the exponential distribution, often used in Bayesian analysis.

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/your-repository-name.git
   ```
2. **Navigate to the Folder**:
   ```bash
   cd your-repository-name
   ```
3. **Install Dependencies**:
   Ensure you have Python 3 installed, along with any dependencies listed in `requirements.txt`:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

Each distribution is implemented as a Python class, which can be imported and used to create distribution objects. Each class contains methods for calculating the probability density function (PDF), cumulative distribution function (CDF), mean, variance, and other essential properties.

Example:
```python
from distributions import NormalDistribution

# Instantiate a normal distribution with mean 0 and standard deviation 1
normal_dist = NormalDistribution(mean=0, std_dev=1)

# Calculate PDF and CDF at a specific value
pdf_value = normal_dist.pdf(0)
cdf_value = normal_dist.cdf(0)

print("PDF:", pdf_value)
print("CDF:", cdf_value)
```

## Examples

Check the `examples` folder for Jupyter notebooks demonstrating usage and visualization for each distribution.

## Contributing

Contributions are welcome! If you'd like to add more distributions, improve the code, or fix any issues, please open an issue or submit a pull request.

### Steps to Contribute
1. Fork this repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to adjust any details or add additional sections based on the specifics of your project. Let me know if there’s anything else you’d like to include!