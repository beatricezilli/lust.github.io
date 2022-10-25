# Lust in the paintings 

This project was created by [Beatrice Zilli](https://github.com/beatricezilli) and [Antony Persianov](https://github.com/antonpersi) as the final output of the _Modelling and Visualizing Textual Data_ course held at Ca' Foscari Venice University by Professors [Tiziana Mancinelli](https://github.com/tmancinelli) and Antonio Montefusco. 
You can look at the project here: https://beatricezilli.github.io/lust.github.io/


# Our research question

Starting from the course's topic, namely Vices and Virtues, we decided to take into analysis the vice of Lust and investigate its representation in the paintings over the years in the history of art. The project aims at showing how the iconography of Lust changed throughout centuries and how its representation is connected to gender issues, in particular the woman's image. 

Lust is classified by the Christian tradition as one of the seven capital sins. It indicates an excessive, that is irrational, attachment to venereal pleasure. For centuries, the idea of lust has been attributed to the Devil, demons and evil spirits. The representation of this vice has a long history in the art world. In the visual arts, lust has been used as a recurring theme throughout history to represent, and often condemn, the physical and sexual desire. This work focuses, in the first place, on showing how the iconographic representation of lust changed over time, but it also investigates the feminine figure in it and how the concept of woman associated to lust shifted throughout centuries.


# Modelling process 
As pointed out by Sahle et al. in <i> Modelling: Thinking in Practice. An Introduction </i> (2018), the practice of modelling as "explanatory, exploratory and empirical strategies of enquiry" has gain much recognition and attention over the last decades among scientists and scholars, especially with the advent of Digital Humanities that made this practice a core one. Julia Flanders and Fotis Jannidis in their paper <i> A gentle introduction to Data Modelling </i> (2018) point out the importance of models and modelling in different digital humanities activities, such as creating databases, digital editions, softwares and so on. Modelling is the basic of every digital scholarly project, including this one. The concept of modelling is hard to define, but a model is always a kind of mapping, it represents an object, a concept, a research question through different forms of expression that could be visual diagrams, theoretical ideas, images and so on. In our case, our model is the process of creation of an idea that can visually portray information and interpretations on the vice of Lust, it's representation in the paintings, and it's relation to the feminine figure.  

The first step to create this model was building a [conceptual map](https://miro.com/app/board/uXjVO_zZzUo=/?share_link_id=851890614963) on Miro. Through formal and standardized knowledge representations, known as ontologies, we realized a conceptual model made of entities, attributes and relations that helps the reader understand the web content, but that also helped us bearing in mind the structure we wanted our project to have. 
After that, we focused on finding the images of the paintings we selected for our project, which had to be in a good resolution and not subjected by copyright. Our lab assitant, [Valerio Remediani](https://github.com/VRemediani), then helped by uploading the images in IIIF so we could implement the website with [OpenSeaDragon](https://openseadragon.github.io) and [Mirador](https://projectmirador.org) viewer. 

In creating this process, we also used ontologies to create a RDF triple. The Resource Description Framework is one of the most significant applications of graphs developed by the [W3C consortium](https://www.w3.org). With RDF, information about entities is transmitted in a way that is understandable to both humans and machines. This is done through triples, formal statements consisting of a subject, a predicate, and an object. The information about the subject, the predicate and the object is as far as possible expressed as an Internationalized Resource Identifier (IRI).


### Triples of the Data Model
<img width="1247" alt="Снимок экрана 2022-10-24 в 15 32 21" src="https://user-images.githubusercontent.com/99298812/197537948-6d9142a6-3ade-43a8-8107-ec191da383ec.png">

### Graph of the data model
<img width="989" alt="Снимок экрана 2022-10-24 в 15 33 51" src="https://user-images.githubusercontent.com/99298812/197538303-2c126aa4-3841-48d7-81ed-ecfe8799c874.png">


# Visualization

The employ of [IIIF](https://iiif.io) made it possible to have a visual representation of our model. The International Image Interoperability Framework (IIIF) standard specifies two APIs that provide access to digital images and information (metadata). It not only defines a standarized method of describing and delivering images on the web, but it also helps, through metadata and consistent API, in solving the problem of replication of data, that could put at risk the quality and information about images.
A key aspect of a digital project should be interactivity, and we achieved this through the use of IIIF, Mirador and OpenSeaDragon. In order to make our project less academic and more interactive, we embedded a webpage where the user can play with images, different sizes and details of the illustrations. In this way, the visitor of our webpage can both read the texts and descriptions we made, but also explore him or herself the topic through the images, by zooming on the paintings and looking for details that could answer the research questions, following the timeline of the paintings from the most ancient to the most recent one, or surfing back and forth throughout the centuries. 
One of the main purposes of models and modelling is, in fact, enhance learning and understanding, at two different stages: in the creation of it and in its application and following manipulation. This means that not only the user can learn from it, but that we also did in creating our project. 

For what regards the webpage layout, we tried to respect as much as possible the UI/UX good principles, using headbars to facilitate the navigation through the website, labels on the images, buttons, declaration of the contents and also presentation of the creators, namely us. We also followed the FAIR principles in the creation of our project: Findability, Accessibility, Interoperability and Reusability were guaranteed by uploading everything on GitHub, were all the data and metadata are accessible, retreivable and reusable by anyone.   


# Conclusions 

The goal of this project was to use web technologies such as Mirador Viewer, OpenSeaDragon, GitHub repository, IIIF Images, and digital ontologies to visualize a representation of Lust in art. The main idea was to produce a creative digital project that stood out from the more academic ones. An interactive and unusual depiction of the representation of Lust has been created by combining colors, images of various sizes, brief descriptions, and pills on ideas and concepts. With this project, we hope to encourage the user to explore and think critically about the art in general and the representation of Lust in it. Lust in art can now be experienced not only through paintings or sculptures, but also through web technologies.


# Contributions 

The project was ideated and created by both of us in collaboration, the different tasks have been split as follow:

### Beatrice 
* Website design with html 
* OpenSeaDragon and Mirador 
* Conceptual map on Miro 
* Text descriptions 

### Anton 
* Manifest 
* Foaf.ttl and RDF 
* Text descriprions 
* Bibliography research 


# Tool used 

- OpenSeaDragon
- Mirador 
- IIIF 
- Brackets 
- Miro 
- RDF, Foaf.ttl


# Resources 

1.	Alexander, J., M., (2001) 'Beauties, Bawds and Bravura: The Critical History of Restoration Portraits of Women’, in _Painted Ladies: Women at the Court of Charles II_, eds Catherine MacLeod and Julia Marciari Alexander (London: National Portrait Gallery), pp. 62–71.
2.	Burke, J., (2006) _Sex and Spirituality in 1500s Rome: Sebastiano del Piombo's Martyrdom of Saint Agatha_, The Art Bulletin, 88:3, 482-495, DOI: 10.1080/00043079.2006.10786301
3.	Ciula, A., Eide, Ø., Marras, C., & Sahle, P. (2018), _Modelling: Thinking in Practice; An Introduction_. Historical Social Research, Supplement, 31, 7-29. doi: https://doi.org/10.12759/hsr.suppl.31.2018.7-29.
4.	Connell, R. W. (1987) _Gender and power_, Stanford, CA: Stanford University Press.  [Google Scholar]
5.	Dubois, D. 2001. _"Seeing the female body differently:" Gender issues in The Silence of the Lambs_. Journal of Gender Studies, [Taylor & Francis Online], [Web of Science ®], [Google Scholar]
7.	Flanders, J. and Jannidis, F. (eds) (2019) _The shape of data in the digital humanities: modeling texts and text-based resources._ London ; New York: Routledge, Taylor & Francis Group.
8.	Frueh, J., _'The Erotic as Social Security'_, Art Journal 53, no. 1 (March 1, 1994): 66–72, https://doi.org/10.1080/00043249.1994.10791609.
9.	_'Gender and Sexuality'_, Google Art and Culture, accessed October 23, 2022, https://artsandculture.google.com/usergallery/gender-and-sexuality/KAJCzenSqPEYJA
10.  Lynne Oliva, _'Art Lust: Desire and the Work of Picasso and Klimt'_, Psychoanalytic Perspectives 7, no. 2 (November 2010): 244–58, https://doi.org/10.1080/1551806X.2010.10473093.
11.  McCarty, W., _Modeling: A Study in Words and Meanings_, in <i> A Companion to Digital Humanities </i>, 254 - 270, 
 (2007), DOI:10.1002/9780470999875.ch19
12.  Pritchard, W. (2009) _‘Woman, that fair Copy’: gender and painting in English writing_, 1650–1700, Word & Image, 25:1, 75-84, DOI: 10.1080/02666280802048271
13.  Pruitt, D., C., _'It Rhymes with Lust? Matt Baker and the Ironic Politics of Race, Sex and Gender in the Golden Age'_, Journal of Graphic Novels and Comics 7, no. 2 (April 2, 2016): 197–209, https://doi.org/10.1080/21504857.2015.1135470.
14.	 Wertham, F. (2004) _Seduction of the Innocent_. Reprint, Laurel, NY: Main Road Books. [Google Scholar]



