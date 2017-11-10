

```python
    %load_ext literacy
    from pandas import *
```


```python
about.md
```



![](https://user-images.githubusercontent.com/4236275/32387941-61eb6494-c09c-11e7-8e39-510689aab037.png)

# [Atlanta Jupyter User Group Meeting](https://callisto-morns.github.io/) [One](https://callisto-morns.github.io/)

## Saturday November 11, 2017 _@_ the Georgia Tech Research Institute

__Atlanta Jupyter User Group Meeting__ is a satellite event orbitting the [Project Jupyter](https://jupyter.org).  At each __Atlanta Jupyter User Group Meeting__, Jupyter beginners and veterans will join to share their works.  These events will attract designers, developers, and scientists across the southeast region crafted with Project Jupyter tools.


# [Purchase Tickets at Eventbrite for $5](https://www.eventbrite.com/e/callisto-morn-one-an-event-for-jupyter-users-tickets-39268778975)

> *Tickets on the day of the event are $10*

## [Submit a Talk or Demo](https://docs.google.com/forms/d/e/1FAIpQLSfY1c4y2vLE-q3VMBjOpvTi4pK5D6Q9KudNk25AsxQUjsT3eA/viewform)


## [Github](https://github.com/callisto-morns/one) 


## [Questions?](https://github.com/callisto-morns/one/issues) 

[![Gitter chat](https://badges.gitter.im/callisto-one/Lobby.png)](https://gitter.im/callisto-one/Lobby)

---




```python
# <small>9:00-9:10</small> Open Remarks

* Goals of the Jupyter User Group
* Code of Conduct
```


# <small>9:00-9:10</small> Open Remarks

* Goals of the Jupyter User Group
* Code of Conduct



```python
# <small>9:10-9:45</small> Panel Discussion


```


# <small>9:10-9:45</small> Panel Discussion




```python
demonstrations.md
```



# Case Studies

# <small>9:45-10:15</small> Data exploration in Jupyter

#### Christian McDaniel and Rajeswari Sivakumar

Data exploration in a collaborative environment can be a cumbersome process. In our lab, headed by Dr. Shannon Quinn at the University of Georgia, the use of Jupyter Notebook has streamlined tasks such as data visualization, data preparation, calculations and the sharing of our results. As students, the user-friendly functionality and display of Jupyter Notebook has been instrumental in our ability to learn from each other’s findings. We will explore our use of Jupyter Notebook throughout our most recent research, conducted for the Parkinson’s Disease Digital Biomarker DREAM Challenge, a recent open challenge from Sage Bionetworks. The motivation for the challenge is derived from the effects of Parkinsonian motor symptoms on everyday motor activities. Task-related motion-sensor time series data was provided, and challenge participants were asked to use this data to extract meaningful features which indicate the presence and severity of Parkinsonian motor symptoms. 

# <small>10:15-10:45</small> Flight Data with Bokeh and Datashader

#### [Luke Starnes](http://lstarnes.com/)

This talk will discuss the growth of publicly available aircraft flight data due to the Automatic Dependent Surveillance – Broadcast (ADS-B) mandate. After providing some background, we will review a recent project which analyzed a large worldwide dataset consisting of over 7M reports per day. We will discuss the process used for cleaning, refactoring, and storing the data for quick access. This will include some pointers for those undertaking similar projects. Then we will discuss some of the interesting information we can learn from this data and review visualizations created with Datashader and Bokeh. The slides and code will be made available after the talk. 

# <small>10:45-11:15</small> Style Guides for Jupyter

#### Tony Fast


# Short Demonstrations

# <small>11:30-11:55</small> Up and Running with Jupyter Lab

Y'all have heard about JupyterLab.  This walk through will demonstrate the flexible use cases that the newest version of JupyterLab supports.

    conda install -c conda-forge jupyterlab

# <small>11:55-12:05</small> [SQL with Jupyter Notebooks](# )

#### [Greg Werner](https://github.com/jgwerner)

Many data analysts love SQL for data analysis, for good reason. SQL is a powerful language and is used by countless data analysts and data scientists alike. As some of these personas transition from analysts to data scientists (where the world is indeed gray), having a SQL editor within Jupyter Notebooks becomes a powerful proposition. Learn how to add open source SQL editors as extensions to Jupyter Notebooks with this talk. Source code will be available for all attendees.

# <small>12:05-12:20</small> [Dynamic Notebook Generation for Reports]()

#### [Casey Hartnett](https://github.com/caseyhartnett)

We will start by learning what makes a IPython Notebook. We will then take an example report for a hotel and create a new notebook to generate this report for any number of hotels. We can generate a single file with repeated analysis for different hotels or generate separate notebooks for each. Lastly, we will learn how to run this process from the command line to streamline reporting process further.



# <small>12:20-12:40</small> Group Discussion


# <small>12:40-12:55</small> Tiny Talks

# <small>12:55-1:00</small> Closing

---


```python
# [Full Schedule](schedule.csv)

    
```


# [Full Schedule](schedule.csv)

    



```python
    
    read_csv('schedule.csv')
```




<div>
<style>
    .dataframe thead tr:only-child th {
        text-align: right;
    }

    .dataframe thead th {
        text-align: left;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>start</th>
      <th>end</th>
      <th>duration</th>
      <th>section</th>
      <th>description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>8:30</td>
      <td>9:00</td>
      <td>30 min</td>
      <td>Registration</td>
      <td>Code of Conduct</td>
    </tr>
    <tr>
      <th>1</th>
      <td>9:00</td>
      <td>9:10</td>
      <td>10 min</td>
      <td>Open remarks</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>2</th>
      <td>9:10</td>
      <td>9:45</td>
      <td>35 min</td>
      <td>Panel Discussion</td>
      <td>4 people</td>
    </tr>
    <tr>
      <th>3</th>
      <td>9:45</td>
      <td>10:15</td>
      <td>30 min</td>
      <td>Jupyter Lab Walk Through</td>
      <td>Tony Fast</td>
    </tr>
    <tr>
      <th>4</th>
      <td>9:45</td>
      <td>10:15</td>
      <td>30 min</td>
      <td>Data Exploration in Jupyter</td>
      <td>Raj Sivakumar &amp; Christian McDaniel</td>
    </tr>
    <tr>
      <th>5</th>
      <td>10:15</td>
      <td>10:45</td>
      <td>30 min</td>
      <td>Flight Data in Jupyter</td>
      <td>Luke Starnes</td>
    </tr>
    <tr>
      <th>6</th>
      <td>10:45</td>
      <td>11:15</td>
      <td>30 min</td>
      <td>Style Guides for Jupyter</td>
      <td>Tony Fast</td>
    </tr>
    <tr>
      <th>7</th>
      <td>11:15</td>
      <td>11:30</td>
      <td>15 min</td>
      <td>Break</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>8</th>
      <td>11:40</td>
      <td>11:50</td>
      <td>10 min</td>
      <td>SQL with Jupyter Notebooksk</td>
      <td>Greg Werner</td>
    </tr>
    <tr>
      <th>9</th>
      <td>12:05</td>
      <td>12:20</td>
      <td>15 min</td>
      <td>Dynamic Notebook Generation for Reports</td>
      <td>Casey Hartnett</td>
    </tr>
    <tr>
      <th>10</th>
      <td>12:20</td>
      <td>12:40</td>
      <td>20 min</td>
      <td>Group Discussion</td>
      <td>All</td>
    </tr>
    <tr>
      <th>11</th>
      <td>12:40</td>
      <td>12:55</td>
      <td>15 min</td>
      <td>Tiny Talks</td>
      <td>Whomever</td>
    </tr>
    <tr>
      <th>12</th>
      <td>12:55</td>
      <td>1:00</td>
      <td>5 min</td>
      <td>Closing</td>
      <td>Tony Fast</td>
    </tr>
  </tbody>
</table>
</div>




```python
contributing.md
```



# [contributing](contributing.ipynb)

[![Build Status](https://travis-ci.org/callisto-morns/one.svg?branch=master)](https://travis-ci.org/callisto-morns/one)

## [Submit questions and suggestions through the github issues](https://github.com/tonyfast/callistory/issues)

We hope that community participation can assist future organizers in producing diy technology events.

## Development

* __[readme.ipynb](readme.ipynb)__ provides instruction for external services.
* __[index.ipynb](readme.ipynb)__ the main event site.
* __[about.ipynb](about.ipynb)__ provides information about the event.  Who what where when how why.
* __[contributing.ipynb](about.ipynb)__ provides information about the event.  Who what where when how why.
* __[talks.ipynb](long.ipynb)__ provides provides long format presentations information.

# [Code of Conduct](code_of_conduct.md)




```python
<style>.highlighter-rouge {display: none;}</style>
```


<style>.highlighter-rouge {display: none;}</style>
