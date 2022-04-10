---
layout: page
title: What's New
include_in_header: true
---

# Changelog
The Sharp Cooking team makes frequent updates to keep up with the latest iOS and Android capabilities and enhance your experience. See below for version release notes.

{% for item in site.data.releasenotes_enUS reversed %}
## Version {{item.version}} {% if item.latest %}(Latest){% endif %}

### What's New
{% for newItem in item.new %}
- {{newItem}}
{% endfor %}

### Known issues
{% for knownIssue in item.knownIssues %}
- {{knownIssue}}
{% endfor %}
{% endfor %}

## **Roadmap**
> Below features are currently being evaluated or under development. The development team cannot guarantee that all features listed here will be delivered in the next version.

- (In Progress - Preview in v1.7) Focus mode
  - Remove all distractions and focus on the recipe
  - Voice guidance
  - Step timers
- (In Progress - v1.7) Recipe Printing
- (In Progress - v1.7) Recipe image display with pinch to zoom
- (Not Started) Picture gallery in a recipe
- (Not Started) Automatic storage management of app images
- (Not Started) Unit of measure conversions
  - From Imperial to metric system and vice-versa
- (Not Started) Alternative ingredients
  - No butter? You can use x amount of olive oil as a replacement
