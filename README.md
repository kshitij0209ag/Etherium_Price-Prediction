# Etherium_Price-Prediction
# Problem : To predict the price of etherium
-> crypto prices are extremely volatile, and the people who trade them are trying to capitalize on that volatility.
-> The value of one ETH was trending between 1800 USD and 2300 USD in July 2021.

# What is Cryptocurrency ?
-> A cryptocurrency, crypto-currency, or crypto is a binary data designed to work as a medium of exchange wherein individual coin ownership records are stored in a ledger existing in a form of a computerized database using strong cryptography to secure transaction records, to control the creation of additional coins, and to verify the transfer of coin ownership.
-> Cryptocurrency does not exist in physical form (like paper money) and is typically not issued by a central authority.

# What Is Ethereum?
-> Ethereum is a blockchain platform with its own cryptocurrency, called Ether (ETH) or Ethereum, and its own programming language, called Solidity.

-> As a blockchain network, Ethereum is a decentralized public ledger for verifying and recording transactions. The network's users can create, publish, monetize, and use applications on the platform, and use its Ether cryptocurrency as payment. Insiders call the decentralized applications on the network "dapps."

1. Ethereum is an open-source blockchain-based platform used to create and share business, financial services, and entertainment applications.
2. Ethereum users pay fees to use dapps. The fees are called "gas" because they vary depending on the amount of computational power required.
3. Ethereum has its own associated cryptocurrency, Ether or ETH.
4. bIts cryptocurrency is now second only to Bitcoin in market value.

# What Is Ethereum in Simple Terms?
-> Ethereum, like any blockchain, is a database of information that is designed to be unhackable. Ether, or ETH, is the cryptocurrency used to complete transactions on the blockchain.

-> Unlike in a traditional database, information in a blockchain is organized as a chronological "chain" made up of "blocks" of data. For instance, every transaction using an Ether coin must be verified and recorded as an additional block on that coin's unique blockchain.

# How Does Ethereum Make Money?
-> Users pay fees to use dapps on the Ethereum platform. These fees are called "gas" because they vary depending on the amount of computational power used

# Approach to solve Problem.
1. First of all we will collect/load/Download the data.
2. After having the data we will read that data in our jupyter notebook in the form of DataFrame.
3. After creating dataframem we will analyse the data like no. of rows and columns.
4. Then we try to process the data according to our need, we make necessary change adding or removing rows/columns etc.
5. After some preprocessing then we will visualize the data for better understanding of the features , here we will look at the heatmap which tells about the correlation between different features or columns.
6. After Visualizing we will select our feature to be used for model training.
7. After data preparation we will split our data into training and testing set, so that we can paas them to our model for training and testing.
8. After splitting data and visualizing our data sets we select the appropriate model for prediction , here we are using the Linear Regression model , because our data is showing Linear behaviour.
9. After model building we will test the accuracy of our model and predict some test data or values using that model.
10. in last we wiil save our model using pickle module, so if in future we want to use it we can just import and predict values insatntly.


# What is NumPy?
-> NumPy is the fundamental package for scientific computing in Python. It is a Python library that provides a multidimensional array object, various derived objects (such as masked arrays and matrices), and an assortment of routines for fast operations on arrays, including mathematical, logical, shape manipulation, sorting, selecting, I/O, discrete Fourier transforms, basic linear algebra, basic statistical operations, random simulation and much more.

# What Is Pandas?
-> Pandas is an open source Python package that is most widely used for data science/data analysis and machine learning tasks. It is built on top of another package named Numpy, which provides support for multi-dimensional arrays.

# What Can You Do With DataFrames Using Pandas?
-> Pandas makes it simple to do many of the time consuming, repetitive tasks associated with working with data, including:

Data cleansing
Data fill
Data normalization
Merges and joins
Data visualization
Statistical analysis
Data inspection
Loading and saving data
And much more


# What Is Python Matplotlib?
-> matplotlib.pyplot is a plotting library used for 2D graphics in python programming language. It can be used in python scripts, shell, web application servers and other graphical user interface toolkits.

# Is Matplotlib Included in Python?
-> Matplotlib is not a part of the Standard Libraries which is installed by default when Python, there are several toolkits which are available that extend python matplotlib functionality. Some of them are separate downloads, others can be shipped with the matplotlib source code but have external dependencies.

# Python Matplotlib : Types of Plots
-> There are various plots which can be created using python matplotlib. Some of them are listed below:

## An introduction to seaborn
-> Seaborn is a library for making statistical graphics in Python. It builds on top of matplotlib and integrates closely with pandas data structures.
-> Seaborn helps you explore and understand your data. Its plotting functions operate on dataframes and arrays containing whole datasets and internally perform the necessary semantic mapping and statistical aggregation to produce informative plots. Its dataset-oriented, declarative API lets you focus on what the different elements of your plots mean, rather than on the details of how to draw them.

# What is scikit-learn?
-> Scikit-learn provides a range of supervised and unsupervised learning algorithms via a consistent interface in Python.

-> The library is built upon the SciPy (Scientific Python) that must be installed before you can use scikit-learn. This stack that includes:

NumPy: Base n-dimensional array package
SciPy: Fundamental library for scientific computing
Matplotlib: Comprehensive 2D/3D plotting
IPython: Enhanced interactive console
Sympy: Symbolic mathematics
Pandas: Data structures and analysis

## Scikit-learn comes loaded with a lot of features. Here are a few of them to help you understand the spread:

Supervised learning algorithms
Unsupervised learning algorithms
Cross-validation
Various toy datasets
Feature extraction








