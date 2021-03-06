# gitbucket-label-kanban-plugin
[![Build Status](https://travis-ci.org/kasancode/gitbucket-label-kanban-plugin.svg?branch=master)](https://travis-ci.org/kasancode/gitbucket-label-kanban-plugin)

A [GitBucket](https://github.com/gitbucket/gitbucket) plugin for Kanban-style issue management.  
The lanes are labels prefixed with "@", milestones, priorities and assignees.   

![Screenshot](./doc/screenshot.png)


## Installation

Download jar file from [the release page](https://github.com/kasancode/gitbucket-label-kanban-plugin/releases) and put it into `GITBUCKET_HOME/plugins`.

## Version

Plugin version|GitBucket version
:---|:---
2.0.x|4.26.x -
1.0.x|4.26.x - 4.29.x

## Build from source

`$ sbt package`

## Usage


1. Click "Add lane" button to add lanes (prefixed labels).  
![labelList](./doc/labels.png)

1. Select the lane type.   
![lanes](./doc/keys.png)

1. Drag an Issue to another lane.   
![dragging](./doc/dragging.png)

