# Building Megapolis
## City Planning using Optimization

Building a city from the ground up is not a radically new idea. After some online research, we found that a lot of countries have tackled the projects of building a city from the ground up. We decided to use Julia lang, along with some other Julia packages and optimization solvers to find out how to use optimization to solve the city planning problems. We modeled our project into three different parts, progressively built on top of each one. 

To see what and how we did it, clone this repository and run the julia notebook in the 'submission' folder.

Some packages that are needed:
1. Julia: To install a Julia IDE with a Julia notebook, installation can be found [here](https://juliacomputing.com/products/juliapro.html)
2. This model also required to install and purchase the Gurobi Solver, installation can be found [here](http://www.gurobi.com/products/gurobi-optimizer?utm_source=Google&utm_medium=CPC&utm_term=gurobi&utm_campaign=Brand_N.America_search&campaignid=193283256&adgroupid=51266130904&creative=207661204751&keyword=gurobi&matchtype=p&gclid=Cj0KCQjw5qrXBRC3ARIsAJq3bwosVYT_qA32sKDZ7zE0GMaHWBWUCVtgWTEAgWCK2sTYJm4pL0U5pfwaAmm9EALw_wcB)
3. After installed the two required packages, we also used some optimization and graphing library. To install, do:`Pkg.add("JuMP")`, `Pkg.add("Plots")`, and `Pkg.add("Images")` in the IDE or the jupyter notebook.

More questions about our project, please email any one of us at the email specified in the notebook.
