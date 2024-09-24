---
optionsClassName: TreeToTagFieldMapOptions
optionsClassFullName: MigrationTools.Tools.TreeToTagFieldMapOptions
configurationSamples:
- name: defaults
  order: 2
  description: 
  code: >-
    {
      "MigrationTools": {
        "Version": "16.0",
        "CommonTools": {
          "FieldMappingTool": {
            "FieldMaps": [
              {
                "FieldMapType": "TreeToTagFieldMap",
                "ApplyTo": [
                  "*"
                ]
              }
            ]
          }
        }
      }
    }
  sampleFor: MigrationTools.Tools.TreeToTagFieldMapOptions
- name: sample
  order: 1
  description: 
  code: There is no sample, but you can check the classic below for a general feel.
  sampleFor: MigrationTools.Tools.TreeToTagFieldMapOptions
- name: classic
  order: 3
  description: 
  code: >-
    {
      "$type": "TreeToTagFieldMapOptions",
      "toSkip": 0,
      "timeTravel": 0,
      "ApplyTo": [
        "*"
      ]
    }
  sampleFor: MigrationTools.Tools.TreeToTagFieldMapOptions
description: missing XML code comments
className: TreeToTagFieldMap
typeName: FieldMaps
architecture: 
options:
- parameterName: ApplyTo
  type: List
  description: missing XML code comments
  defaultValue: missing XML code comments
- parameterName: timeTravel
  type: Int32
  description: missing XML code comments
  defaultValue: missing XML code comments
- parameterName: toSkip
  type: Int32
  description: missing XML code comments
  defaultValue: missing XML code comments
status: missing XML code comments
processingTarget: missing XML code comments
classFile: /src/MigrationTools.Clients.TfsObjectModel/Tools/FieldMappingTool/FieldMaps/TreeToTagFieldMap.cs
optionsClassFile: /src/MigrationTools/Tools/FieldMappingTool/FieldMaps/TreeToTagFieldMapOptions.cs

redirectFrom:
- /Reference/FieldMaps/TreeToTagFieldMapOptions/
layout: reference
toc: true
permalink: /Reference/FieldMaps/TreeToTagFieldMap/
title: TreeToTagFieldMap
categories:
- FieldMaps
- 
topics:
- topic: notes
  path: /docs/Reference/FieldMaps/TreeToTagFieldMap-notes.md
  exists: false
  markdown: ''
- topic: introduction
  path: /docs/Reference/FieldMaps/TreeToTagFieldMap-introduction.md
  exists: false
  markdown: ''

---