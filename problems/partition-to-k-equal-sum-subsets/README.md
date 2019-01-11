<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    Openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

## 698. Partition to K Equal Sum Subsets (Medium)

<p>Given an array of integers <code>nums</code> and a positive integer <code>k</code>, find whether it&#39;s possible to divide this array into <code>k</code> non-empty subsets whose sums are all equal.</p>

<p>&nbsp;</p>

<p><b>Example 1:</b></p>

<pre>
<b>Input:</b> nums = [4, 3, 2, 3, 5, 2, 1], k = 4
<b>Output:</b> True
<b>Explanation:</b> It&#39;s possible to divide it into 4 subsets (5), (1, 4), (2,3), (2,3) with equal sums.
</pre>

<p>&nbsp;</p>

<p><b>Note:</b></p>

<ul>
	<li><code>1 &lt;= k &lt;= len(nums) &lt;= 16</code>.</li>
	<li><code>0 &lt; nums[i] &lt; 10000</code>.</li>
</ul>


### Related Topics
  [[Recursion](https://github.com/openset/leetcode/tree/master/tag/recursion/README.md)]
  [[Dynamic Programming](https://github.com/openset/leetcode/tree/master/tag/dynamic-programming/README.md)]

### Similar Questions
  1. [Partition Equal Subset Sum](https://github.com/openset/leetcode/tree/master/problems/partition-equal-subset-sum) (Medium)

### Hints
  1. We can figure out what target each subset must sum to.  Then, let's recursively search, where at each call to our function, we choose which of k subsets the next value will join.