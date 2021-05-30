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

- (Released in v1.3) show default recipes on first install
- (Released in v1.3) save last multiplier used for each recipe
- (Released in v1.4) share recipe with image
- (Released in v1.5) sorting options
- (Released in v1.5) dark mode
- (Not Started) Picture gallery in a recipe
- (Not Started) Automatic storage management of app images
- (Not Started) Unit of measure conversions
  - From Imperial to metric system and vice-versa
- (Not Started) Alternative ingredients
  - No butter? You can use x amount of olive oil as a replacement
