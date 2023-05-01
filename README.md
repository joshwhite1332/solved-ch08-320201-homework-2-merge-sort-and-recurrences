Download Link: https://assignmentchef.com/product/solved-ch08-320201-homework-2-merge-sort-and-recurrences
<br>
<strong>Problem 1: Merge Sort                                                                                                                                      </strong>

<ul>

 <li>Implement a variant of Merge Sort that does not divide the problem all the way down to subproblems of size 1. Instead, when reaching subsequences of length <em>k </em>it applies Insertion Sort on these <em>n/k </em></li>

 <li>Apply it to the different sequences from Problem 2 (from last homework) for different numbers of <em>k</em>. Add the computation times to the plots you had generated in Problem 2.</li>

 <li>How do the different values of <em>k </em>change the best-, average-, and worst-case asymptotic time complexities for this variant? Explain/proove your answer.</li>

 <li>Based on the results from (b) and (c), how would you choose <em>k </em>in practice? Briefly explain.</li>

</ul>

<strong>Problem 2: Recurrences                                                                                                                                     </strong>

Use substitution method, recursion tree, or master method to derive upper and lower bounds for <em>T</em>(<em>n</em>) in each of the following recurrences. Make the bounds as tight as possible. Assume that <em>T</em>(<em>n</em>) is constant for <em>n</em>≤ 2.

<ul>

 <li><em>T</em>(<em>n</em>) = 36<em>T</em>(<em>n/</em>6) + 2<em>n</em>.</li>

 <li><em>T</em>(<em>n</em>) = 5<em>T</em>(<em>n/</em>3) + 17<em>n</em><sup>1<em>.</em>2</sup>.</li>

 <li><em>T</em>(<em>n</em>) = 12<em>T</em>(<em>n/</em>2) + <em>n</em><sup>2 </sup>lg<em>n</em>.</li>

 <li><em>T</em>(<em>n</em>) = 3<em>T</em>(<em>n/</em>5) + <em>T</em>(<em>n/</em>2) + 2<em><sup>n</sup></em>.</li>

 <li><em>T</em>(<em>n</em>) = <em>T</em>(2<em>n/</em>5) + <em>T</em>(3<em>n/</em>5) + Θ(<em>n</em>).</li>

</ul>