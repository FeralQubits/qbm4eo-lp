## Welcome to QBM4EO

### Supervised quantum machine learning system for Earth land cover understanding.


### The solution 

<div style="text-align: justify"> 
The surface of the Earth is a constantly changing landscape. Human activity such as urban development, agriculture, mining and geoengineering impacts Earth surface significantly. Currently, these changes can be observed from the Earth’s orbit using a multitude of sensors deployed on satellites like the Sentinel constellation. These satellites provide Earth observation information from multispectral sensors. This information can be used to determine land-use classes. These classes provide refined, useful information about a particular section of the Earth surface, which can be used to monitor changes occurring on the surface. 
</div>
&nbsp;
<img title="a title" alt="Alt text" src="/img/autoencoder.png">

&nbsp;

### Description of the SOLUTION 


- In our solution, we will provide an algorithm, and its implementation, for training machine learning systems using quantum annealing devices (specific purpose quantum computers) for multilabel land-use classification. As a proof-of-concept, we will also provide pretrained models for a selected set of data. 

- **The solution** — following the software-as-a-service model — will consist of a machine learning system deployed in the cloud, accessible by an API. 

- **The client** will be able to request the training of its model on the Sentinel-2 multispectral data they select and demand the land-use labels for a particular set of land patches.

- **The solution will** use the **D-Wave quantum annealer** during the training process. The annealer will be used in the most difficult part of the machine learning pipeline. Namely, in generation of the multispectral data representation and multilabel classification. 

- We aim to use a two-stage data transformation process. In the first stage, the data will be transformed from its natural representation into a binary sequence, which is more natural for quantum machines. This binary string should encode most of the relevant information about a hyperspectral data cube patch. 

### Consumer Needs

<div style="text-align: justify"> 
QBM4EO could be a well-fitted solution to consumer needs in the Polish market. We have many problems in which EO analyses could be helpful. One of these is the effects of climate change, especially drought. For example, cumulative costs of drought in 2018 in Poland was assessed at about 2,6 billion PLN. The next problem is a lack of spatial plans. According to Statistic Poland, 42% of houses in Poland are built without a spatial plan and require special agreement. This phenomenon is the main obstacle in fluent progress in the Polish real estate market. We describe only a few main problems in which a developed solution could be helpful to solve these, but there are many other economic areas where QBM4EO could be used.
</div>

&nbsp;

### Contact
 qbm4eo@centrumetos.pl