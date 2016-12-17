---
layout: single
permalink: /
author_profile: true
date:
---

## Keywords

Machine Learning, Neuroimaging, Scientific computing, Software Engineering, Bioinformatics, High Dimensional Data.
Machine Learning in Neuroimaging

## Summary

I am a research scientist at [NeuroSpin/CEA](http://i2bm.cea.fr/drf/i2bm/english/Pages/NeuroSpin/Presentation.aspx), Paris-Saclay ([map](https://goo.gl/maps/EHnp1JiFkHU2)): a MRI neuroimaging center within the [CEA](http://www.cea.fr/english) (Commissariat à l'énergie atomique, Saclay, France). I am developing machine learning algorithms (classification/regression) and multivariate/univariate statistics analysis tools. Those algorithms aim to provide computer-aided diagnosis/prognosis tools or biomarkers discovering methods for brain diseases. I am now integrating genetic (DNA array) together with neuroimaging. The specificity of such data is their large dimension which requires new specific feature extraction/selection and sparse and structured machine learning (convex optimisation) algorithms.

## Scientific Computing

I am a core contributor of [ParsimonY](https://github.com/neurospin/pylearn-parsimony) a Machine Learning library in Python dedicated to high dimensionnal structured input data such as brain images (MRI, PET) or genetics data (DNA, RNA).

## (Former) Students in (Co-)Supervision

- Pietro Gori (Post-doc, 2016-now) together with JF Mangin and J Houenou
- Amicie de Pierrefeu (PhD, 2016-now) together with Philippe Ciuciu
- Fouad Hadj Selem (Post-doc, 2013-2015) together with V Frouin and JF Mangin
- Tommy Lofstedt (Post-doc, 2013-2015) together with V Frouin
- Mathieu Dubois (Post-doc, 2013-2014) together with V Frouin
- Clémence Pinaud (Engineer trainee 2014)
- Jinpeng Li (Research Engineer 2013-2014)
- Cecilia Damon (PhD defended on 2011) together with JB Poline
- Edith Lefloch (PhD defended on 2012) together with V Frouin





{% include base_path %}

<h3 class="archive__subtitle">{{ site.data.ui-text[site.locale].recent_posts }}</h3>

{% for post in paginator.posts %}
  {% include archive-single.html %}
{% endfor %}

{% include paginator.html %}

