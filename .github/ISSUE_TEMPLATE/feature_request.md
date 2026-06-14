---
name: Feature request
description: Suggest a new feature or improvement
title: "[Feature]: "
labels: ["enhancement"]
body:
  - type: markdown
    attributes:
      value: |
        Suggest features that fit offline single-player modding, testing, or quality-of-life use.
  - type: textarea
    id: feature
    attributes:
      label: Feature description
      description: What do you want added or improved?
    validations:
      required: true
  - type: textarea
    id: use-case
    attributes:
      label: Use case
      description: Why would this be useful in Retrowave?
    validations:
      required: true
  - type: dropdown
    id: category
    attributes:
      label: Category
      options:
        - Menu/UI
        - Money tools
        - Vehicle upgrades
        - Vehicle unlocks
        - Gameplay utilities
        - Traffic settings
        - Statistics/progression
        - Other
    validations:
      required: true
  - type: checkboxes
    id: scope
    attributes:
      label: Scope check
      options:
        - label: This request is for offline single-player use.
          required: true
        - label: This request does not target multiplayer, public leaderboards, or competitive systems.
          required: true
