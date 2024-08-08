---
title: '{{ strings.Title .File.ContentBaseName }}'
layout: '{{ strings.ToLower .File.ContentBaseName }}'
url: '/{{  strings.ToLower .File.ContentBaseName | inflect.Singularize  }}'
summary: "archives"
---