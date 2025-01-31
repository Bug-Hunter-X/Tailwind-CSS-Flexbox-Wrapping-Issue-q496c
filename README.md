# Tailwind CSS Flexbox Wrapping Issue

This repository demonstrates a common issue encountered when using Tailwind CSS's flexbox utilities: items not wrapping to the next line when there is insufficient horizontal space.  The problem arises from the default `flex-nowrap` behavior of the `flex` utility.

The `bug.html` file showcases the problematic code. The `bugSolution.html` file provides a corrected version using the `flex-wrap` utility to enable wrapping.

## Problem

When using `flex` without specifying `flex-wrap`, Tailwind defaults to `flex-nowrap`. This prevents items from wrapping onto the next line, resulting in horizontal overflow.

## Solution

Adding the `flex-wrap` utility class resolves the issue, allowing items to wrap to subsequent lines when necessary.