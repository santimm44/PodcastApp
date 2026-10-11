# Podcast App

## Intended use

The application is intended to be used for offline listening.

## Features aimed in this application

### MVP

* RSS Link searching
* play a single podcast episode at a time with no queue
* Display episode information
* Download episode on local storage

### Beyond MVP

* Create queue for podcasts
* subscribe to a podcast
* create event notifications when new episodes are released
* create playlists
* drag and drop items in queue to reorder the list of episodes
* advance options for downloading episodes:
  * Compresion options for the episode
  * Download every new episode toggle
  * Select file path for downloads

## General Layout

### app.core

Application logic, podcast and episode models, playback behavior

### app.infrastructure

SQLite DB, downloaded files, RSS Fetching, data persistence

### app.ui

WPF windows. layouts, controls, user interaction