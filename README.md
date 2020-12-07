# Block-search-method
Fullsearch, 3SS, 4SS, HexBM, and DiamondBM<br />

Evaluate 5 distinct block-matching algorithms: Fullsearch, 3SS, 4SS, HexBM, and DiamondBM. In each case, the image table is already generated although your solution should work for any size numpy array. The scores in the table represent grayscale image values. <br />

Each evaluation algorithm will use the image table.  Use the score cell as the starting center: (8,8), although this should be programmable or used as default to select the center of an NxN size image array.<br />

Full Search - Use the center of in each round to find the best value in a 7x7 area surrounding query point. Code Full Search as a BxB location (assume it can be centered by B being odd valued).<br />

Full Search	Use the center of in each round to find the best value in a 7x7 area surrounding query point. Code Full Search as a BxB location (assume it can be centered by B being odd valued).<br />		

3SS (3 Stage Search) - Use the center of in each round to find the best value.<br />	

4SS (4 Stage Search) - Use the center of in each round to find the best value.<br />

HexagonBM- Use the center of in each round to find the best value.<br />

Diamond- Use the center of in each round to find the best value.<br />
