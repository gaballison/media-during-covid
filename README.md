# Library Patron Media Consumption During COVID-19

This was created as the final project for the May 2020 cohort of [Code Louisville](https://codelouisville.org/)'s Python Development course. [Click to view requirements for running this project](#how-to-run-it)

## What Is It

On March 6, 2020, Indiana Governor Eric Holcomb issued [Executive Order 20-02](https://www.in.gov/gov/files/20-02ExecutiveOrder(DeclarationofPublicHealthEmergencyforCOVID-19)FINAL.pdf) declaring a public health emergency for the novel coronavirus COVID-19 pandemic. At their regular monthly meeting on March 17, the [JTPL](https://jefflibrary.org) Board of Trustees [voted to close the library](https://jefflibrary.org/wp/wp-content/uploads/2020/05/Board-Meeting-Minutes-03172020.pdf) effective Wednesday, March 18 to limit the spread of the disease.

Library patrons were instructed to keep all of their currently checked-out materials until told otherwise, and the focus shifted to emphasizing what materials were available online for free through the Library. This project analyzes and visualizes this data on what formats and titles were most popular during this period.

### Notes about the data

The library re-opened to the public in a limited capacity on Monday, June 15. In order to compare apples to apples as much as possible I'm using data for the full months of March and June, instead of only the days we were closed during those months, so I can look at 4 complete months of data.

All of the data currently comes from JTPL patron usage of [Hoopla](https://hoopladigital.com), an online platform offering digital content in eBook, eAudiobook, movie, comic, music, and TV show formats. I hope to be able to expand this in the future for a bigger picture of media usage, [see future plans](#future-plans)

## How To Run It

Here's how to access the project:

### 1. Install Dependencies

This project was built in a [pipenv virtual environment](https://pipenv-fork.readthedocs.io/en/latest/), so cloning the repo and running

```shell
pipenv install
```

 will automatically install all required dependencies. If you'd rather do it manually, here are the requirements:

- [Python 3.8](https://www.python.org/downloads/release/python-380/)
- [Jupyter Lab 2.2.2 / Jupyter Notebook 6.0.3](https://jupyter.org/documentation)
- [matplotlib 3.3.0](https://matplotlib.org/3.3.0/index.html)
- [pandas 1.1.0](https://pandas.pydata.org/docs/whatsnew/v1.1.0.html)

### 2. Run Jupyter Notebook

The body of the project itself is in a Jupyter Notebook, so [start the notebook server](https://jupyter.readthedocs.io/en/latest/running.html) from the command line:

```shell
jupyter notebook
```

It should automatically launch the notebook directory in your browser, so open the `Main.ipynb` file to run it!

## Project Requirements Met

These are the 3 specific [project requirements](https://docs.google.com/document/d/1annXSfeq9YhIbbSKMig4ckWWaU0DmAeF1h3JbY0GOp0/edit) I aimed to meed:

- [x] Read data from an external file, such as text, JSON, CSV, etc and use that data in your application
- [x] Create and call at least 3 functions, at least one of which must return a value that is used
- [x] Visualize data in a graph, chart, or other visual representation of data

I have also made at least **7** commits to this repo, which is more than the minimum 5 as per the above requirements :sweat_smile:

## Future Plans

Because of time constraints, this project initially focuses on looking just at the titles and media formats from one library vendor, [Hoopla](https://hoopladigital.com). I would like to expand on this to include data from other library vendors like [OverDrive](https://jefflibrary.overdrive.com/) (for a larger selection of eBooks and eAudiobooks read) and [Freegal](https://jeffersonin.freegalmusic.com/) (for more music usage).
