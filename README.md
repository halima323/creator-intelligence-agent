# Creator Intelligence Agent

An AI-powered automation built with **n8n** to automate YouTube creator discovery, research, qualification, and reporting.

## Problem

Finding suitable YouTube creators manually involved searching, collecting channel data, checking activity, filtering creators, and organizing the final results.

This process could take approximately **6–7 hours** manually.

## Solution

I built an end-to-end automation that handles the creator research process automatically.

**Creator Discovery → Data Extraction → Deduplication → Enrichment → Activity Analysis → AI Analysis → Qualification → Google Sheets → Email**

## What It Does

* Discovers YouTube creators based on defined criteria
* Collects and processes creator data through API requests
* Removes duplicate creators
* Enriches channel and activity information
* Uses **Google Gemini** for AI-powered information extraction
* Filters and qualifies creators based on predefined criteria
* Stores qualified creators in Google Sheets
* Sends the final results through email

## Tech Stack

**n8n · APIs · Google Gemini · Google Sheets · Gmail**

## Project Demo

### Workflow

[▶️ Watch the workflow demonstration](./workflowoverview.mp4)

Shows the complete n8n automation and its processing stages.

### Sample Result

[▶️ View the creator intelligence result](./Creators%20sample.mp4)

Shows an example of the creator data produced by the automation.

## Outcome

Automated a repetitive **6–7 hour creator research process** into a structured, repeatable workflow, reducing manual effort and accelerating creator qualification.
