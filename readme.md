# Roman Imperial Coin crowd sourcing

[![DOI](https://zenodo.org/badge/19055/MicroPasts/romanImperialCoins.svg)](https://zenodo.org/badge/latestdoi/19055/MicroPasts/romanImperialCoins)

This project has been formulated by Daniel Pett (British Museum) and Ethan Gruber (American Numismatic Society) to aid
with the assignation of Roman Imperial Coinage (RIC) identifiers. 

At the time of writing, the Portable Antiquities Scheme database holds details for over 200,000 Roman coins. Many of 
these fall into the Imperial coinage category. In August 2016, the facility was introduced to integrate with Online 
Coins of the Roman Empire ([OCRE](http://numismatics.org/ocre/)) and tie the two resources together. This relies on the PAS records being assigned a 
standardised identifier, and has presented a computational problem that can possibly be solved by Human interaction with
automatically generated results.

Funded by
=========
![AHRC funded](http://oac.lib.bris.ac.uk/Dserve/images/AHRC%20Logo%20Gray%20LScape2.JPG)

Funded Partners
===============
![British Museum](http://finds.org.uk/images/logos/bm_logo.png)
![UCL](http://crowdsourced.micropasts.org/static/img/black.jpg)
![Portable Antiquities Scheme](http://www.dayofarchaeology.com/wp-content/uploads/2011/05/pasrgbsize4.jpg)
![American Numismatics Society](http://numismatics.org/pmwiki/pub/skins/ans/ans_seal.gif)

Creating the application
========================

You need to install the pybossa-client first (use a virtualenv and this needs boto):

```bash
    $ git clone repoUrl
    $ cd repoName
    $ pbs create_project
```

Once installed, you will need to import tasks and perhaps update the template. To do this:

```bash
   $ cd repoName
   $ pbs update_project
```

To import tasks, we use a csv file and the built in csv importer from the import tasks section of the created project.
You can find an example csv file in this repo.

Documentation
=============

We recommend that you read the section: [Build with PyBossa](http://docs.pybossa.com/en/latest/build_with_pybossa.html) 
and follow the [step by step tutorial](http://docs.pybossa.com/en/latest/user/tutorial.html).

