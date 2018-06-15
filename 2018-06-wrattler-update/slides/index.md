- title : Data exploration through dot-driven development 
- description : 
- author : Tomas Petricek
- theme : white
- transition : none

****************************************************************************************************

# Wrattler: _Interactive, smart<br /> and polyglot notebooks_

<h4 style="margin-bottom:0px;margin-top:300px">James Geddes<em>, Tomas Petricek, Charles Sutton</em></h4>

_[https://github.com/wrattler](https://github.com/wrattler)_

----------------------------------------------------------------------------------------------------

<div style="padding-left:100px">

**<span style="display:inline-block;width:60px">W</span>**  
**<span style="display:inline-block;width:60px">R</span>**  
**<span style="display:inline-block;width:60px">A</span>**  
**<span style="display:inline-block;width:60px">T</span>**  
**<span style="display:inline-block;width:60px">T</span>**  
**<span style="display:inline-block;width:60px">L</span>**  
**<span style="display:inline-block;width:60px">E</span>**  
**<span style="display:inline-block;width:60px">R</span>**  

</div>

----------------------------------------------------------------------------------------------------

<div style="padding-left:100px">

**<span style="display:inline-block;width:60px">W</span>** _Wrangle_  
**<span style="display:inline-block;width:60px">R</span>** _Reproduce_  
**<span style="display:inline-block;width:60px">A</span>** _Analyse_  
**<span style="display:inline-block;width:60px">T</span>** _Transform_  
**<span style="display:inline-block;width:60px">T</span>** _Troubleshoot_  
**<span style="display:inline-block;width:60px">L</span>** _Learn_  
**<span style="display:inline-block;width:60px">E</span>** _Explore_  
**<span style="display:inline-block;width:60px">R</span>** _Revise_  

</div>

****************************************************************************************************

### What makes data science hard?

<br />

_<i class="fa fa-hand-spock"></i>_ Big data is big  
<span style="margin-right:60px"></span> _Hard-to-find special cases_

_<i class="fa fa-calendar-alt"></i>_ The Double Anna Karenina principle  
<span style="margin-right:60px"></span> _Every data set is different_

_<i class="fa fa-sync-alt"></i>_ Feedback loops everywhere  
<span style="margin-right:60px"></span> _Can't say what works until we've done it_

_<i class="fa fa-align-justify"></i>_ Death by a thousand cuts  
<span style="margin-right:60px"></span> _Many tasks are repetitive_

----------------------------------------------------------------------------------------------------

### Data science 
_What tools do we need?_

<br />

_<i class="fa fa-comment"></i>_ Interactive – _give quick feedback_

_<i class="fa fa-retweet"></i>_ Reproducible – _be able to go back_

_<i class="fa fa-sign-language"></i>_ Polyglot – _mix tools that work_

_<i class="fa fa-flask"></i>_ Smart – _get help from the AI_

_<i class="fa fa-user"></i>_ Explainable – _no black boxes_

----------------------------------------------------------------------------------------------------

<img src="images/screen1.png" style="height:700px;margin-left:80px;margin-top:-20px" />

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

# Project plan
_From prototype to open-source project_

----------------------------------------------------------------------------------------------------

### Project status
_Wrattler prototype available at [github.com/wrattler](http://github.com/wrattler)_

<br />

_<i class="fa fa-check-square"></i>_ Done – _Prototype and architecture_<br />
<span style="margin-right:60px"></span> _Dependency graph and datadiff assistant_

_<i class="fa fa-cog"></i>_ Current – _System development_<br />
<span style="margin-right:60px"></span> _AIDA data analyses and JupyterLab integration_

_<i class="fa fa-eye"></i>_ Research – _Open questions_<br />
<span style="margin-right:60px"></span> _Further AI assistants and semantic data store_

----------------------------------------------------------------------------------------------------

### Development milestones
_Detailed plan [available on GitHub](https://github.com/wrattler/wrattler/issues/9)_

<br />

_<span class="circ"><span>0</span></span>_ Basic browser notebook  _(mid-August)_  
_<span class="circ"><span>1</span></span>_ Internal alpha version _(mid-September)_  
_<span class="circ"><span>2</span></span>_ Public with AIDA analyses _(end of November)_  
_<span class="circ"><span>3</span></span>_ Adding more assistants _(end of February)_  


****************************************************************************************************

# Wrattler prototype 
_Noteboks that are_ <span class="circ"><span>1</span></span> interactive 
<span class="circ"><span>2</span></span> smart _and_ 
<span class="circ"><span>3</span></span> polyglot

----------------------------------------------------------------------------------------------------

### <span class="circ"><span>1</span></span> Interactive
_Tighter interaction feedback loop_

<br />

_<i class="fa fa-globe"></i> Browser-based language_

_<i class="fa fa-stopwatch"></i> Recalculated on-the-fly_

_<i class="fa fa-arrow-up"></i> Using dependency graph_

----------------------------------------------------------------------------------------------------

<img src="images/graph-simple.png" style="width:70%;margin-left:15%" />

----------------------------------------------------------------------------------------------------

<img src="images/screen2.png" style="margin-left:20px;margin-top:20px" />

----------------------------------------------------------------------------------------------------

### <span class="circ"><span>2</span></span> Smart
_Simplifying process with AI assistants_

<br />

_<i class="fa fa-database"></i> Full access to data store_

_<i class="fa fa-language"></i> Domain specific languages_

_<i class="fa fa-archive"></i> No black box magic_

----------------------------------------------------------------------------------------------------

<img src="images/screen3.png" style="margin-left:20px;margin-top:20px" />

----------------------------------------------------------------------------------------------------

### <span class="circ"><span>3</span></span> Polyglot
_Enabling platform for data science_

<br />

_<i class="fa fa-table"></i> Share data via data frames_

_<i class="fa fa-archive"></i> Computation graph for provenance_

_<i class="fa fa-comment-alt"></i> Semantic annotations_

----------------------------------------------------------------------------------------------------

<img src="images/screen4.png" style="margin-left:20px;margin-top:20px" />

****************************************************************************************************

# Summary
_Interactive, smart and polyglot notebooks_

----------------------------------------------------------------------------------------------------

### Wrattler
_Three key ideas behind the system_

<br />

_<i class="fa fa-database"></i> Separate state and language runtimes_

_<i class="fa fa-globe"></i> Dependency graph in the browser_

_<i class="fa fa-magic"></i> Platform for AI assisted data science_

----------------------------------------------------------------------------------------------------

## Questions, answers & discussion

#### Data store – _Best data and annotation formats?_

#### Integration – _Languages? Jupyter integration?_

#### AI assistants – _What kinds of assistants?_

<br />
<br />

_[http://tomasp.net](http://tomasp.net/academic) <span style="margin:0px 6px 0px 6px">|</span>
[tomas@tomasp.net](mailto:tomas@tomasp.net) <span style="margin:0px 6px 0px 6px">|</span>
[@tomaspetricek](http://twitter.com/tomaspetricek)_

> To wrap up, I'll end with a slide that lists the three next papers that I plan to write.
> The first one is about implementing live programming environments, which is surprisingly
> tricky and the second one is extending the data aggregation work to cover data cleaning with
> AI assistants. Finally, I talked about one of the things that I'm interested in, but I also
> work on philosophy and history of programming and I got invited to submit a paper to an
> ACM HOPL conference, so that's my third. I have ideas about coeffects too, but I only wanted
> to list three.
