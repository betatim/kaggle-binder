# kaggle-binder
Use the Kaggle kernels environment on mybinder.org.


## But why?

The [Kaggle kernels](https://www.kaggle.com/kernels) image contains a vast number of tools and libraries. We use it as a general purpose environment to run notebooks.


## How can I use this?

To use it add the link to the Git repository that contains your notebook to the end of this URL:

```
https://mybinder.org/v2/gh/betatim/kaggle-binder/master?urlpath=git-pull?repo=<URL_TO_YOUR_REPO_HERE>
```

Yes, there are two `?` in that URL. It has to be like that.

As an example the [this link](https://mybinder.org/v2/gh/betatim/kaggle-binder/master?urlpath=git-pull?repo=https://github.com/betatim/binderlyzer) will launch the Kaggle environment and fill it with the contents of https://github.com/betatim/binderlyzer


## What libraries are included?

Check out the (huge) `Dockerfile` from which the Kaggle kernels environment is built: https://github.com/Kaggle/docker-python/blob/master/Dockerfile. It probably contains the data science library you were thinking of using.
