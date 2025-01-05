# Tailwind JIT Mode: Conflicting CSS Rules and Unexpected Overrides

This repository demonstrates a common issue encountered when using Tailwind CSS's Just-In-Time (JIT) mode.  The problem arises from conflicting or ambiguously structured CSS rules that lead to unexpected style overrides, even when specificity appears correct.

The `bug.css` file shows the problematic code.  The `bugSolution.css` file offers solutions to address the conflict.

**Key issue:** JIT compilation orders can affect how classes are applied, potentially leading to unexpected overrides.  Careful ordering and structured CSS are essential for preventing such errors. 