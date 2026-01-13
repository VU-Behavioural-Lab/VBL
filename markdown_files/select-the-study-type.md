# Select the study type

After selecting **"Add New Study"**, you will have the option to pick from several study types. 

Select {% if study_type == 'lab' %}**"Standard Study"**{% endif %} {% if study_type == 'online' %}**"Online External Study"**{% endif %} on this page to start your study.

{% if study_type == 'lab' %}
>[!screenshot] <i class="fa-solid fa-camera"></i> Image: Select the Study Type in SONA  
><img src="/static/images/study-type-standard.png" alt="Add New Study" class="responsive-image">
{% endif %} 

{% if study_type == 'online' %}
>[!screenshot] <i class="fa-solid fa-camera"></i> Image: Select the Study Type in SONA  
><img src="/static/images/study-type-online.png" alt="Add New Study" class="responsive-image">
{% endif %}