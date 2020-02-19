## Overview ##

This repository aims to provide a platform for thinking about, 
and developing, a unified view of metadata elements required to 
describe climate indices (aka climate indicators). 

To facilitate data exchange and dissemination the metadata should, 
as far as possible, follow 
[Climate and Forecasting [CF] Conventions](http://cfconventions.org/). 
Considering the very rich and diverse flora of climate indices this 
is however not always possible. By collecting a wide range of 
different indices it is easier to discover any common patterns and 
features that are currently not well covered by the CF Conventions. 
Currently identified issues frequently relate to 
[`standard_name`](http://cfconventions.org/Data/cf-conventions/cf-conventions-1.8/cf-conventions.html#standard-name) 
or/and [`cell_methods`](http://cfconventions.org/Data/cf-conventions/cf-conventions-1.8/cf-conventions.html#cell-methods)
which both are *controlled vocabularies* of the CF Conventions.

This repository is in active development, and the content will frequently change. 

Currently, the main component is a speadsheet file, **master_table.xls**, 
that contains several tables as separate sheets. The *.xls* format should 
[hopefully] be readable/editable by several common desktop office.

The sheets are as follows:

* **index_table**  ---  the main table holding the metadata for the 
individual indices. Most of the indices developed by the 
[ETCCDI](https://www.wcrp-climate.org/etccdi) and [ET-SCI](https://climpact-sci.org/about/project/) 
are included, as are the ones produced by 
[ECA&D](https://www.ecad.eu/indicesextremes/index.php). 
However, some of the more complex indices remain to be included. 

* **variables**  ---  specification of input variables (following CMIP5/6 and 
CORDEX rules). This sheet also gives common aliases for the variable names.

* **index_functions**  ---  some details related to code snippets (external) 
for calculation of the indices.

* **ECA&D**  ---  list of indices produced by 
[ECA&D](https://www.ecad.eu/indicesextremes/index.php). Many of these are 
already covered by existing entries in the *index_table* sheet.



This work is supported by the European project [IS-ENES3](https://is.enes.org/) and by
[SMHI Rossby Centre](https://www.smhi.se/en/research/research-departments/climate-research-rossby-centre2-552).


## Licence ##

**CF-index-meta** (c) by *Lars Barring* and *Klaus Zimmermann*, Rossby Centre, 
Swedish Meteorological and Hydrological Institute (SMHI).

![](https://i.creativecommons.org/l/by-sa/4.0/88x31.png) **CF-index-meta** is 
licensed under a Creative Commons Attribution-ShareAlike 4.0 International License.

You should have received a copy of the license along with this
work. If not, see <http://creativecommons.org/licenses/by-sa/4.0/>.


