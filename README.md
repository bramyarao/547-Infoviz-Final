# Did We Save Our Tigers?

Authors: <br/>
Kattie Sepehri, Unma Desai, Ramya Rao Basava<br/>
Department of Computer Science, <br/>
University of British Columbia, Vancouver.
<br/>

### This work is copyrighted.
<br/>

## Code Programming Details
<div style="text-align: justify">
For this project we used Python 3 programming language and the Plotly library to create the visualizations. References have been provided in the code as required. These visualizations are then saved as .html files (for interactive visualizations) or .png figures (for static visualizations) to be embedded in the main webpage created using html and css. The webpage is an explainer article about the project and illustrates all the visualizations designed. 
</div>


## Code Folder Details
<div style="text-align: justify">
The Github repository consists of the following folders and files:
<ul style="list-style-type:disc;"> 
<li> Data folder: Contains the original and processed data files. Depending on the visualization, different processed data files exist, which will be used as input. In addition, this folder also contains the india_states.geojson file which gives the polygon information of various states in India. This will be needed to plot the Choropleth maps of India in visualizations 1 and 2. </li>
<li> JupyterCodes: Each of the 7 visualizations have an individual jupyter notebook in this folder. Please note that for the first two visualizations, where the Indian map is ploted, the files are pretty big (was not uploading to github), so we did not save the fully run notebook. The output was cleared and the code was saved. If you want to see these plots, you can check the webpage or the .html files saved in HTMLs folder. </li>
<li> index.html: This is the main .html file for creating the webpage. </li>
<li> CSSheets: Contains the main.css file which provides the styling details for the index.html webpage. </li>
<li>HTMLs: In this folder, the plots obtained for the visualizations coded in Jupyter notebooks, are directly saved as .html files or .png figures to be embedded in the index.html file.</li>
</ul>
</div> 

 ## How to compile and run?

 ### Step-1:
<div style="text-align: justify">
Run all the jupyter notebooks. Outputs will be automatically saved to the HTMLs folder.
</div>

 ### Step-2:
<div style="text-align: justify">
Run the index.html file on a live server. Alternately it will show on the Github pages: https://bramyarao.github.io/547-Infoviz-Final/
</div>


