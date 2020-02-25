<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](../check-if-n-and-its-double-exist "Check If N and Its Double Exist")
　　　　　　　　　　　　　　　　
[Next >](../tweet-counts-per-frequency "Tweet Counts Per Frequency")

## [1347. Minimum Number of Steps to Make Two Strings Anagram (Medium)](https://leetcode.com/problems/minimum-number-of-steps-to-make-two-strings-anagram "制造字母异位词的最小步骤数")

<p>Given two equal-size strings <code>s</code> and <code>t</code>. In one step you can choose <strong>any character</strong> of <code>t</code> and replace it with <strong>another character</strong>.</p>

<p>Return <em>the minimum number of steps</em> to make <code>t</code>&nbsp;an anagram of <code>s</code>.</p>

<p>An&nbsp;<strong>Anagram</strong>&nbsp;of a&nbsp;string&nbsp;is a string that contains the same characters with a different (or the same) ordering.</p>

<p>&nbsp;</p>
<p><strong>Example 1:</strong></p>

<pre>
<strong>Input:</strong> s = &quot;bab&quot;, t = &quot;aba&quot;
<strong>Output:</strong> 1
<strong>Explanation:</strong> Replace the first &#39;a&#39; in t with b, t = &quot;bba&quot; which is anagram of s.
</pre>

<p><strong>Example 2:</strong></p>

<pre>
<strong>Input:</strong> s = &quot;leetcode&quot;, t = &quot;practice&quot;
<strong>Output:</strong> 5
<strong>Explanation:</strong> Replace &#39;p&#39;, &#39;r&#39;, &#39;a&#39;, &#39;i&#39; and &#39;c&#39; from t with proper characters to make t anagram of s.
</pre>

<p><strong>Example 3:</strong></p>

<pre>
<strong>Input:</strong> s = &quot;anagram&quot;, t = &quot;mangaar&quot;
<strong>Output:</strong> 0
<strong>Explanation:</strong> &quot;anagram&quot; and &quot;mangaar&quot; are anagrams. 
</pre>

<p><strong>Example 4:</strong></p>

<pre>
<strong>Input:</strong> s = &quot;xxyyzz&quot;, t = &quot;xxyyzz&quot;
<strong>Output:</strong> 0
</pre>

<p><strong>Example 5:</strong></p>

<pre>
<strong>Input:</strong> s = &quot;friend&quot;, t = &quot;family&quot;
<strong>Output:</strong> 4
</pre>

<p>&nbsp;</p>
<p><strong>Constraints:</strong></p>

<ul>
	<li><code>1 &lt;= s.length &lt;= 50000</code></li>
	<li><code>s.length == t.length</code></li>
	<li><code>s</code> and <code>t</code> contain lower-case English letters only.</li>
</ul>

### Related Topics
  [[String](../../tag/string/README.md)]

### Hints
<details>
<summary>Hint 1</summary>
Count the frequency of characters of each string.
</details>

<details>
<summary>Hint 2</summary>
Loop over all characters if the frequency of a character in t is less than the frequency of the same character in s then add the difference between the frequencies to the answer.
</details>