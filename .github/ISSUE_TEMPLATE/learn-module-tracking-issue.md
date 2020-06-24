---
name: Learn Module Tracking Issue
about: For tracking the development of Learn modules
title: Topic - Est Publish Date
labels: content-development, learn
assignees: ''

---

# Event Information
| Category | Details |
|-----------|---------|
| Reactor Topic | <AI Services - Coding, Languages, and Frameworks - DevOps and Dev Tools - IoT - Mixed Reality - Cloud Development - Data Science and Machine Learning - Emerging Technologies - Personal and Business Development> |
| Monthly Topic (if applicable) | <Topic taken from [Azure Dev Marketing](https://aka.ms/DevEdCalFY21H1)> |
| (Estimated) Publish Date | <Month ##, ###> | 
| Author | <Name or GitHub alias> |
| Related Reactor Events/Content | <Please provide links to all related content> |
| GitHub Repo with Initial Content | <Please link new content repo with the `aed-learn` prefix> |

## Content Outline
Please add a row for each item below and add additional rows for additional content.

**Learning Path**: Learning Paths are expected to be between 2 and 5 hours in length. They are expected to have 4-8 Modules.  
**Modules**: Modules are expected to be 20-45 mintues in length. They are expected to have 4-8 Units. They are expected to be stand-alone (a customer doesn't have to complete the entire Learning Path to learn from a Module).   
**Units**: Units are expected to be 5 - 15 minutse in length.  

| Category | Title | Duration | Pre-Reqs |  
|----------|-------|----------|----------|
| <Learning Path> | <title> | <120-300 minutes> | |
| <Module> | <title> | <20-45 minutes> | |
| <Unit> | <title> | <5-15 minutes> | |


# Content Creation Checklist

## 12 Weeks Prior
- [ ] Reactor Content Team (RCT) or Author opens a new issue for an new Learn content; filling in the Content Outline table. Both RCT and Author are marked as assignees.
- [ ] RCT and Author discuss details of the content in the comments of this issue. RCT adds the _content-development_ and _learn_ labels and adds the issue to the __Content Development__ project in the __Proposed Content__ column
- [ ] RCT and Author create a new repo where the initial content will live. This repo should be in the `/microsoft` GitHub org and should be prefixed with `aed-learn-`.
- [ ] RCT does a review of content outline and fills out the [Microsoft Learn Intake Form](https://forms.office.com/Pages/ResponsePage.aspx?id=v4j5cvGGr0GRqy180BHbR4AJ1yx2bOZFi4gC6gsf1WFUREpOSDJWWU4wSFQ4S0dZNzdZMTdUVjc2MyQlQCN0PWcu)
- [ ] RCT moves the issue to the __Waiting Learn Approval__ column and adds the _in-review_ label

## 10 Weeks Prior
- [ ] Once content is approved, RCT removes the _in-review_ label and adds the _confirmed-content_ label. RCT moves the issue to the __Development In Progress__ column
- [ ] RCT and Author work on the `aed-learn` repo where the content lives through PRs

## 8 Weeks Prior
- [ ] When the content is ready for a final review, RCT adds the _in-review_ label and moves the issue to the __Internal Review__ column
- [ ] RCT does a final review and makes sure all changes are merged into the `aed-learn` repo
- [ ] RCT meets with the person (maybe vendor) who will be migrating the content onto Learn to walk them through the project and answer any questions
- [ ] RCT meets with the Learn representative to ensure that everything is still on track
- [ ] RCT removes the _in-review_ label, adds the _ready-to-publish_ label, and moves the issue to the _Publishing In Progress__ column

## 7-1 Weeks Prior  *(Done in /microsoft-docs/learnpr)*
- [ ] RCT and author engage with the person who is migrating the content onto Learn to ensure all questions are answered

## 1 Week Prior
- [ ] RCT adds the _in-review_ label and RCT and Author do a final review of the content in preview form
- [ ] RCT approves the content for publishing

## When Published
- [ ] RCT runs through the content live to ensure there are no issues
- [ ] RCT removes the _in-review_ label, and moves the issue into the __Published__ column
- [ ] RCT adds the information of the published content on the `/microsoft/ReactorPlanning` README
