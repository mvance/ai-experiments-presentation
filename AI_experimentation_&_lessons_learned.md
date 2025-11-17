 AI-experimentation & lessons learned

# progression

## Readme Driven Development (2010)

## bookmarklets

### small to medium Javascript scripts contained (or wrapped) in a bookmark

#### have access to lots of Web APIs

#### can include lots of JS libraries via CDNs

#### can wrap externally hosted custom code

##### easy to host on gist.github.com

### 📺"sub" (search hub)

#### YubNub clone

##### search shortcuts for easy/quick navigation

### 📺book suggestion automator bookmarklet

#### small reduction in friction helps increase my usage

### 📺"listenwise" TTS bookmarklet

#### Edge TTS sounds good at first, but it's quirky

### scrape book title and author to find book on GoodReads

### 📺"bub" (book hub)

## CLI tools

### web scraping

#### CLIs

##### 🖼️pin_pop_xref

#### Playwright based scraping

##### tried a scraping-specific toolset, but couldn't resolve dependencies even with `uv` and Ai help

### 🖼️transcribe audio snippets based on exported bookmark timestamps

#### my first AI-assisted Python

##### whisper.cpp

#### LLM helped navigate `uv` for easier/cleaner dependency management

### API backup utilities

### reverse engineering pocketcast API

#### open source mobile apps, but no documented API

##### used to create multiple CLI tools to fetch different API data

##### generated documentation for parts of the API

## single page apps

### 📺custom mp3 player

#### to correlate audio book transcriptions to ebook passages for highlighting

#### failed attempt to create VLC plugin using Lua

#### use CDN-hosted dependencies to avoid complex build steps

### 📺"spelldle" game

#### wordle + spelling bee

#### many failed attempts using Claude and REPLIT

#### an early foray into spec-driven development

##### went from getting ~50% of what I wanted to ~80%

##### still surprisingly frustrating

##### eventually tried creating reference examples

#### 🖼️test suite helped considerably

## Chrome extension

### tool to deal lots of open tabs

#### find and close

##### duplicate tabs

##### already bookmarked

## automation

### book highlight tagging

#### ML toolchain complexity

#### local models

##### ollama

##### API calling to local and remote LLMs was **MUCH** easier

# lessons learned

## start small

### don't boil the ocean

## keep it fun

### avoid bloat

### avoid complex hosting

### paradox

#### find a balance between

##### keep it simple and DIY
 
don't reinvent the wheel


## lean on the LLMs for logistical non-coding tasks

### debugging

#### ask the LLM to help you debug manually

#### ask the LLM to add debugging code

## keep a running list of project ideas handy

## use LLMs to summarize

### documentation

### code

## use LLMs to help write

### prompts

### specifications

### documentation

#### README.md

### commit messages

### tests

## use LLMs to code

### LLMs are good at JSON parsing

### reference implementations / PoCs

### data gathering

### data analysis

### CLI one-liners

#### JSON parsing w/jq

## circle back to old projects to apply new lessons learned

### bookmarklet state passing via URL arguments

### bookmarklet state passing localStorage

### bookmarklet state passing via URL hash

## don't be afraid

### try something new

#### languages

##### python

##### Google Apps Script

#### tools

##### OrbStack

##### Ollama

##### openweb ui

#### APIs

##### text-to-speech

###### web speech api

###### Edge TTS

###### Kokoro

###### OpenAI

##### transcription

###### Whisper.cpp

#### AI models

##### large & small

##### local & cloud

##### checkout out API/model router services

###### openrouter & others

#### libraries

### put a project on hold or abandon it altogether

#### ❌failures & semi-failures

##### automator script to override Mac OS TTS behavior

###### multiple APIs returned "definitive" answers about the API differently

###### overriding default behavior proved tricky

##### reviving `drush qd` quick drupal from earlier versions of Drush

###### had trouble getting existing drush tests to run successfully

##### VLC plugin

###### lots of boilerplate code

###### didn't seem like a particularly beginner friendly ecosystem

##### reader-mode bookmarklet based on defuddle library

###### found existing implementations doing what I wanted before I got very far

##### reverse engineering Kagi Universal Summarizer prompt

###### would require a lot of infrastructure to support all the formats Kagi already does

##### countless attempts before I got spelldle stable

###### failed at a couple of creative "simple" backend implementations

##### Edge TTS

###### technically it works and I learned a lot implementing it, but it's too glitchy for regular use

##### book highlight tagging

###### python machine learning libraries were very tricky to get running
 
probably needed a bigger pre-tagged data set to learn from


#### ill-fated attempts don't seem as bothersome

### make mistakes

#### LLMs can usually help you clean up the mess/aftermath

### experiment

### change strategy

#### if an LLM fails 2-3 times, it's time to change strategy

### get 2nd, 3rd, etc. opinions from different models

# juggling metaphor

## you don't juggle torches on day one

### I could tell you how, but that doesn't get you very far

# what next

## sdd tools
 
- Spec-Kit by GitHub

 
- Kiro by AWS

 
- Tessl by Tessl

 
- BMad Method (BMM) by BMad Code


## natural language development

## TDD
