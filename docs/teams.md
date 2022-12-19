---
title: Teams
---

!!! Danger "Defects"
	Teams slightest  defects or security issues during the project will require [Remediating](defect _remediation_cost.md) and increasing overall lifetime costs. Team members can lower remediation costs by frequently [Previewing](preview.md) their work so stake holder can give feedback

### Team Overview

Iterative website development teams Define, Design, Develop, Deploy and Maintenance teams are operational at the same time creating, testing 

<div style="text-align: center;">

``` mermaid
	graph TD
    dev --- def
    dev --- des
    dev --- dep
    dev --- mnt
    def --- des
    dep --- mnt

    dev([Development])
    def([Define])
    des([Design])
    dep([Deploy])
    mnt([Maintenance])
```

<b>Iterative Development Teams</b>

</div>

The first goal Developemnt teams is to reach a [Minimum Viable Product](minimum_viable)
 

 
### Team - Define
 
 - Defining websites helps the Iterative Development teams and stakeholders understand the project.

#### Define - Prerequisites

Defining website prerequisites is the first steps in optimizing website costs

- Defining what the project is about

- Funding

- Purpose

- Functionality

- Stakeholders

- Content

- The musts and wants features

- The security requirements

### Team - Design

The core foundations of a user's website experience are:

- Fast - Website responds quickly to user interactions with smooth scrolling.

- Integrated - The website uses the full capabilities of the user device to create an experience true to the device.

- Reliable - Loads quickly and reliably even in uncertain network conditions.

- Engaging - Keeps user coming back to a website

- The slightest errors or security issues during design will require [[Defect Remediation Costs |remediating]]sometime during the life time of the website.

#### Design - Prerequisites

- Decisions about Website Design

- Consistency

- Theme

- Color Scheme

- Typology

- Navigation

- User interaction
	
#### Design - Website

- Responsive Website Design

	The majority of users access websites using mobile devices. Users have little tolerance for slow loading website pages or pages that do not conform to their screen size

- Ensures pages load quickly

- Website pages are display correctly on a variety of devices and window or screen size

- The website look and feel, users experience, and functionality are consistently maintain

- Consistency website consistency is the look and feel of the site. The users experience, and functionality does not vary between website pages.
	
- The website theme is:

	- Color scheme
	
	- Header
	
	- Pages
	
	- Fonts
	
	- Footer
	
	- Typology
	
	- Navigation
	
	- User interaction

### Team - Develop

- Translates the Define and Design teams processes into website pages 

- Uses development languages to create website material such as text, graphics, and abstract logical structures. These languages are nonhuman, and strict 

- Configures and uses website development tools

- The slightest errors or security issues during development will require [[Defect Remediation Costs​|remediating]] sometime during the life time of the website.

#### Develop - Prerequisites
- Decisions about resources required to transform the Define and Design work into a website and infrastructure

- Decisions about static site generator and programming tools
		
### Team - Deploy

- Deploying a website is making it available on the Internet. The production version is deployed when stakeholders agree.

- Developers working on features, fixes, or testing may deploy a private Preview website with their changes, without disturbing other developers work or the production version. This enables the stakeholders to monitor progress. See Preview Deployments

- The slightest errors or security issues during Deploy will require [[Defect Remediation Costs​|remediating]] sometime during the life time of the website

#### Deploy - Prerequisites

- Decisions about resources required for deploying production version of the website to the Internet

- Decisions about resources required for team developers working on features, fixes, or testing to deploy private Preview Internet websites with their changes, for stake holders to view and give feedback, without disturbing other developers work or the production version

### Team - Maintenance

- Maintain is remediating Define, Design,Develop, Deploy, or Security defects

- All teams may have members on the Maintain team to solve defects.

- Hot fixes are immediate fixes required for the production deployment.

- Problems requiring remediation are triaged. They are ranked from immediate Hot Fixes to those that are not show stoppers.
- The guardian and stakeholders may choose to Rollback the production deployment to a previous production deployment if triage determines the remediation time is unacceptable.

- All fixes use the established fork, solution development, pull request processes, and version incrementing, including Hot Fixes.
  
#### Maintenance - Prerequisites

- Decisions about remediating deployed websites

- Organizing members from other teams to be part of the Maintain team while remediating specific defects.
  
