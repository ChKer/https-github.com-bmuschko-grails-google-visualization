[![Travis CI build status](https://travis-ci.org/bmuschko/grails-google-visualization.svg)](https://travis-ci.org/bmuschko/grails-google-visualization)
# Grails Google Visualization plugin

## Overview

[This Grails plugin](http://grails.org/plugin/google-visualization) provides a taglib for the interactive charts of the [Google Visualization API](https://developers.google.com/chart/).

## Documentation
You can find the full documentation in the corresponding GitHub wiki [here](https://github.com/bmuschko/grails-google-visualization/wiki).

## News
- **December 7, 2016**: Release version 2.2.1: Reverted changes introduced in release 2.1.1 as per issue #67
- **September 15, 2016**: Release version 2.2 (not recommended): new config paramater `google.maps.key` required to use Google Map based visualization as mentioned in issue #65.
- **August 21, 2016**: Release version 2.1.1 (not recommended): renames url mapping file to avoid conflicts as stated in issue #63.
- **August 17, 2016**: Release version 2.1 with bugfix for issue #54 and added support for AnnotationChart.
- **October 09, 2015**: Release version 2.0 providing Grails 3 support.
- **January 07, 2015**: Bug fix release 1.0.1 to add "title" config option to the Calendar chart.
- **January 04, 2015**: We are pleased to announce the release of version 1.0 with quite a few changes, that potentially could present some backward compatibility issues. Please check the changelog for more details: https://github.com/bmuschko/grails-google-visualization/wiki/changelog

## Features
* Supports the following visualizations: Annotated Time Line, Annotation Chart, Area Chart, Bar Chart, Bubble Chart, Candlestick Chart, Column Chart, Combo Chart, Gauge, Geo Chart Geo Map, Intensity Map, Line Chart, Map, Motion Chart, Organizational Chart, Pie Chart, Scatter Chart, Stepped Area Chart, Table Chart, Time Line Chart and Tree Map. See the [gallery](https://developers.google.com/chart/interactive/docs/gallery) for more information.
* Implements redesigned charts (Area, Bar, Bubble, Candlestick, Column, Combo, Line, Pie, Scatter and Stepped Area Charts) from the previously known as "Core Chart package" as well as the deprecated versions.
* Provides implementations for [table formatters](https://developers.google.com/chart/interactive/docs/gallery/table#Formatters) TableArrowFormat, TableBarFormat, TableColorFormat, TableDateFormat, TableNumberFormat and TablePatternFormat.
* Visualization [Event Handling](https://developers.google.com/chart/interactive/docs/events).
* Provides support for [Data Tables Roles](https://developers.google.com/chart/interactive/docs/roles) (since version 1.0)
