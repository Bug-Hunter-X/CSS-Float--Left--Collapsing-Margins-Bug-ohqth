# CSS Float: Left; Collapsing Margins Bug

This repository demonstrates a common issue in CSS related to collapsing margins when using the `float: left;` property. The bug manifests as unexpected layout inconsistencies across different browsers, primarily due to the way browsers handle margin collapsing.

The `bug.css` file contains the problematic code, while `bugSolution.css` provides a corrected version that addresses the margin collapsing issue using techniques such as `overflow: hidden;` or clearfix methods.