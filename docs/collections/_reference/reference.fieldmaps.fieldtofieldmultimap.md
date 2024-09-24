---
optionsClassName: FieldToFieldMultiMapOptions
optionsClassFullName: MigrationTools.Tools.FieldToFieldMultiMapOptions
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
                "FieldMapType": "FieldToFieldMultiMap",
                "ApplyTo": [
                  "*"
                ]
              }
            ]
          }
        }
      }
    }
  sampleFor: MigrationTools.Tools.FieldToFieldMultiMapOptions
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
                "FieldMapType": "FieldToFieldMultiMap",
                "ApplyTo": [
                  "SomeWorkItemType",
                  "SomeOtherWorkItemType"
                ],
                "SourceToTargetMappings": {
                  "SourceField1": "TargetField1",
                  "SourceField2": "TargetField2"
                }
              }
            ]
          }
        }
      }
    }
  sampleFor: MigrationTools.Tools.FieldToFieldMultiMapOptions
- name: classic
  order: 3
  description: 
  code: >-
    {
      "$type": "FieldToFieldMultiMapOptions",
      "SourceToTargetMappings": {
        "SourceField1": "TargetField1",
        "SourceField2": "TargetField2"
      },
      "ApplyTo": [
        "*",
        "SomeWorkItemType",
        "SomeOtherWorkItemType"
      ]
    }
  sampleFor: MigrationTools.Tools.FieldToFieldMultiMapOptions
description: missing XML code comments
className: FieldToFieldMultiMap
typeName: FieldMaps
architecture: 
options:
- parameterName: ApplyTo
  type: List
  description: missing XML code comments
  defaultValue: missing XML code comments
- parameterName: SourceToTargetMappings
  type: Dictionary
  description: missing XML code comments
  defaultValue: missing XML code comments
status: missing XML code comments
processingTarget: missing XML code comments
classFile: /src/MigrationTools.Clients.TfsObjectModel/Tools/FieldMappingTool/FieldMaps/FieldtoFieldMultiMap.cs
optionsClassFile: /src/MigrationTools/Tools/FieldMappingTool/FieldMaps/FieldtoFieldMultiMapOptions.cs

redirectFrom:
- /Reference/FieldMaps/FieldToFieldMultiMapOptions/
layout: reference
toc: true
permalink: /Reference/FieldMaps/FieldToFieldMultiMap/
title: FieldToFieldMultiMap
categories:
- FieldMaps
- 
topics:
- topic: notes
  path: /docs/Reference/FieldMaps/FieldToFieldMultiMap-notes.md
  exists: false
  markdown: ''
- topic: introduction
  path: /docs/Reference/FieldMaps/FieldToFieldMultiMap-introduction.md
  exists: false
  markdown: ''

---