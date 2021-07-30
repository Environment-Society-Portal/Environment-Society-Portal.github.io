# Environment & Society Portal

The [Environment & Society Portal](http://www.environmentandsociety.org/) is the open-access digital publication platform and archive of the [Rachel Carson Center for Environment and Society](http://www.carsoncenter.uni-muenchen.de/index.html) (RCC), a nonprofit joint initiative of the [LMU (University of Munich)](http://www.en.uni-muenchen.de/index.html) and the [Deutsches Museum](http://www.deutsches-museum.de/en), funded by the [German Federal Ministry for Education and Research](https://www.bmbf.de/bmbf/en/home/home_node.html). As such, it reflects the research themes of the Rachel Carson Center and its [fellows](http://www.carsoncenter.uni-muenchen.de/fellows/index.html), who are international experts in related fields. 

Following Rachel Carson's example, the Environment & Society Portal makes environmental research accessible to the public and diverse scholarly communities. Today, with much research locked behind paywalls, the Portal works to make knowledge open and discoverable. Its peer-reviewed OA e-journal [_Arcadia_](http://www.environmentandsociety.org/arcadia) showcases the work of early-career researchers in environmental history; [29 virtual exhibitions](http://www.environmentandsociety.org/exhibitions) present the work of our fellows to broad public audiences; the multimedia library presents books, films, journal articles, and archival documents. The content is made discoverable with three interactive tools (map, timeline, keyword explorer), reaching more than one million unique users. 

The portal is built on the open-source Content Management Framework Drupal (Version 7), integrating various other open-source libraries, plugins and technologies.

## Server Setup

* Linux <https://www.linuxfoundation.org>
* MySQL <https://www.mysql.com> / MariaDB <https://mariadb.org>
* Apache HTTP Server <https://httpd.apache.org>
* PHP <https://www.php.net>

## Content Management

The portal’s content structure and editorial backend are built on Drupal’s versatile and flexible site building tools.

* CMS: Drupal 7 <https://drupal.org>
* Site building (Content types, Taxonomy, Views etc.)
* Custom editorial workflows and roles
* Media library based on the Drupal Scald Module <https://www.drupal.org/project/scald>
* Various improvements to the editorial experience
* Media License Management

## Frontend

A responsive redesign of the Environment & Society Portal was implemented in 2017 to further improve the user experience on all kinds of devices.

* Radix Theme <https://www.drupal.org/project/radix>
* Bootstrap Frontend Framework (Version 3) <https://getbootstrap.com>
* Open-source tools for a streamlined theme development:
  * Sass <https://sass-lang.com>
  * Gulp.js <https://gulpjs.com>
  * npm <https://www.npmjs.com>
* Automatic PDF-generation with mPDF <https://github.com/mpdf/mpdf>

## Portal Search

The [Portal search](http://www.environmentandsociety.org/search) provides a faceted search interface that allows you to filter by keyword, content type, media type, theme, region or collection. It integrates an Apache Solr Server to achieve a fast response time and an improved user experience.

* Apache Solr Search <https://solr.apache.org/>
* Drupal Search API <https://www.drupal.org/project/search_api>
* Drupal Search API Solr <https://www.drupal.org/project/search_api_solr>

## Virtual Exhibitions

Curated by experts in the environmental humanities, [Virtual Exhibitions](http://www.environmentandsociety.org/exhibitions) put digitized material into interpretive contexts.The exhibitions can be fully managed within a custom editorial backend including reusable components and integration of Open-source libraries like TimelineJS and Masonry.js.

* Masonry.js <https://github.com/desandro/masonry>
* TimelineJS <https://timeline.knightlab.com>

## Keyword Explorer

The [Keyword Explorer](http://www.environmentandsociety.org/tools/keywords) lets you browse Portal content by themes and tags, narrowing your results to content matching your chosen keywords. A custom user interface built with D3.js combined with a fast responding Solr server make the Keyword explorer an intuitive exploration tool.

* Apache Solr Search <https://solr.apache.org>
* D3.js <https://d3js.org>

## Portal Timeline

The interactive [timeline](http://www.environmentandsociety.org/tools/timeline) allows you to browse Environment & Society Portal content chronologically. It is built on the Open-source timeline by the Wellcome Library with further customizations and improvements for large data sets.

* Wellcome Timeline <https://github.com/wellcometrust/timeline>

## Portal Map

The [Map Viewer](http://www.environmentandsociety.org/tools/map) displays Portal content by geographic location and allows you to filter by keyword, content type or theme.
Backbone.js <https://backbonejs.org> 

* Apache Solr Search <https://solr.apache.org>
* Google Maps Integration
