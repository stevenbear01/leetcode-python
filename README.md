# LeetCode Python Solutions

This repository contains solutions to various LeetCode problems implemented in Python. The solutions are organized by difficulty level: easy, medium, and hard.

## Project Structure

```
leetcode-python
├── solutions
│   ├── easy
│   │   └── two_sum.py
│   ├── medium
│   │   └── longest_substring.py
│   └── hard
│       └── merge_k_lists.py
├── tests
│   ├── test_two_sum.py
│   └── __init__.py
├── requirements.txt
├── pyproject.toml
├── .gitignore
└── README.md
```

## Setup Instructions

1. Clone the repository:
   ```
   git clone <repository-url>
   cd leetcode-python
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage

- To solve the two-sum problem, use the `two_sum` function defined in `solutions/easy/two_sum.py`.
- To find the length of the longest substring without repeating characters, use the `longest_substring` function in `solutions/medium/longest_substring.py`.
- To merge k sorted linked lists, use the `merge_k_lists` function in `solutions/hard/merge_k_lists.py`.

## Running Tests

To run the tests, use the following command:
```
pytest tests/
```

## Contributing

Feel free to submit pull requests for any improvements or additional solutions!