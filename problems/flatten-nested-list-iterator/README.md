<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    Openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

## 341. Flatten Nested List Iterator (Medium)

<p>Given a nested list of integers, implement an iterator to flatten it.</p>

<p>Each element is either an integer, or a list -- whose elements may also be integers or other lists.</p>

<p><strong>Example 1:</strong></p>

<div>
<pre>
<strong>Input: </strong><span id="example-input-1-1">[[1,1],2,[1,1]]</span>
<strong>Output: </strong><span id="example-output-1">[1,1,2,1,1]
</span><strong>Explanation: </strong>By calling <i>next</i> repeatedly until <i>hasNext</i> returns false, 
&nbsp;            the order of elements returned by <i>next</i> should be: <code>[1,1,2,1,1]</code>.</pre>

<div>
<p><strong>Example 2:</strong></p>

<pre>
<strong>Input: </strong><span id="example-input-2-1">[1,[4,[6]]]</span>
<strong>Output: </strong><span id="example-output-2">[1,4,6]
</span><strong>Explanation: </strong>By calling <i>next</i> repeatedly until <i>hasNext</i> returns false, 
&nbsp;            the order of elements returned by <i>next</i> should be: <code>[1,4,6]</code>.
</pre>
</div>
</div>


### Related Topics
  [[Stack](https://github.com/openset/leetcode/tree/master/tag/stack/README.md)]
  [[Design](https://github.com/openset/leetcode/tree/master/tag/design/README.md)]

### Similar Questions
  1. [Flatten 2D Vector](https://github.com/openset/leetcode/tree/master/problems/flatten-2d-vector) (Medium)
  1. [Zigzag Iterator](https://github.com/openset/leetcode/tree/master/problems/zigzag-iterator) (Medium)
  1. [Mini Parser](https://github.com/openset/leetcode/tree/master/problems/mini-parser) (Medium)
  1. [Array Nesting](https://github.com/openset/leetcode/tree/master/problems/array-nesting) (Medium)