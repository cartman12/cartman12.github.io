---
layout: post
published: true
title: Finding Exoplanets
subtitle: Supporting scientists in discovering new exoplanets
image: >-
  https://github.com/mohamad-ali-nasser/mohamad-ali-nasser.github.io/blob/master/img/transit_light_mohamad_ali_nasser_machine_learning.png?raw=true
---
## Supporting scientists in discovering new exoplanets


The project's objective was to source data from the TESS Telescope and to create a model, using Neural Networks, that identifies the likelihood that an object orbiting a star is an exoplanet or not. 
Furthermore, working with a front-end team, we created a user interface where we crowd source the identification process by giving users an option to vote on the likelihood that the transit light curves and intensity indicate that the star has exoplanets.

Initially, data sourcing proved to be complicated, it included one master file and several other files pertaining information about each star in different constellations. However, once we were able to source the complete data from multiple sources, both the labeled and the unlabeled, we were able to properly wrangle and clean the data.

For training, we built a Sequential model using the Keras library.

Below is a preview of the final web app: 

![transit light mohamad ali nasser machine learning Neural Networks]({{site.baseurl}}/img/transit_light_mohamad_ali_nasser_machine_learning.png)

![transit_light_mohamad_ali_nasser_machine_learning_2.png]({{site.baseurl}}/img/transit_light_mohamad_ali_nasser_machine_learning_2.png)


The following links lead to the website and code respectively.

[Finding Planets](https://findingplanets.netlify.com/)

Login:

user: testuser 

pass: testpass

[Github](https://github.com/BW-Finding-Planets)