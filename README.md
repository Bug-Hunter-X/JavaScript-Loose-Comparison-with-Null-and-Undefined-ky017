# JavaScript Loose Comparison with Null and Undefined

This repository demonstrates a common JavaScript bug related to loose comparison (`==`) with `null` and `undefined` values.  The issue arises because of JavaScript's type coercion during loose comparisons, which can lead to unexpected results. The provided example showcases the problem and its solution using strict comparison (`===`).

## Bug Description

The `bug.js` file contains a function that attempts to handle `null` input values using a loose comparison. However, due to type coercion, the comparison doesn't always behave as intended, leading to errors in certain scenarios.  The `bugSolution.js` file provides a corrected version that uses strict comparison to avoid this issue. 