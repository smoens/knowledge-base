📚 Resource list

- [📊 Data Visualisation](#-data-visualisation)
  - [Applications](#applications)
    - [Amazon Quicksight `*`](#amazon-quicksight-)
    - [Dash `*`](#dash-)
    - [D3js `*`](#d3js-)
    - [Google Looker `*`](#google-looker-)
    - [Grafana](#grafana)
    - [Power BI](#power-bi)
    - [RShiny](#rshiny)
    - [Streamlit](#streamlit)
    - [Tableau](#tableau)
- [🤖 Machine Learning](#-machine-learning)
- [🔗 Data Warehousing](#-data-warehousing)
- [👩‍💻 Software Development](#-software-development)
- [📙 Books](#-books)
  - [Machine Learning](#machine-learning)
    - [Deep Learning by Ian Goodfellow et al. `*`](#deep-learning-by-ian-goodfellow-et-al-)
    - [Pattern Recognition and Machine Learning by Christopher M. Bischop `*`](#pattern-recognition-and-machine-learning-by-christopher-m-bischop-)
  - [Data Warehousing](#data-warehousing)
    - [The Data Warehouse Toolkit by Ralph Kimball `currently reading`](#the-data-warehouse-toolkit-by-ralph-kimball-currently-reading)
- [🕵️‍♀️ People](#️️-people)
  - [Eugene Yan `machine learning` `career`](#eugene-yan-machine-learning-career)
  - [Susan Shu Chang `machine learning` `career`](#susan-shu-chang-machine-learning-career)
  - [Martin Fowler `software development` `architecture`](#martin-fowler-software-development-architecture)


# 📊 Data Visualisation

## Applications

### Amazon Quicksight `*`
* https://aws.amazon.com/quicksight/
* Currently I don't know how Amazon Quicksight differentiates itself from other data visualisation applications (aside from its pay-per-session model) because I haven't tested it out yet. Just like with Google Looker I'm however excited about how cloud providers are adding data visualisation solutions to their stack, and how this might change and improve the way we analyse data. The problem I currently have with solutions like Tableau and Power BI, is how scalable these solutions are in terms of creation and distribution of datasets and data governance. With the proliferation of custom data models it might be difficult to maintain an overview. It might be the case that these integrated visualisation solutions that are getting closer to the actual database, might provide some advantages in terms of data governance and reduce data model duplication.

### Dash `*`
* https://plotly.com/dash/
* When you search for the web application equivalent to RShiny for Python, this is the one that pops up. 
* other resources
  * https://dash-gallery.plotly.host/Portal/

### D3js `*`
* https://d3js.org/
* The most stunning visualisations I've ever seen, were mostly made with this Javascript library. With the presence of [Observable](https://observablehq.com/) notebooks it's gotten even easier to get started with the tool, but I still haven't succeeded in moving beyond some beginner charts. It takes more time to create a simple barchart than the plug-and-play alternatives in other tools, but the amount of flexibility and the beauty can make it definitely worthwhile. This is one of the tools that's the highest on my "wanting to master"-list.

### Google Looker `*`
* https://looker.com/
* There are already a lot of great visualisation tools out there, but of course there's always room for improvement. It looks like Google Looker has a **more backend driven and robust approach to data visualisation where the Don't Repeat Yourself principle isn't violated** (at least from the database modeling side), contrary to tools like Tableau and Power BI. Tableau and Power BI both have data prep tools as well, but why would one need to have those data prep tools if the work is already done during the data engineering process (aside perhaps from some additional data cleaning work). From demos it seems one can just select import model from database making the model directly available for the visualisation 
  
    What I currently don't like about Google Looker is that I can't start  just testing it out straight away. With other environments or tools at a click of a button you can start playing around straight away, for Looker I need to wait for a team to contact me. This takes the fun out of wanting to test something out straight away and adds unnecessary friction to get started 
    * ![Google Looker message stating that I need to wait for a Looker team](.\assets\dataviz-google-looker.PNG)

### Grafana
* https://grafana.com/
* I know nothing about this one. A team at the company I work uses this tool for data monitoring, but haven't tried it out myself

### Power BI
* https://powerbi.microsoft.com/en-us/
* Kudos to Microsoft and how they made Power BI one of the most widely adopted visualisation tools at the moment. By making the tool readily available to just about everyone, they've managed to decrease the distance between data and business users. I think in terms of look and feel it isn't as stunning as Tableau, but for people already familiar with the Microsoft stack, in particular Excel, the transition to this application and the additional insight into data it can provide is just what they need.

### RShiny
* https://shiny.rstudio.com/
* When you're already working in R for data analytics, this is a great tool to translate your data to a web application. 

### Streamlit
* https://streamlit.io/
* As the website says
  > Streamlit turns data scripts into shareable web apps in minutes.
All in Python. All for free. No front‑end experience required.
* other resources
  * https://streamlit.io/gallery

### Tableau
* https://www.tableau.com/
* I've already played around and created dashboards in Tableau. I think with Tableau the beauty is in the details and in their beautiful visualisation library and user experience design. I think however for a lot of use cases it's not worth the additional cost and for a lot of business cases Power BI will be just as convenient, easy to use and more tailored to self-service than a tool like Tableau


# 🤖 Machine Learning

# 🔗 Data Warehousing

# 👩‍💻 Software Development

--- 

# 📙 Books

## Machine Learning

### [Deep Learning by Ian Goodfellow et al.](https://www.amazon.com/Deep-Learning-Adaptive-Computation-Machine/dp/0262035618/ref=sr_1_1?dchild=1&keywords=deep+learning&qid=1620673009&sr=8-1) `*`

### [Pattern Recognition and Machine Learning by Christopher M. Bischop](https://www.amazon.com/Pattern-Recognition-Learning-Information-Statistics/dp/0387310738/ref=sr_1_1?crid=3GENABVE2V25O&dchild=1&keywords=pattern+recognition+and+machine+learning&qid=1620673230&sprefix=pattern+recognition+%2Caps%2C243&sr=8-1) `*`

## Data Warehousing

### [The Data Warehouse Toolkit by Ralph Kimball](https://www.amazon.com/Data-Warehouse-Toolkit-Definitive-Dimensional/dp/1118530802/ref=sr_1_1?crid=3I658WVYZRO5L&dchild=1&keywords=the+data+warehousing+toolkit&qid=1620673127&sprefix=the+data+warehousing+%2Caps%2C237&sr=8-1) `currently reading`

--- 

# 🕵️‍♀️ People

## Eugene Yan `machine learning` `career`
  * https://eugeneyan.com/
    * Great posts about machine learning and career advice
  * https://github.com/eugeneyan
    * At Eugene Yan's github page you can find some great lists about [papers on real-world machine learning](https://github.com/eugeneyan/applied-ml), [machine learning advances](https://github.com/eugeneyan/ml-surveys)...
    * His lists have inspired me be more 

## Susan Shu Chang `machine learning` `career`
  * https://www.susanshu.com/

## Martin Fowler `software development` `architecture`
  * https://martinfowler.com/

