- title : Data exploration through dot-driven development 
- description : 
- author : Tomas Petricek
- theme : white
- transition : none

****************************************************************************************************

# Wrattler: _Interactive, smart<br /> and polyglot notebooks_

<h4 style="margin:300px 0px 0px 0px">Tomas Petricek <em>for the AIDA team</em></h4>

_[http://tomasp.net](http://tomasp.net/academic) <span style="margin:0px 6px 0px 6px">|</span>
[tomas@tomasp.net](mailto:tomas@tomasp.net) <span style="margin:0px 6px 0px 6px">|</span>
[@tomaspetricek](http://twitter.com/tomaspetricek)_

****************************************************************************************************

### What makes data science hard?

<br />

_<i class="fa fa-hand-spock"></i> Hard-to-find special cases_

_<i class="fa fa-calendar-alt"></i> Every data set is correct in its own way_

_<i class="fa fa-sync-alt"></i> Can't say what works until we've done it_

_<i class="fa fa-align-justify"></i> Many tasks are repetitive by nature_

----------------------------------------------------------------------------------------------------

### What do we want?

<br />

_<i class="fa fa-comment"></i>_ Interactive tools _to give quick feedback_

_<i class="fa fa-retweet"></i>_ Reproducible _for being able to go back_

_<i class="fa fa-sign-language"></i>_ Polyglot _to mix tools that work_

_<i class="fa fa-flask"></i>_ Smart _to get help from AI assistants_

_<i class="fa fa-user"></i>_ Explainable _without magical black boxes_

----------------------------------------------------------------------------------------------------

### AI for Data Analytics 

<br />

_<i class="fa fa-eye"></i>_ Understanding data<br />
<span style="margin-right:60px"></span> _What type does it have?_

_<i class="fa fa-filter"></i>_ Merging data sources<br />
<span style="margin-right:60px"></span> _Tabular data across files (datadiff)_

_<i class="fa fa-database"></i>_ Reading data from external sources<br />
<span style="margin-right:60px"></span> _Making sense of real-world CSV files_

_<i class="fa fa-magic"></i>_ Putting it all together<br />
<span style="margin-right:60px"></span> _Interactive, smart and polyglot notebooks_

****************************************************************************************************

# Wrattler vision
_Making notebooks interactive, smart and polyglot_

----------------------------------------------------------------------------------------------------

# DEMO
_Analysing broadband speed in Wrattler_  

----------------------------------------------------------------------------------------------------

## Traditional notebook architecture

<img src="images/jupyter.png" style="width:70%;margin-bottom:60px"/>

_<span class="circ"><span>1</span></span> Limited reproducibility_  
_<span class="circ"><span>2</span></span> No rollback of state_  
_<span class="circ"><span>3</span></span> Limited interaction model_  
_<span class="circ"><span>4</span></span> One language per kernel_  

----------------------------------------------------------------------------------------------------

## Wrattler system architecture

<img src="images/wrattler.png" style="width:70%"/>

----------------------------------------------------------------------------------------------------

## Wrattler system architecture
 
_<span class="circ"><span>1</span></span> Versioning and provenance_  
_<span class="circ"><span>2</span></span> Interactive development_  
_<span class="circ"><span>3</span></span> Platform for AI assistants_  
_<span class="circ"><span>4</span></span> Polyglot programming_  

****************************************************************************************************

# Wrattler prototype 
_Making notebooks_ <span class="circ"><span>1</span></span> interactive 
<span class="circ"><span>2</span></span> smart _and_ 
<span class="circ"><span>3</span></span> polyglot

----------------------------------------------------------------------------------------------------

### <span class="circ"><span>1</span></span> Interactive
_Giving feedback as soon as possible_

<br />

_<i class="fa fa-globe"></i> Browser-based language_

_<i class="fa fa-stopwatch"></i> Recalculated on-the-fly_

_<i class="fa fa-arrow-up"></i> Using dependency graph_

----------------------------------------------------------------------------------------------------

<img src="images/graph-simple.png" style="width:70%;margin-left:15%" />

----------------------------------------------------------------------------------------------------

# <span class="circ"><span>1</span></span> DEMO
Interactive – _Exploring data in the browser_

----------------------------------------------------------------------------------------------------

### <span class="circ"><span>2</span></span> Smart
_Simplifying process with AI assistants_

<br />

_<i class="fa fa-database"></i> Data access via the data store_

_<i class="fa fa-edit"></i> Domain specific languages_

_<i class="fa fa-eye"></i> Generate cleaning script, not clean data_

----------------------------------------------------------------------------------------------------

# <span class="circ"><span>2</span></span> DEMO
Smart – _Cleaning data with the datadiff assistant_

----------------------------------------------------------------------------------------------------

### What is an AI assistant?

_<span class="circ"><span>1</span></span> Run some AI 
<span style="margin-left:20px" class="circ"><span>2</span></span> Ask the user 
<span style="margin-left:20px" class="circ"><span>3</span></span> Repeat_

<br />

_AI assistants as interaction trees_

 - _Each node represents a user choice_
 - _Each node provides a cleaning script_
 
----------------------------------------------------------------------------------------------------

### <span class="circ"><span>3</span></span> Polyglot
_Enabling platform for data science_

<br />

_<i class="fa fa-table"></i> Share data via data frames_

_<i class="fa fa-archive"></i> Computation graph for provenance tracking_

_<i class="fa fa-comment-alt"></i> Semantics for information exchange_

----------------------------------------------------------------------------------------------------

# <span class="circ"><span>3</span></span> DEMO
Polyglot – _Sharing data between R and JavaScript_

****************************************************************************************************

# Status update
_From prototype to open-source project_

----------------------------------------------------------------------------------------------------

### Project status

<br />

_<i class="fa fa-check-square"></i>_ Done – _Prototype and architecture_<br />
<span style="margin-right:60px"></span> _Dependency graph and datadiff assistant_

_<i class="fa fa-cog"></i>_ Current – _System development_<br />
<span style="margin-right:60px"></span> _Production version with AIDA data analyses_

_<i class="fa fa-eye"></i>_ Research – _Open questions_<br />
<span style="margin-right:60px"></span> _Further AI assistants and semantic data store_

----------------------------------------------------------------------------------------------------

### Development milestones
_Working in the open to engage with community<br />
Follow the progress at: [github.com/wrattler](https://github.com/wrattler)_

<br />

_<span class="circ"><span>0</span></span>_ Basic browser notebook  _(mid-August)_  
_<span class="circ"><span>1</span></span>_ Internal alpha version _(mid-September)_  
_<span class="circ"><span>2</span></span>_ Public with AIDA analyses _(end of November)_  
_<span class="circ"><span>3</span></span>_ Adding more assistants _(end of February)_  

****************************************************************************************************

# Summary
_Making the hard part of data science easier_

----------------------------------------------------------------------------------------------------

### Wrattler
_Putting it all together_

<br />

_<i class="fa fa-magic"></i> Platform for AI assisted data science_

_<i class="fa fa-database"></i> Data store with semantic annotations_

_<i class="fa fa-globe"></i> Interactive with provenance in the browser_


----------------------------------------------------------------------------------------------------

### Questions, answers & discussion
_To be continued in a room next door!_

<br />

_<span class="circ"><span>1</span></span>_ Interactivity – _How to advise the AI in datadiff?_<br />
_<span class="circ"><span>2</span></span>_ Problems – _Where can AI assistants help?_<br />
_<span class="circ"><span>3</span></span>_ Integration – _How to make it easy to use?_

<br />
<br />

Tomas Petricek _for the AIDA team_<br />
_[http://tomasp.net](http://tomasp.net/academic) <span style="margin:0px 6px 0px 6px">|</span>
[tomas@tomasp.net](mailto:tomas@tomasp.net) <span style="margin:0px 6px 0px 6px">|</span>
[@tomaspetricek](http://twitter.com/tomaspetricek)_
