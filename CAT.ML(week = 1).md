
## Machine Learning Questions
1. Define machine learning; what are the differences between machine learning and normal programming?

2. There're 4 types of machine learning:
	-   Supervised Learning.
	-   Unsupervised Learning.
	-   Semi-Supervised Learning.
	-   Reinforced Learning. 

	$\Rightarrow$ Compare two of them, at least, to each other.

3. Clustering is _______________ , and Classification is _______________ :


	|    Clustering    |  Classification  |
	|------------------|:---------------:|
	| <input type="checkbox" /> Supervised   |<div style="text-align: left"> <input type="checkbox"/> Supervised </div> |
	|<input type="checkbox" /> Unsupervised |<div style="text-align: left"><input type="checkbox" /> Unsupervised</div> |
	| <input type="checkbox" /> Reinforced   | <div style="text-align: left"><input type="checkbox" /> Reinforced </div>  |

*note: Answers need to be `checked` in the `<input/>` tag in source code, just edit it to be `<input ... checked/>`*

4. What is Gradient Descent? Do you know any other thing similar to it?

5. You're approximating a function $f(x) = wx+b$, you have the data points $\textbf{x}$.
	1. What is $w$?
	2. What is $x$?
	3. What is $b$?
	4. Why is $\textbf{x}$ written in bold-face in the question, what does it mean?
	5. How are you planning to get the values of $w, b$?

6. $w:=w - \alpha \frac{1}{m}\sum_{i =1}^{m}(f_{w, b}(x^{(i)} )- y^{(i)}) x^{(i)}$
	1. What is $\alpha$?
	2. What is $m$?
	3. What is $y$?
	4. What does the summation compute?


## *Bonus* NumPy Questions

1. What does `np.cumsum` calculate?

2. What do `np.argmin` and `np.argmax` calculate?

3. How to rotate a matrix $90 ^{\circ}$?

4. What do `np.arange` and `np.newaxis` do?
	```
	data = np.arange(0, 5)
	column = data[:, np.newaxis]
	```

5. What's the difference between `np.flatten` and `np.ravel`?

6. 
	```
	 A = np.linspace(0, 1, 11)
	 A[[0, 2, 4]]
	```
	
	```
	A = np.linspace(0, 1, 11)
	A[0: 2: 4]
	```
	$\Rightarrow$ What does each return? And why?