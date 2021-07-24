# Tutorial on Understanding Group Membership from Language Use

This repository holds Jupyter Notebooks and slides related to this tutorial.
- Data prepration. This tutorial provides the instruction and code on how to preprocess the raw text data and convert it to LIWC feature vectors in a robust way. An example file is provided to try and test the tutorial.
- Salient social identity detection model. We provide the instructions and code to build the salient social identity detection model. The user would be abe to run the code using the provided dataset, or his/her own datasets after following the data prepration tutorial.
- Domain adaptation. In case that train and test data are drawn from different distributions (domains), it is advised to apply the domain adaptation to shift the source and target distributions towards each other. This tutorial provides the full explanation of the concept of domain adaptation and the code to instructions required to apply the 'Unsupervised visual domain adaptation using subspace alignment'.


# Requirements:
- Install Jupyter Notebook
- Download the datasets, Mumsnet and Reddit data from https://osf.io/974fc/?view_only=a1b5afe488db4014b3f21ed808bcceb9 and Reddit data https://osf.io/qp6cs/?view_only=a1b5afe488db4014b3f21ed808bcceb9, respectively.
- Clone the package, and save the datasets in ./data folder

You can then launch the notebooks.
