Download Link: https://assignmentchef.com/product/solved-csci-570-homework3
<br>
<ol>

 <li>Suppose we define a new kind of directed graph in which positive weights are assigned to the vertices but not to the edges. If the length of a path is defined by the total weight of all nodes on the path, describe an</li>

</ol>

algorithm that finds the shortest path between two given points A and B within this graph.

<ol start="2">

 <li>For each of the following recurrences, give an expression for the runtime T(n) if the recurrence can be</li>

</ol>

solved with the Master Theorem. Otherwise, indicate that the Master Theorem does not apply.

<ul>

 <li><em>T</em>(<em>n</em>) = 3<em>T</em>(<em>n</em>/2) + <em>n</em><sup>2</sup></li>

 <li><em>T</em>(<em>n</em>) = 4<em>T</em>(<em>n</em>/2) + <em>n</em><sup>2</sup></li>

 <li><em>T</em>(<em>n</em>) = <em>T</em>(<em>n</em>/2) + 2<sup> <em>n </em></sup>− <em>n</em></li>

</ul>

<ul>

 <li><em>T</em>(<em>n</em>) = 2<em><sup>n</sup>T</em>(<em>n</em>/2) + <em>n<sup>n</sup></em></li>

 <li><em>T</em>(<em>n</em>) = 16<em>T</em>(<em>n</em>/4) + <em>n </em>+ 10</li>

 <li><em>T</em>(<em>n</em>) = 2<em>T</em>(<em>n</em>/2) + <em>nlogn</em></li>

</ul>

<ul>

 <li><em>T</em>(<em>n</em>) = 2<em>T</em>(<em>n</em>/4) + <em>n</em><sup>51</sup></li>

</ul>

<ul>

 <li><em>T</em>(<em>n</em>) = 0.5<em>T</em>(<em>n</em>/2) + 1/<em>n</em></li>

 <li><em>T</em>(<em>n</em>) = 16<em>T</em>(<em>n</em>/4) + <em>n</em>!</li>

</ul>

<ul>

 <li><em>T</em>(<em>n</em>) = 10<em>T</em>(<em>n</em>/3) + <em>n</em><sup>2</sup></li>

 <li>3. Suppose that we are given a sorted array of distinct integers A[1, …, n] and we want to decide whether there is an index i for which A[i] = i. Describe an efficient divide-and-conquer algorithm that solves this problem and explains the time complexity.</li>

 <li>4.We know that binary search on a sorted array of size n takes O(logn) time. Design a similar divide-and-conquer algorithm for searching in a sorted singly linked list of size n. Describe the steps of your algorithm in plain English. Write a recurrence equation for the runtime complexity. Solve the equation by the master theorem.</li>

 <li>5. Given n balloons, indexed from 0 to n − 1. Each balloon is painted with a num- ber on it represented by array nums. You are asked to burst all the balloons. If you burst the balloon i you will get nums[i − 1] × nums[i] × nums[i + 1] coins. Here left and right are adjacent indices of i. After the burst, the left and right then become adjacent. You may assume nums[−1] = nums[n] = 1 and they are not real therefore you cannot burst them. Design a dynamic programming algorithm to find the maximum coins you can collect by bursting the balloons wisely. Analyze the running time of your algorithm.Example. If you have the nums = [3,1,5,8]. The optimal solution would be 167, where you burst balloons in the order of 1, 5, 3 and 8. The array nums after each step is: [3,1,5,8] → [3,5,8] → [3,8] → [8] → [] And the number of coins you get is 3×1×5+3×5×8+1×3×8+1×8×1 = 167.6.Given a non-empty string str and a dictionary containing a list of unique words, design a dynamic programming algorithm to determine if str can be segmented into a sequence of dictionary words. If str =“algorithmdesign” and your dictionary contains “algorithm” and “design”. Your algorithm should answer Yes as str can be segmented as “algorithmdesign”. You may assume that a dictionary lookup can be done in O(1) time.</li>

</ul>




7.     A tourism company is providing boat tours on a river with n consecutive segments. According to previous experience, the profit they can make by providing boat tours on segment i is known as ai. Here, ai could be positive (they earn money), negative (they lose money), or zero. Because of the administration convenience, the local community requires that the tourism company do their boat tour business on a contiguous sequence of the river segments (i.e., if the company chooses segment i as the starting segment and segment j as the ending segment, all the segments in between should also be covered by the tour service, no matter whether the company will earn or lose money). The company’s goal is to determine the starting segment and ending segment of boat tours along the river, such that their total profit can be maximized. Design a dynamic programming algorithm to achieve this goal and analyze its runtime.