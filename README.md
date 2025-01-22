# :focus-visible CSS Incompatibility Bug

This repository demonstrates a common issue with the `:focus-visible` pseudo-class in CSS.  Older browsers lack support for this feature, which can result in inconsistent styling when elements receive focus.

## Bug Description

The `:focus-visible` pseudo-class aims to style elements only when their focus is visually apparent to the user.  However, this functionality is not universally supported across all browsers.

## Solution

The solution involves using a JavaScript fallback to detect focus and add the necessary styles conditionally.