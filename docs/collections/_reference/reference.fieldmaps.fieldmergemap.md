---
optionsClassName: FieldMergeMapOptions
optionsClassFullName: MigrationTools.Tools.FieldMergeMapOptions
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
                "FieldMapType": "FieldMergeMap",
                "ApplyTo": [
                  "*"
                ]
              }
            ]
          }
        }
      }
    }
  sampleFor: MigrationTools.Tools.FieldMergeMapOptions
- name: sample
  order: 1
  description: 
  code: >-
    {
      "MigrationTools": {
        "Version": "16.0",
        "CommonTools": {
          "FieldMappingTool": {
            "FieldMaps": [
              {
                "FieldMapType": "FieldMergeMap",
                "ApplyTo": [
                  "SomeWorkItemType"
                ],
                "formatExpression": "{0} \n {1}",
                "sourceFields": [
                  "Custom.FieldA",
                  "Custom.FieldB"
                ],
                "targetField": "Custom.FieldC"
              }
            ]
          }
        }
      }
    }
  sampleFor: MigrationTools.Tools.FieldMergeMapOptions
- name: classic
  order: 3
  description: 
  code: >-
    {
      "$type": "FieldMergeMapOptions",
      "sourceFields": [
        "Custom.FieldA",
        "Custom.FieldB"
      ],
      "targetField": "Custom.FieldC",
      "formatExpression": "{0} \n {1}",
      "ApplyTo": [
        "*",
        "SomeWorkItemType"
      ]
    }
  sampleFor: MigrationTools.Tools.FieldMergeMapOptions
description: missing XML code comments
className: FieldMergeMap
typeName: FieldMaps
architecture: 
options:
- parameterName: ApplyTo
  type: List
  description: missing XML code comments
  defaultValue: missing XML code comments
- parameterName: formatExpression
  type: String
  description: missing XML code comments
  defaultValue: missing XML code comments
- parameterName: sourceFields
  type: List
  description: missing XML code comments
  defaultValue: missing XML code comments
- parameterName: targetField
  type: String
  description: missing XML code comments
  defaultValue: missing XML code comments
status: missing XML code comments
processingTarget: missing XML code comments
classFile: /src/MigrationTools.Clients.TfsObjectModel/Tools/FieldMappingTool/FieldMaps/FieldMergeMap.cs
optionsClassFile: /src/MigrationTools/Tools/FieldMappingTool/FieldMaps/FieldMergeMapOptions.cs

redirectFrom:
- /Reference/FieldMaps/FieldMergeMapOptions/
layout: reference
toc: true
permalink: /Reference/FieldMaps/FieldMergeMap/
title: FieldMergeMap
categories:
- FieldMaps
- 
topics:
- topic: notes
  path: /docs/Reference/FieldMaps/FieldMergeMap-notes.md
  exists: false
  markdown: ''
- topic: introduction
  path: /docs/Reference/FieldMaps/FieldMergeMap-introduction.md
  exists: false
  markdown: ''

---