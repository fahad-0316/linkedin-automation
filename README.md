# LinkedIn Automation System - Talent Sourcing and Outreach Engine

> An open-source LinkedIn automation project which finds details of persons looking for a job and contacts them, for finding talent, discovering profiles, generating leads, discovering new profiles, and managing campaigns.

## Overview

This system simply automates the manual searching and finding of potential candidates, then also automates the process of sending them emails and booking meeting interviews with them along with sending multiple follow-ups emails, then finally exploring every data into the clients ATS or CRM software. It can be used as a foundation for recruitment automation.

# Features

## Talent Searching
It can search and collect data on LinkedIn profiles based on keywords based input data, the data includes job title, skills, location, industry, company, experience, keywords, education, professional background.

## LinkedIn Profile Discovery
When it finds the potential candidate profiles, it can extract profile's information like name, headline, current position, company, location, skills, experience, education, profile URL, and all their educational and employment information, and public profile metadata. It can scrape candidate profiles matching seniority, intent filters, role, location, open to work signals etc. 

## Lead Generation
Then it creates targeted lists for sales, business development, partnerships, and other professional outreach workflows, whichever the client wants to search. It can organize and store the profiles according to job role, company, industry, location, skills, keywords, business relevance. It performs MX record and paginates LinkedIn talent search results.

## Store Data and Data Export
It can store the data it found in a database or google sheets; it can also export that data to multiple CRMs and ATS softwares like Workable, Ashby, Greenhouse, Lever and HubSpot by using built in Webhooks and RestAPI endpoints sync.

## Email Validation 
Before contacting the selected potential profiles via their given business email, it verifies contact email deliverability by using SMTP handshakes, it checks that is the email address contactable or not, by doing it, it keeps emails bounce rates less than 2%.

## Profile Deduplication
It also checks candidate profile ids against the company's CRM database to avoid redundant outreach; it checks that is that candidate already a part of the company? Or company contacted it before? So that it can avoid duplicate contacts.

## Campaigns
It can create and run campaigns in which it can send emails to the candidates, it can also send multiple follow-up emails to the clients and can schedule interview meetings and can sync with calender and can schedule meetings and send links to the candidates, and then it can track those campaigns.

## Personalized Outreaches
It schedules multi-stage email out-reach with calendar, booking links directly into the company's ATS system. It sends the emails by using dynamic company tokkens for personalization, data according to company's info. 

## Warm-up Sessions
It handles Linkedin rate limits by setting a daily limit quota of Linkedin activity, does human like activities like scrolling, liking a post, sending and accepting random connections requests, interacting with users and generating randomized delays. It also uses multiple recruiter session cookies with the help of an anti-detect browser like Multilogin.

## Sync With ATS and CRM
It uses ATS Pipeline Webhooks to send profile info, contact info, reply to notes to CRM and ATS softwares like Workable, Ashby, Greenhouse, Lever and HubSpot, to remain in sync with them. 

# Working
Tell keywords for search -> Scrapes matching profiles, career milestones, public contact info -> Validates contact emails -> Tracks progress, send calender meeting links, syncs in CRM/ATS

# Technology Stack
Python 
FastAPI
RestAPI
MultiLogin
Webhooks

# Who is it for?
Technical recruiters who wants to maintain automated pipeline of good engineers or candidates without doing manual search.
The internal talent teams who wants to hire for executive or other related roles directly without paying anything to third party recruiter agencies.
Recruiters can use the system to organize candidate sourcing and outreach workflows.

# FAQs

## Can this project be used for recruitment?
Yes. This tool is designed to support candidate discovery, talent sourcing, campaign management, and recruitment outreach workflows.

## Can this project be used for lead generation?
Yes. The system can serve as a foundation for professional campaigns and lead-generation workflows.

## Is LinkedIn automation allowed?
The answer depends on the specific activity, implementation, applicable policies, and laws. 
Users should review LinkedIn's current terms and policies before doing automation.
