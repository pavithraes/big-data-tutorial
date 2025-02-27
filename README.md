# Data of an Unusual Size: A practical guide to analysis and interactive visualization of massive datasets

While most folks aren't at the scale of cloud giants or black hole research teams that analyze Petabytes of data every day, you can easily fall into a situation where your laptop doesn't have quite enough power to do the analytics you need.

"Big data" refers to any data that is too large to handle comfortably with your current tools and infrastructure. As the leading language for data science, Python has many mature options that allow you to work with datasets that are orders of magnitudes larger than what can fit into a typical laptop's memory.

In this hands-on tutorial, you will learn the fundamentals of analyzing massive datasets with real-world examples on actual powerful machines on a public cloud -- starting from how the data is stored and read, to how it is processed and visualized.

You will understand how large-scale analysis differs from local workflows, the unique challenges associated with scale, and some best practices to work productively with your data.

By the end, you will be able to answer:

- What makes some data formats more efficient at scale?
- Why, how, and when (and when not) to leverage parallel and distributed computation (primarily with Dask) for your work?
- How to manage cloud storage, resources, and costs effectively?
- How interactive visualization can make large and complex data more understandable (primarily with hvPlot)?
- How to comfortably collaborate on data science projects with your entire team?

The tutorial focuses on the reasoning, intuition, and best practices around big data workflows, while covering the practical details of Python libraries like Dask and hvPlot that are great at handling large data. It includes plenty of exercises to help you build a foundational understanding within three hours.

<!-- TODO: Update and uncomment

## Repository structure

### Tutorial structure

### Supporting resources

-->

## Setup for SciPy 2023

You can use Nebari (JupterHub) hosted at [scipy.quansight.dev](https://http://scipy.quansight.dev/) to follow along with this tutorial.

Follow [this participant's guide](https://docs.google.com/document/d/1vnWhNyUBRpILb2MAHQfTmZQY3pCIaCmroV9ke49nQlE/edit) to register and sign-in to Nebari, and use the following link to clone the tutorial materials:

```bash
https://github.com/nebari-dev/big-data-tutorial.git
```

In the `big-data-tutorial` folder that's created with all material, navigate to `00-introduction.ipynb`.

The environment for this tutorial is `global-gloabl-data-of-unusual-size`, and it is automatically selected for you. :)


## Live presentations

* SciPy US 2023 (Upcoming!)
* [PyCon US 2023](https://us.pycon.org/2023/schedule/presentation/64/)

You can check out the [tags](todo) for previous versions of this tutorial.

---

This repository is covered by the [Nebari Code of Conduct](https://github.com/nebari-dev/governance/blob/main/CODE_OF_CONDUCT.md),
and is under [BSD 3-Clause license](https://github.com/nebari-dev/nebari/blob/develop/LICENSE).
