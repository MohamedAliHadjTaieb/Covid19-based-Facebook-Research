# Covid19-based-Facebook-Research
<p align="justify">In the context of the Covid-19 pandemic, we realize a research work based on the analysis of the data gathered from the Facebook to track the pandemic trends using multlilingual topic modelling for the period spanning from January 1st, 2020 to May 15, 2020.</p>

link to the web site :  https://mohamedalihadjtaieb.github.io/Covid19-based-Facebook-Research/

# Process Descripiton

The process is composed mainly from 3 modules:
<ol>
 <li><p align="justify">Data Collection: It concerns the collection of facebook public posts focused on the context of the pandemic based on a multlingual vocabulary centerd COVID-19. It includes also a routine for updating teh data after extracting the infromation from active users pertaining to a great range of countries.</p></li>
 <li><p align="justify">Multilingual Topic Modelling: It includes a step of pre-teratment for preparing the gathered data. Then, we applied the LDA (Latent Dirichlet allocation) topic modelling method for extracting the COVID-19 related trends through the time from the January 1st, 2020.</p></li>
 <li><p>Results presentation: We propose a novel way for presenting the topic modelling results based on graph structure.</p> </li>
 </ol>

# Dataset description

 <ol>
  <li><b>Overview</b></li>
 
 The image below shows the repartition of geolocation of the information sources using Facebook.
  
 <iframe src="https://www.google.com/maps/d/u/0/embed?mid=1yioy-DZ-7ZX6kMLHMMKJpcHYlhLqbnZQ" width="640" height="480"></iframe>
  
<!--![Image description](https://user-images.githubusercontent.com/19282671/82613476-a823c300-9bc5-11ea-93ec-ecfadee607fc.png)-->
<li>Number of collected public posts during the period since January 1st, 2020 to May 15, 2020.</li>

<img src="https://user-images.githubusercontent.com/19282671/82613476-a823c300-9bc5-11ea-93ec-ecfadee607fc.png">
</ol> 

# COVID-19 Facebook trends

<table>
 <tr><td></td><td><b>January-February 2020</b></td><td><b>March 2020</b></td><td><b>April 2020</b></td><td><b>May 15, 2020</b></td></tr>
 <tr><td><b>Arabic</b></td><td><a href="https://github.com/MohamedAliHadjTaieb/Covid19-based-Facebook-Research/blob/master/GraphRepresentation/Arabic/Output_29-2_ar.gexf">gexf</a><br><a href="https://github.com/MohamedAliHadjTaieb/Covid19-based-Facebook-Research/blob/master/GraphRepresentation/Arabic/Covid_19.zip-29-2_ar_FB.gephi">gephi</a></td><td><a href="https://github.com/MohamedAliHadjTaieb/Covid19-based-Facebook-Research/blob/master/GraphRepresentation/Arabic/Output-31-3_ar.gexf">gexf</a><br><a href="https://github.com/MohamedAliHadjTaieb/Covid19-based-Facebook-Research/blob/master/GraphRepresentation/Arabic/Covid_19.zip-31-3_ar_FB.gephi">gephi</a></td><td><a href="https://github.com/MohamedAliHadjTaieb/Covid19-based-Facebook-Research/blob/master/GraphRepresentation/Arabic/Output_30-4_ar.gexf">gexf</a><br><a href="https://github.com/MohamedAliHadjTaieb/Covid19-based-Facebook-Research/blob/master/GraphRepresentation/Arabic/Covid_19.zip-30-4_ar_FB.gephi">gephi</a></td><td><a href="https://github.com/MohamedAliHadjTaieb/Covid19-based-Facebook-Research/blob/master/GraphRepresentation/Arabic/Output_15-5_ar.gexf">gexf</a><br><a href="https://github.com/MohamedAliHadjTaieb/Covid19-based-Facebook-Research/blob/master/GraphRepresentation/Arabic/Covid_19.zip-15-5_ar_FB.gephi">gephi</a></td></tr>
 <tr><td><b>English</b></td><td><a href="https://github.com/MohamedAliHadjTaieb/Covid19-based-Facebook-Research/blob/master/GraphRepresentation/English/Output_29-2_En.gexf">gexf</a><br><a href="https://github.com/MohamedAliHadjTaieb/Covid19-based-Facebook-Research/blob/master/GraphRepresentation/English/Covid_19.zip-29-2_En_FB.gephi">gephi</a></td><td><a href="https://github.com/MohamedAliHadjTaieb/Covid19-based-Facebook-Research/blob/master/GraphRepresentation/English/Output_31-3_En.gexf">gexf</a><br><a href="https://github.com/MohamedAliHadjTaieb/Covid19-based-Facebook-Research/blob/master/GraphRepresentation/English/Covid_19.zip-31-3_En_FB.gephi">gephi</a></td><td><a href="https://github.com/MohamedAliHadjTaieb/Covid19-based-Facebook-Research/blob/master/GraphRepresentation/English/Output_30-4_En.gexf">gexf</a><br><a href="https://github.com/MohamedAliHadjTaieb/Covid19-based-Facebook-Research/blob/master/GraphRepresentation/English/Covid_19.zip-30-4_En_FB.gephi">gephi</a></td><td><a href="https://github.com/MohamedAliHadjTaieb/Covid19-based-Facebook-Research/blob/master/GraphRepresentation/English/Output_15-5_en.gexf">gexf</a><br><a href="https://github.com/MohamedAliHadjTaieb/Covid19-based-Facebook-Research/blob/master/GraphRepresentation/English/Covid_19.zip-15-5_en_FB.gephi">gephi</a></td></tr>
 <tr><td><b>French</b></td><td>gexf<br>gephi</td><td>gexf<br>gephi</td><td>gexf<br>gephi</td><td>gexf<br>gephi</td></tr>
 <tr><td><b>German</b></td><td>gexf<br>gephi</td><td>gexf<br>gephi</td><td>gexf<br>gephi</td><td>gexf<br>gephi</td></tr>
 <tr><td><b>Italian</b></td><td>gexf<br>gephi</td><td>gexf<br>gephi</td><td>gexf<br>gephi</td><td>gexf<br>gephi</td></tr>
 <tr><td><b>Japanese</b></td><td>gexf<br>gephi</td><td>gexf<br>gephi</td><td>gexf<br>gephi</td><td>gexf<br>gephi</td></tr>
 <tr><td><b>Spanish</b></td><td>gexf<br>gephi</td><td>gexf<br>gephi</td><td>gexf<br>gephi</td><td>gexf<br>gephi</td></tr>
 </table>

