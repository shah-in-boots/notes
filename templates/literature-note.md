---
category: reference
citekey: {{citekey}}
stage: working
year: {{date | format('YYYY')}}
---


# {{title}}

{% persist "tags" %}{% if isFirstImport %}
#literature
{% endif %}
{% endpersist %}

> [!tip]  
> **Zotero** = {{pdfZoteroLink}}
> **Citation Key** = @{{citekey}}

> [!cite]
> {{bibliography}}

{% if abstractNote %}
## Abstract
{{abstractNote}}
{% endif %}

# Annotations
{% persist "annotations" %}  
{% set newAnnotations = annotations | filterby("date", "dateafter", lastImportDate) %}  

{% if newAnnotations.length > 0 %}  
###### Imported: {{importDate | format("YYYY-MM-DD h:mm a")}}  
{% for annotation in newAnnotations %}  
> {{annotation.annotatedText}}  
{% if annotation.imageRelativePath %} 
![{{annotation.imageRelativePath}}]({{annotation.imageRelativePath}})
{% endif %}
{% if annotation.comment %}
*{{annotation.comment}}*
{% endif %}
{% endfor %}  

{% endif %}  
{% endpersist %}

# Notes
{% persist "notes" %}{% if isFirstImport %}
{% endif %}
{% endpersist %}