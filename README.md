# part-iii-essay
My Part III Essay on Safe Screening Rules.

Brief, 'easy-to-read' summary of the focus of this essay:

<ul>
  <li> The linear model is the canonical example of a statistical model. It is ubiquitious in statistics, econometrics, finance, and many other fields. </li>
  <li> There has been an explosion of data in recent years. This has led to the linear model being applied in high-dimensional settings. However, the linear model does not perform well in such settings.</li>
  <li> A popular adaptation of the linear model, which is particularly suited for high-dimensional applications, is the Lasso. The Lasso is able to produce SPARSE solutions - solutions with many components equal to zero. This can be viewed as 'automatic' feature selection: the Lasso can select important variables for you, offering the practicioner a smaller, more manageable subset of features to work with. </li>
  <li> My essay is focused on speeding up the computation of Lasso solutions using so-called 'safe screening' techniques. </li>
  <li> These rules aim to identify - AHEAD OF TIME - features whose corresponding components will be zero in the Lasso solution. Once we've identified these features, we can remove them from the problem and solve a smaller problem - which can be done more quickly. </li>
  <li> As a secondary focus, I explore applications of the safe screening technique to other (convex) learning problems with sparsity-promoting penalties. </li>
<ul>
