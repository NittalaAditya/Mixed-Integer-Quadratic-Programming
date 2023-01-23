# Problem Overview

One of the most common problems in predictive analytics is variable selection for regression.
Direct variable selection using optimization has long been dismissed by the statistics/analytics
community because of computational difficulties. This computational issue was part of the
motivation for the development of LASSO and ridge regression. However, in the recent past
there have been tremendous advancements in optimization software, specifically the ability to
solve mixed integer quadratic programs (MIQP). This project will pose the variable selection
problem for regression as an MIQP which you will solve using gurobi. You will compare the
results you find to LASSO to see if the additional ‘shrinkage’ component of LASSO really is more
beneficial than finding the ‘best’ set of variables to include in your regression.

Pretend that you are a junior consultant at an analytics consulting firm. You frequently
use LASSO in your job, but your boss has heard that the computational time of direct
variable selection has decreased with the advent of better solvers. Your boss wants you
to figure out if the firm should shift away from using LASSO to incorporate more direct
variable selection. Write this project as if this is what you’re going to deliver to your
boss. Describe the advantages and disadvantages of both techniques. Your boss is
pretty technical and understands optimization, so don’t be afraid to include quantitative
material. Your boss is also busy, so be sure to include some visualizations to get the
important points across. For the purpose of your report, you can assume that your boss
is interested in the data posted with the project.
