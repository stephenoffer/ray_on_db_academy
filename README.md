# Ray on Databricks Academy - Tutorials on Ray and Ray-based Libraries

*This material is taken from the Anyscale Academy and has been modified to run on Databricks.*

## Getting Help

For Ray related technical questions, reach out to #help-ray on Slack

For account related questions, reach out to the #ray-gtm team

### Engineering
- Nitin Wagh (nitin.wagh@databricks.com)
- Mahesh Venkatachalam (mahesh.venkatachalam@databricks.com) 
- Ben Wilson (benjamin.wilson@databricks.com)

### Field Engineering
- Stephen Offer  (stephen.offer@databricks.com)
- Puneet Jain (puneet.jain@databricks.com) 

## Getting Ray Set Up on a Databricks Cluster

To get started with this course, please create a cluster with this configuration:

- Ray on Databricks currently only supports Single-Access mode clusters
- The init functions in this course are set to run with 2 worker nodes and 4 CPUs per node, so select a cluster with at least 2 workers and 4 CPUs available per node.
- Ray will be included in the Databricks Machine Learning Runtime (MLR) in Q1 of 2024, but if not using the latest MLR, please install using the Libraries panel, selecting PyPI as the source and installing 'ray[all]'

This cluster can be reused for all sections of this course.

## Which Tutorials Are Right for Me?

Here is a recommended reading list, based on your interests:

| You Are... | Best Tutorials |
| :--------- | :------------- |
| A developer who is new to Ray | First, [_Ray Crash Course_](ray-crash-course/00-Ray-Crash-Course-Overview.ipynb), then [_Advanced Ray_](advanced-ray/00-Advanced-Ray-Overview.ipynb) |
| A developer who is experienced with Ray | [_Advanced Ray_](advanced-ray/00-Advanced-Ray-Overview.ipynb) |
| A developer or data scientist interested in Reinforcement Learning | [_Ray RLlib_](ray-rllib/00-Ray-RLlib-Overview.ipynb) |
| A developer or data scientist interested in Hyperparameter Tuning  | [_Ray Tune_](ray-tune/00-Ray-Tune-Overview.ipynb) |
| A developer or data scientist interested in distributed training models in PyTorch or TensorFlow | [_Ray Train_](ray-tune/00-Ray-Train-Overview.ipynb)(renamed from Ray SGD)|
| A developer or data scientist interested in model serving | [_Ray Serve_](ray-serve/00-Ray-Serve-Overview.ipynb) |
| A _DevOps_ engineer interested in managing Ray clusters | _Ray Cluster Launcher_ (forthcoming) |

See the [Overview notebook](Overview.ipynb) for detailed, up-to-date descriptions for each tutorial and the lessons it contains.

## Troubleshooting and Further Information

See the [Troubleshooting, Tips, and Tricks](reference/Troubleshooting-Tips-Tricks.ipynb) notebook.

For details on the Ray API and the ML libraries, see the [Ray Docs](https://docs.ray.io/en/latest/). For other information, see [ray.io](https://ray.io), including the [Ray blog](https://medium.com/distributed-computing-with-ray).

[Ray](https://ray.io) started at [U.C. Berkeley RISELab](https://rise.cs.berkeley.edu/). It is now developed in artisanal, small batches at [Anyscale](https://anyscale.com).