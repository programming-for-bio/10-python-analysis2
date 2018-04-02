

## Assignment notebook 10.7

Your assignment is to apply a probabilistic model similar to the switchpoint model in notebook 10.6. You can either follow the instructions below to generate a model like in notebook 10.6, or if you are feeling ambitious, you can choose another example model implementation from the [examples section](http://docs.pymc.io/examples.html) of the pymc3 documentation. 

You task is to use `np.random` to generate data under a known distribution and then to apply probabilistic inference using pymc3 to fit a model for the parameters of your generative model. See notebooks 10.4 or 10.6 for good examples. 


### Instructions:

+ Fork the class repo and make a new notebook in the assignments dir named nb-10.7-{gh-username}.ipynb. 


+ Generate data into a dataframe called `data` using numpy and pandas. Your data *must be different* from what was used in the examples already. Choose different parameters. The intention here is that you will test how changing parameters changes the results. Play around with trying out several different values. 


+ Implement a model that is appropriate for the data you have simulated. This can be a simple regression model like in notebook 10.4, or a more complex one like in notebook 10.6. Choose something that is interesting to you. 


+ Fit your model, plot the trace, and print the summary. 


+ Using markdown, describe how closely your model predicted your generative parameters. Are your parameters within the 95% HPD interval? Do you think you ran the MCMC sampler long enough? Do you think anything went wrong? If so, what did you try to troubleshoot the problem? Did you seek help or answers?


+ Commit and push your completed assignment notebook and make a pull request. 