# Hi! I'm Franz Louis Cesista ッ

<p align="center">
  <a href="https://github.com/leloykun">
    <img src="https://img.shields.io/github/followers/leloykun.svg?label=GitHub&style=social" alt="GitHub">
  </a>
  <a href="https://twitter.com/leloykun">
    <img src="https://img.shields.io/twitter/follow/leloykun?label=Twitter&style=social" alt="Twitter">
  </a>
  <a href="https://ponder.substack.com">
    <img src="https://img.shields.io/badge/Ponder--_.svg?style=social&logo=substack" alt="Ponder">
  </a>
  <a href="https://www.linkedin.com/in/franzcesista/">
    <img src="https://img.shields.io/badge/LinkedIn--_.svg?style=social&logo=linkedin" alt="LinkedIn">
  </a>
	<a href="https://drive.google.com/file/d/1ZQJv8LYzEPe-JoxEWaM1Ahdi-j2Z0UVK/view?usp=sharing">
    <img src="https://img.shields.io/badge/CV--_.svg?style=social&logo=giphy" alt="Curriculum Vitae">
  </a>
</p>

I study math 🔢, machine learning 🧠, and competitive programming 🥇 - among other things. I'm currently working at [Expedock](http://expedock.com/) as a full-stack software engineer specializing on data science and machine learning.

## Tech Stack
| **Layer** | **Tools** |
| --- | --- |
| Dev env | <a href="https://www.docker.com/"> <img src="https://img.shields.io/badge/Docker--_.svg?style=social&logo=docker" alt="Docker"> </a> |
| Cloud | <a href="https://aws.amazon.com/"> <img src="https://img.shields.io/badge/AWS--_.svg?style=social&logo=amazonaws" alt="AWS"> </a> <a href="https://cloud.google.com/"> <img src="https://img.shields.io/badge/GCP--_.svg?style=social&logo=googlecloud" alt="GCP"> </a> |
| DB | <a href="https://firebase.google.com/"> <img src="https://img.shields.io/badge/Firebase--_.svg?style=social&logo=firebase" alt="Firebase"> </a> <a href="https://www.postgresql.org/"> <img src="https://img.shields.io/badge/PostgreSQL--_.svg?style=social&logo=postgresql" alt="PostgreSQL"> </a> <a href="https://www.snowflake.com/"> <img src="https://img.shields.io/badge/SnowFlake--_.svg?style=social&logo=snowflake" alt="Snowflake"> </a> <a href="https://www.metabase.com/"> <img src="https://img.shields.io/badge/MetaBase--_.svg?style=social&logo=metabase" alt="MetaBase"> </a> |
| Backend | <a href="http://www.cplusplus.org/"> <img src="https://img.shields.io/badge/C++--_.svg?style=social&logo=c%2B%2B" alt="C++"> </a> <a href="https://www.python.org/"> <img src="https://img.shields.io/badge/Python--_.svg?style=social&logo=python" alt="Python"> </a> <a href="https://flask.palletsprojects.com/"> <img src="https://img.shields.io/badge/Flask--_.svg?style=social&logo=flask" alt="Flask"> </a> <a href="https://github.com/sqlalchemy/sqlalchemy"> <img src="https://img.shields.io/badge/SQLAlchemy--_.svg?style=social&logo=github" alt="SQLAlchemy"> </a> <a href="https://github.com/sqlalchemy/alembic"> <img src="https://img.shields.io/badge/Alembic--_.svg?style=social&logo=github" alt="Alembic"> </a> |
| API | <a href="https://en.wikipedia.org/wiki/Representational_state_transfer"> <img src="https://img.shields.io/badge/REST--_.svg?style=social&logo=rest" alt="REST"> </a> <a href="https://graphql.org/"> <img src="https://img.shields.io/badge/GraphQL--_.svg?style=social&logo=graphql" alt="GraphQL"> </a> <a href="https://github.com/strawberry-graphql/strawberry"> <img src="https://img.shields.io/badge/Strawberry--_.svg?style=social&logo=github" alt="Strawberry"> </a> |
| Frontend | <a href="https://reactjs.org/"> <img src="https://img.shields.io/badge/React--_.svg?style=social&logo=react" alt="React"> </a> <a href="https://redux.js.org/"> <img src="https://img.shields.io/badge/Redux--_.svg?style=social&logo=redux" alt="Redux"> </a> <a href="https://www.typescriptlang.org/"> <img src="https://img.shields.io/badge/TypeScript--_.svg?style=social&logo=typescript" alt="TypeScript"> </a> |
| ML | <a href="https://www.keras.io/"> <img src="https://img.shields.io/badge/Keras--_.svg?style=social&logo=keras" alt="Keras"> </a> <a href="https://www.tensorflow.org/"> <img src="https://img.shields.io/badge/TensorFlow--_.svg?style=social&logo=tensorflow" alt="Tensorflow"> </a> <a href="https://scikit-learn.org/"> <img src="https://img.shields.io/badge/ScikitLearn--_.svg?style=social&logo=scikitlearn" alt="Scikit-Learn"> </a> <a href="https://github.com/awslabs/autogluon"> <img src="https://img.shields.io/badge/AutoGluon--_.svg?style=social&logo=github" alt="AutoGluon"> </a>  |

## Math/Research Interests
- **Non-Euclidean Geometry**. More specifically, I'm interested in embedding high-dimensional data into lower-dimensional non-euclidean spaces. Although embedding into euclidean spaces, $\mathbb{R}^n$, is good enough for most cases, there are cases where non-euclidean spaces might be more appropriate. For example:
  - Embedding hierarchical data such as the phylogenetic tree-representation of single-cell specialization data. Real-world hierarchical data are usually tree-like with near-constant branching factors. Thus, they grow exponentially with respect to the depth (e.g. the $k^{th}$-level of a binary tree has $2^{k}$ nodes). However, euclidean spaces, $\mathbb{R}^n$, only grow polynomially with respect to $n$. On the other hand, negatively-curved spaces such as the `poincare disc` grow exponentially. Thus, it's better to embed hierarchical data into them - we just need to be careful with floating-point errors.
  - Embedding complex cyclical data. In my stint at [ExoraPH](https://www.exora.ph/), I used [<img src="https://img.shields.io/badge/UMAP--_.svg?style=social&logo=github" alt="UMAP">](https://umap-learn.readthedocs.io/en/latest/) to uncover the lower-dimensional, torus-like structure of the Philippine's energy supply-and-demand curves.
- **Geometric Deep Learning**. I'm interested in unifying various concepts in machine learning through the lens of the Erlangen Program. I'm especially fascinated with the following:
  - How we can derive linear regression, convolution, the attention mechanism, and message-passing from the geometric transformations we want our models to preserve. For example:
    - If we want translation-invariance, then we have to use convolutions as they're the only family of transformations that are translation-invariant.
    - If we want color- and shade-invariance, then we can use batch-normalization.
    - If we let the weights of the convolutions to be learnable (and depend on the neighbors' weights), then we'd end up with the attention mechanism. And
    - If we generalize the attention mechanism to all graph structures (not just regular graphs), then we'd end up with message-passing.
  - In almost all unsupervised learning models, we just fix two of (a) the manifold $X$, (b) the metric on the manifold $d_X$, and (c) the probability measure $\mu_X$ over the metric space $(X, d_X)$ and then try to estimate the remaining one of the three. For example:
    - In `dimensional reduction`, we usually fix $d_{X, p}(x, y) = \sqrt[p]{\sum_i (x_i - y_i)^p}$ and $\mu_X =$ the uniform distribution (such as in UMAP) then try to find a low-dimenional manifold $X$ that preserves the local distances in the original graph as much as possible.
    - In `metric learning`, we usually fix $X = \mathbb{R}^n$ and $\mu_X =$ the uniform distribution then try to find $d_X$ such that similar datapoints are close together and dissimilar datapoints are far way from each other. And, finnaly,
    - In `density estimation`, we usually fix $X = \mathbb{R}^n$ and $d_{X, p}(x, y) = \sqrt[p]{\sum_i (x_i - y_i)^p}$ then try to find the probability distribution $\mu_X$ of our dataset.

If you're interested in collaborating on a research project with me, just email me at franzlouiscesista@gmail.com
