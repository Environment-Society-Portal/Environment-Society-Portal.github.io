# Environment & Society Portal

The Environment & Society Portal is a gateway to open access resources on the human-environment relationship. It makes environmental humanities research accessible to academic communities and the interested public worldwide, reaching more than one million users. The portal is built on the Open-source Content Management Framework Drupal (Version 7), integrating various other Open-source libraries, plugins and technologies.

## Server Setup

* Linux <https://www.linuxfoundation.org>
* MySQL <https://www.mysql.com / MariaDB https://mariadb.org>
* Apache HTTP Server <https://httpd.apache.org>
* PHP <https://www.php.net/>

## Content Management

The portal’s content structure and editorial backend are built on Drupal’s versatile and flexible site building tools.

* CMS: Drupal 7 https://drupal.org 
* Site building (Content types, Taxonomy, Views etc.)
* Custom editorial workflows and roles
* Media library based on the Drupal Scald Module https://www.drupal.org/project/scald 
* Various improvements to the editorial experience
* Media License Management

## Frontend

A responsive Redesign of the Environment & Society Portal was implemented in 2017 to further improve the user experience on all kinds of devices.

* Radix Theme https://www.drupal.org/project/radix
* Bootstrap Frontend Framework (Version 3) https://getbootstrap.com/ 
* Open-source tools for a streamlined theme development:
  * Sass https://sass-lang.com/ 
  * Gulp.js https://gulpjs.com/
  * npm https://www.npmjs.com/ 
* Automatic PDF-generation with mPDF https://github.com/mpdf/mpdf 

## Portal Search

The Portal search provides a faceted search interface that allows you to filter by keyword, content type, media type, theme, region or collection. It integrates an Apache Solr Server to achieve a fast response time and an improved user experience.

* Apache Solr Search https://solr.apache.org/ 
* Drupal Search API https://www.drupal.org/project/search_api 
* Drupal Search API Solr https://www.drupal.org/project/search_api_solr 

## Virtual Exhibitions

Curated by experts in the environmental humanities, Virtual Exhibitions put digitized material into interpretive contexts.The exhibitions can be fully managed within a custom editorial backend including reusable components and integration of Open-source libraries like TimelineJS and Masonry.js.

* Masonry.js https://github.com/desandro/masonry 
* TimelineJS https://timeline.knightlab.com/ 

## Keyword Explorer

The Keyword Explorer lets you browse Portal content by themes and tags, narrowing your results to content matching your chosen keywords. A custom user interface built with D3.js combined with a fast responding Solr server make the Keyword explorer an intuitive exploration tool.

* Apache Solr Search https://solr.apache.org/ 
* D3.js https://d3js.org/ 

## Portal Timeline

The interactive timeline allows you to browse Environment & Society Portal content chronologically. It is built on the Open-source timeline by the Wellcome Library with further customizations and improvements for large data sets.

* Wellcome Timeline https://github.com/wellcometrust/timeline 

## Portal Map

The Map Viewer displays Portal content by geographic location and allows you to filter by keyword, content type or theme.
Backbone.js https://backbonejs.org/ 

* Apache Solr Search https://solr.apache.org/ 
* Google Maps Integration
