---
permalink: /Kyles-Cookbook.html
title: Kyle's Cookbook
created: Tu 22.05.2022, 17:06:11
author: Kyle Klus
categories: Kyles-Cookbook
layout: post_index
backlink: /
tags: status/not_tree, status/needs_work,
aliases:
---

{% assign mocs_cooking = site.categories.cooking | where: "categories", "moc" %}
{% if mocs_cooking != blank %}

## Cooking

{% for post in mocs_cooking %}

- [{{post.title}}]({{post.url}})

{% endfor %}
{% endif %}

{% assign mocs_baking = site.categories.baking | where: "categories", "moc" %}
{% if mocs_baking != blank %}

## Baking

{% for post in mocs_baking %}

- [{{post.title}}]({{post.url}})

{% endfor %}
{% endif %}
