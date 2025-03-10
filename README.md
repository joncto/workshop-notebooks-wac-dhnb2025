# workshop-notebooks-wac-dhnb2025

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/hibernator11/workshop-notebooks-wac-dhnb2025/HEAD)

<img alt="DHNB 2025 conference" src="images/dhnb.png" width="70%">

This project has been developed as part of the workshop "Web Archives Collections as data" for the [DHNB 2025 conference](https://dhnb.eu/conferences/dhnb2025/workshops/web-archive-collections-as-data/). The coordinators of the workshop are:

- Olga Holownia , International Internet Preservation Consortium
- Gustavo Candela, University of Alicante, Spain
- Helena Byrne, British Library, UK
- Jon Carlstedt Tønnessen, National Library of Norway, Norway
- Anders Klindt Myrvoll, Royal Danish Library, Denmark 
- Sophie Ham, National Library of the Netherlands, Netherlands
- Steven Claeyssens, National Library of the Netherlands, Netherlands 

This project provides examples of code based on Jupyter Notebooks to extract Web Archive Content to create collections as data. This examples facilitate the extraction and reuse of datasets of text extracted from all available captures of archived web pages. The datasets can be employed to analyse changes over time and to identify the most relevant words.

## Digital collections
The datasets used in this workshop are the following Web Archives:

- [Australian Web Archive](https://web.archive.org.au/awa/) - [More information](https://trove.nla.gov.au/help/categories/websites-category#australian-web-archive)
- [UK Government Web Archive](https://webarchive.nationalarchives.gov.uk/ukgwa/) - [Terms of use](https://www.nationalarchives.gov.uk/legal/)
- [Internet Archive](https://web.archive.org/web/) - [Terms of Use, Privacy Policy, and Copyright Policy](https://archive.org/about/terms)
- [UK Web Archive - British Library](https://bl.iro.bl.uk/collections/5379d014-1774-46e1-a96a-7089e7c814a3) - [In Copyright](http://rightsstatements.org/page/InC/1.0/?language=es)
- [Norwegian Web Archive - Web News Collection](https://www.nb.no/en/collection/web-archive/research/web-news-corpus/) 

Please, note that we have provided additional information for each of them about terms of use, copyright, etc.

## Notebooks
This project contains the following Jupyter Notebooks:
- Extraction of text from the Australian Web Archive: [getting_text_from_web_pages_AWA](https://nbviewer.org/github/hibernator11/workshop-notebooks-wac-dhnb2025/blob/main/notebooks/getting_text_from_web_pages_AWA.ipynb)
- Extraction of text from the UK Government: [getting_text_from_web_pages_UK](https://nbviewer.org/github/hibernator11/workshop-notebooks-wac-dhnb2025/blob/main/notebooks/getting_text_from_web_pages_UK.ipynb)
- Extraction of text from the Internet Archive and Estonia: [getting_text_from_web_pages_EWA](https://nbviewer.org/github/hibernator11/workshop-notebooks-wac-dhnb2025/blob/main/notebooks/getting_text_from_web_pages_EWA.ipynb)
- Reusing the extracted text from the Australian Web Archive: [reusing_downssteams_AWA](https://nbviewer.org/github/hibernator11/workshop-notebooks-wac-dhnb2025/blob/main/notebooks/reusing_downssteams_AWA.ipynb)

<img alt="Reusing the extracted text from the Australian Web Archive" src="images/downssteam.png" width="50%">
  
- Reusing the metadata provided by the [Scottish Churches dataset](https://bl.iro.bl.uk/concern/datasets/d99a9777-0c28-4a2c-b0f4-c7a43f836b48) (UK Web Archive): [reusing_scottish_churches_UKA-BL](https://nbviewer.org/github/hibernator11/workshop-notebooks-wac-dhnb2025/blob/main/notebooks/reusing_scottish_churches_UKA-BL.ipynb)

<img alt="Reusing the metadata provided by the Scottish Churches dataset" src="images/churches.png" width="50%">

- Extraction and reuse of text and metadata from the Norwegian Web Archive: [webnews-textanalysis-EN](https://nbviewer.org/github/hibernator11/workshop-notebooks-wac-dhnb2025/blob/main/notebooks/webnews-textanalysis-EN.ipynb)

<img alt="Distribution of texts per publication title using the keywords covid-19 OR korona - Web News Collection" src="images/webnews.png" width="50%">

 An additional Jupyter Notebook is provided to show how to use advanced functionalities to retrieve and extract text as datasets from web archives.
- Using advanced functionalities: [getting_text_from_web_pages_advanced_AWA](https://nbviewer.org/github/hibernator11/workshop-notebooks-wac-dhnb2025/blob/main/notebooks/getting_text_from_web_pages_advanced_AWA.ipynb)

Some of the examples are based on the code provided by the [GLAM Workbench](https://glam-workbench.net/), in particular in the examples of code included in the Web Archive section. Please, note that some of the examples provided as examples of use and may not work due to sever access limitations such as the number of requests per second.

 ## Running the notebooks
**To execute the notebook in Binder:**

- Click the launch binder button above. Once the demo launches, click My_sample_notebook.ipynb in the file listing.
- Run the notebook by selecting Cell > Run All. You call also click the play button to run the notebook cell by cell. You will the output of each cell.
- You can edit the cells, and click on play to run and see the changes.

## Licence
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Licence Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/80x15.png" /></a><br />Content is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International license</a>.

Please, note that the datasets used in this project have separate licences.

## References
- [GLAM Workbench](https://glam-workbench.net/)
- Sherratt, Tim; Jackson, Andrew & Bickford, Jake. (2023). GLAM-Workbench/web-archives (version v1.2.0). Zenodo. https://doi.org/10.5281/zenodo.7898218
- [International GLAM Labs Community](https://glamlabs.io/)
- Candela, G., Chambers, S., & Sherratt, T. (2023). An approach to assess the quality of Jupyter projects published by GLAM institutions. Journal of the Association for Information Science and Technology, 74(13), 1550–1564. https://doi.org/10.1002/asi.24835
- Candela, G., Holownia, O., Odsbjerg, M., Cuper, M., Gabriëls, N., Hofmann, K., Gray, E.J., Chambers, S. and Mahey, M. (2025) ‘Promoting Computational Access to Digital Collections in the Nordic and Baltic Countries: An Icelandic Use Case’, <i>Journal of Open Humanities Data</i>, 11(1), p. 7. https://doi.org/10.5334/johd.261.
- National Library of Norway. (2024). Web News Collection (Version 1) [Data set; SQLite and JSON (API)]. Available through the DH-lab API. http://api.nb.no/dhlab/
