---
name: "🎬 Application Issue Report"
about: Report an issue in FlowFlix
title: "[BUG] "
labels: bug
assignees: ''

body:
  - type: input
    id: bug_title
    attributes:
      label: Bug Title
      description: Provide a short and descriptive title for the bug
      placeholder: Example: App crashes when opening movie details

  - type: textarea
    id: steps_to_reproduce
    attributes:
      label: Steps to Reproduce
      description: List the steps to reproduce the issue
      placeholder: |
        1. Open the app
        2. Go to the "Movies" section
        3. Tap on any movie
        4. App crashes

  - type: textarea
    id: bug_description
    attributes:
      label: Bug Description
      description: Explain what the bug is and what you expected to happen
      placeholder: Describe the issue in detail here

  - type: textarea
    id: screenshots_or_recordings
    attributes:
      label: Screenshots / Recordings
      description: Attach any screenshots or recordings if available
      placeholder: Add links to images or video recordings here

  - type: input
    id: app_version
    attributes:
      label: App Version
      description: Specify the version of FlowFlix you are using
      placeholder: Example: 1.0.3

  - type: dropdown
    id: system
    attributes:
      label: System / Platform
      description: Select the platform you are using
      options:
        - Android
        - Android TV
        - iOS
        - macOS
        - Windows
        - Linux
