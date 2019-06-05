- title : Wrattler
- description :
- author : Tomas Petricek
- theme : white
- transition : none

****************************************************************************************************

# Wrattler: _Polyglot, reproducible<br /> and smart notebooks_

<br /><br /><br /><br />

#### _Demonstration of the developed<br /> prototype system (GDI 1.6b)_

----------------------------------------------------------------------------------------------------

### Polyglot<br/>_Passing data from Python to JavaScript_

----------------------------------------------------------------------------------------------------

<img src="images/s1.png" />

_We start with an empty notebook. Wrattler allows us
to add with_ Markdown _comments and cells with_ JavaScript, R  
_and_ Python _code._

----------------------------------------------------------------------------------------------------

<img src="images/s2.png" />

_We use the Python_ pandas _library to easily load CSV file from an online source._

----------------------------------------------------------------------------------------------------

<img src="images/s3.png" />

_After updating the cell and clicking the_ Evaluate _button, we see a preview of the downloaded data._


----------------------------------------------------------------------------------------------------

<img src="images/s4.png" />

_Next, we add a_ JavaScript _cell with source code that uses the_ Plotly _library to build a visualization._

----------------------------------------------------------------------------------------------------

<img src="images/s5.png" />

_When we evaluate the added code, Wrattler runs our_ JavaScript _directly_ in the web browser _and shows the visualization._

----------------------------------------------------------------------------------------------------

### Reproducible<br/>_Recomputation using provenance_

----------------------------------------------------------------------------------------------------

<img src="images/e1.png" />

_Consider a sample notebook with two cells that define data frames `one` and `two`
and a third cell that concatenates the two and prints the result._

----------------------------------------------------------------------------------------------------

<img src="images/e2.png" />

_We can evaluate cells one-by-one by clicking on_ Evaluate. _Here, we evaluated just the first (Python) cell._

----------------------------------------------------------------------------------------------------

<img src="images/e3.png" />

_But you_ do not have to _run cells one-by-one. If we ask to evaluate the last cell, Wrattler
automatically_ runs  
all dependencies.

_Here, we evaluated  
the last cell and the second was evaluated automatically._

----------------------------------------------------------------------------------------------------

<img src="images/e4.png" />

_If we modify a cell, Wrattler updates the_ dependency
graph _it maintains. Results of all cells that depend on a modified cell are removed and
need to be recomputed._

----------------------------------------------------------------------------------------------------

<img src="images/e5.png" />

_Re-evaluating the last cell also evaluates all cells that it depends on, using the new_ dependency graph.

----------------------------------------------------------------------------------------------------

<img src="images/e6.png" />

_If we revert a change back, we do not have to re-evaluate and we see_ earlier outputs immediately.

_Wrattler caches past dependency graph nodes and reuses a past node that has already been evaluated._

----------------------------------------------------------------------------------------------------

### Smart<br/>_Support for data cleaning tools_

----------------------------------------------------------------------------------------------------

<img src="images/d1.png" />

_Wrattler supports other data wrangling and cleaning tools built as part of the_ AI for Data Analytics
_project such as_ datadiff. _As an example, we look at the UK broadband quality data set._

----------------------------------------------------------------------------------------------------

<img src="images/d2.png" />

_We load two data sets,_ bb2013 _and_ bb2014 _which represent same data for two years, but
with some differences in the file structure._

----------------------------------------------------------------------------------------------------

<img src="images/d3.png" />

_To do any data analysis, we need to reconcile the file structure. For this, we can run_ datadiff.
_by adding an R cell to our notebook._

----------------------------------------------------------------------------------------------------

<img src="images/d4.png" />

_Datadiff takes two datasets and generates_ a list of patches _that can be applied to transform
the structure of the first dataset into the structure of the second dataset._

_We first print the inferred patches._

----------------------------------------------------------------------------------------------------

<img src="images/d5.png" />

_We can switch the tab to_ bb2014nice _to see the new transformed dataset, which is now
compatible with the_ bb2013 _dataset._

----------------------------------------------------------------------------------------------------

<img src="images/d6.png" />

_In addition to_ datadiff, _Wrattler also comes with examples showing_ ptype _for inferring types
of columns and_ CleverCSV _for  
smart CSV parsing._

----------------------------------------------------------------------------------------------------

### Comprehensive<br/>_Simplifying the data analytics process_

----------------------------------------------------------------------------------------------------

<img src="images/a1.png" />

_Wrattler helps with_  
all stages _of the data analytics process._

_We look at a larger notebook, analysing the UK broadband quality data._

----------------------------------------------------------------------------------------------------

<img src="images/a2.png" />

_We can mix_ R and Python _for loading data with_ JavaScript _for quickly visualizing and exploring data._

----------------------------------------------------------------------------------------------------

<img src="images/a3.png" />

_We have access to_ datadiff _and other data wrangling tools, which help us make our data ready for interesting analytical tasks._

----------------------------------------------------------------------------------------------------

<img src="images/a4.png" />

_Wrattler makes it easy to analyse data using the_ wide range of libraries _available for R and Python._
