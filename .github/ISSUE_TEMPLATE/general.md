name: General task / question
description: Use this template for general work items.
title: "[Task] "
labels: [enhancement]
body:
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to fill this out.
  - type: textarea
    id: what
    attributes:
      label: What would you like to be added or changed?
      description: A clear and concise description of the task.
    validations:
      required: true
  - type: textarea
    id: why
    attributes:
      label: Why is this needed?
    validations:
      required: false
  - type: textarea
    id: acceptance
    attributes:
      label: Acceptance criteria
      description: What should be true after this work is done?
    validations:
      required: true
  - type: textarea
    id: additional
    attributes:
      label: Additional context
    validations:
      required: false

