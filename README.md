# Bokeh: An Interactive Data Visualization Library in CodeBook

Bokeh is a Python library for creating interactive visualizations for modern web browsers including Jupyter Notebook and LSEG CodeBook. It allows users to create ready-to-use appealing plots and charts nearly without much tweaking. 

Bokeh has been around since 2013. It targets modern web browsers to present interactive visualizations rather than static images. Bokeh provides libraries in multiple languages, such as Python, R, Lua, and Julia. These libraries produce JSON data for BokehJS (a Javascript library), which in turn creates interactive visualizations displayed on modern web browsers. Bokeh provides many benefits including:

Simple to complex visualizations: Bokeh provides different interfaces that target users of many skill levels. Users can use basic interfaces for quick and straightforward visualizations or use advanced interfaces for more complex and extremely customizable visualizations.
Easy to use with Pandas: Bokeh provides the ColumnDataSource class which is a fundamental data structure of Bokeh. Most plots, data tables, etc. will be driven by a ColumnDataSource. Users can also assign a Pandas data frame as a data source to plot charts.
Support several output mediums: The output from Bokeh can be displayed on modern web browsers including Jupyter Notebook. The output can also be exported to an HTML file. Moreover, Bokeh can be used to create interactive web applications by running them on the Bokeh server. 
Bokeh provides different levels of interfaces for users to choose from basic plots with very few customizable parameters to advanced plots with full control over their visualizations. Typically, the interfaces are divided into two levels:

bokeh.plotting: The intermediate-level interface that is comparable to Matplotlib. The workflow is to create a figure and then enrich this figure with different elements that render data points in the figure.
bokeh.models: The low-level interface that provides the maximum flexibility to application developers. This interface provides complete control over how Bokeh plots are assembled, configured, and displayed.

The examples in this article mostly rely on the bokeh.plotting interface. You can refer to the Bokeh Gallery for the list of available charts and examples. 

For the full article, please refer to [this article](https://developers.lseg.com/en/article-catalog/article/bokeh--an-interactive-data-visualization-library-in-codebook).  
