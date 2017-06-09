% OLAP data analysis and visualization with Cubes and CubesViewer
% ![](./media/email-icon.png){height=40 style=vertical-align:middle} jjmontes@gmail.com - ![](./media/github-icon.png){height=40 style=vertical-align:middle} jjmontesl
% PyDay Galicia 2017 (*CC BY-SA 3.0*)


## Agenda

* Business Intelligence and OLAP
* Cubes (Simple Python OLAP server)
* Cubes Examples
* Visualization with CubesViewer

# Business Intelligence and OLAP

## Business Intelligence (BI)

BI comprises the set of strategies, processes, applications, data, technologies
and technical architectures which are used by enterprises[citation needed] to
support the collection, data analysis, presentation and dissemination of
business information.

* ETL (extract, transform and load)
* Data warehousing (storage, accessibility, performance)
* Data mining (querying, visualization... obtaining meaningful results)
* Machine learning (lately)

## Online Analytical Processing (OLAP)

OLAP is an approach to answering multi-dimensional analytical (MDA) queries in computing.
It is typically contrasted to OLTP,

OLAP tools enable users to analyze multidimensional data interactively from multiple
perspectives. Databases configured for OLAP use a multidimensional data model, allowing for
complex analytical and ad hoc queries with a **rapid execution time**.

## (Multidimensional) Data Model

![](./media/olap-facts-dimensions.png)

Based on facts and dimension.

## OLAP Operations

OLAP consists of three basic analytical operations:

* Consolidation (roll-up)
* Drill-down
* Slicing and dicing

---

![](./media/cv-consolidation.png)

**Consolidation** involves *aggregating* fact *measures* appropriately (avg, sum...).

---

![](./media/cv-drilldown.png)

**Drill-down** is the ability to provide separate results over one or
more *dimensions*.

---

![](./media/cv-slicing.png)

**Slicing and dicing** is the ability to select only *slices* of a dimension,
meaning *filtering* a set of values we are interested in.


## ROLAP

ROLAP refers to OLAP

**Star Schema**

* Fact tables
* Dimension tables

## ETL

OLAP / BI
OLTP vs OLAP / Google Analytics
ETL (Data -> ETL -> OLAP)

# Cubes

## Cubes

What it is

## State of art

* OLAP/BI in other languages: Pentaho, MSB
* Common data tools in Python (Pandas, ...)
* Common data analytic tools (ElasticSearch, Cassandra)
* Common visualization tools (Superset, to d3.js/nvd3.js)
* Common SaaS (Qlik, datadog, firebase, google analytics)
* Standards: Google Dataset

## Cubes Concepts

# Cubes Example

## Installing

Using PIP:

```
python3 -m venv env
. env/bin/activate
pip install cubes
```

Cubes works in both Python 2.7 and 3.x.

## Loading the dataset

## Configuring the data model

## Configuring the

# Visualization with CubesViewer

## CubesViewer

## Downloading CubesViewer

## Visualizing the example

CubesViewer can be loaded simply by pointing the browser at:

[http://cubesviewer-path/]()

## More complex example

DatosPublicos

## References

* [Cubes](http://cubes.databrewery.org/)
* [CubesViewer](http://www.cubesviewer.com/)

* Star Schema The Complete Reference -
* [Business Intelligence](https://en.wikipedia.org/wiki/Business_intelligence)
* [Online_analytical_processing](https://en.wikipedia.org/wiki/Online_analytical_processing)
* [Extract, transform, load](https://en.wikipedia.org/wiki/Extract,_transform,_load)
* [Star Schema](https://en.wikipedia.org/wiki/Star_schema)

## Q&A ?

Thanks!




