---
title: "📝 Resume"
slug: "resume"
description: ""
lead: "Lead Introducing Doks, a Hugo theme helping you build modern documentation websites that are secure, fast, and SEO-ready — by default."
date: 2020-11-04T09:19:42+01:00
lastmod: 2020-11-04T09:19:42+01:00
draft: false
weight: 50
images: ["https://images.unsplash.com/photo-1618105965240-9aa565e73a0a?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=MnwxMTc3M3wwfDF8YWxsfDd8fHx8fHwyfHwxNjE4MTYyNjIy&ixlib=rb-1.2.1&q=80&w=2000"]
contributors: ["Pratik Gajjar"]
---



## EXPERIENCE

**Engineering Team**

Employer: **[FamPay.in](https://fampay.in)** | Apr, 20 - Current | Bengaluru

* Designed & Created Saving Challenge & Dynamic Reward Allocation feature. (DRF, Django, Postgres)
* Implemented facility to switch on/off and set/modify transaction limits for all types of transactions as per **[RBI Guidelines](https://www.rbi.org.in/Scripts/NotificationUser.aspx?Id=11788&Mode=0)**.
* Created CD pipeline for frontend infra. (Pulumi, GitLab CI, Docker, AWS Fargate, ECS, ECR, LB, TG, ASG)
    * Infra was able to serve peak **31K RPS**.
* Improved customer support flows & channels via B2B partnerships. Understood technicality and created cross Integration between B2B partners.
    * FreshDesk - Ticketing Software.
    * FreshChat - In-app chat with the support team.
    * FreshBot.AI - ChatBot with the custom business flow.
    * Exotel - Cloud Telephony.
    * WhatsApp - Communication Medium via Kaleyra.
    * WebEngage - Contextual and personalized campaigns for user engagement.
    * SquadVoice - Improve conversion funnel.
    * Metabase - BI tool for the support team.
* Initiated engineering team talks, a bi-weekly meeting where all engineers discuss challenges, achievements, and general tech updates.
* Involved in scaling the team, reviewed 200+ assignments, and took 100+ interviews for various positions.
    * Designed questions and JD for DevOps Role.
    * Streamlined process with hiring board. (ClickUp)
* Published blog on **[The Story Behind FamPay's Tech Stack](https://fampay.in/blog/the-story-behind-fampays-tech-stack/)**
* Created communication microservice. (GoLang, GoKit, Truss, gRPC + Protobuf, Docker)
    * Enable/Disable communication over WhatsApp message.
    * Call Alerts for high-priority internal systems.
    * Mentored Rate limiting feature.
* Performance optimizations (pgadmin, newrelic, hey).
    * Home Page - **80%** DB calls reduced via updating application logic.
    * My Activity - **92%** Avg response time reduced, from 2160ms to 172ms.
    * My Contacts - Query cost reduced, from 1542ms to 64ms.
    * Use gevent/eventlet worker pool for better throughput of Django server and Celery workers.
    * Load Testing APIs. (hey)
* Integrated Postgres and Redis read replica with the backend server. (ElastiCache, RDS, Route53, Django)
* Worked on infra cost optimization making backend services compute cost reduced by **50%** and storage cost by **40%**.
* Added Custom RAM Agent for better visibility of production workloads. (Elastic Beanstalk, Linux CRON, CloudWatch)
* Created custom celery queue length monitoring. (CloudWatch, Celery)
* Secured self-hosted Open Source platforms via OAuth proxy.
* Created infra alerts with slack notification on core services and dashboard with all key metrics for better visualizations. (AWS CloudWatch, ChatOps, NewRelic Alerts).
* Mentored implementation of an internal queue to schedule celery tasks making the system fault-tolerant.
* Introduced code cleaning tools in the CI pipeline. (Black, Isort, Flack8, GitLab CI)
* Created Data Pipeline PoC. (Debezium, Postgres, Kafka, RedShift, S3).
* Research & Implementation of anomaly detection on business data.
* Implemented Home Section backend.
* Implemented User Cohorts feature to make each user's experience unique.
    * With batch upload functionality.
* Made Operations team automating mundane tasks via introducing [n8n](https://n8n.io/) self-hosted automation tool.
* Setup AirFlow for ETL Scripts. (Pulumi, ECS, Fargate)
* Created user categorization helping find PMF and relevant target audience.
* Implemented internal auth feature. (JWT, JWK)
* Implemented user and fam state timeline. (Django Signal)
* Implemented bulk communication feature (DRF, Django).


**Senior Software Engineer**

Employer: **[Truebil.com](https://truebil.com)** | Nov, 19 - Apr, 20 | Mumbai

* Optimized and developed new APIs of Truebil’s Progressive Web App which is now part of **Google Case Study**. Achieved Avg response time of **51ms** from **180ms**.  Resulting **80%** increase in revenue-to-marketing spend. (Django-REST-Framework, Mysql 5.7, Redis)Ref: [How Truebil made the web its channel of growth](https://web.dev/truebil-lite/)
* Architect **redis** caching layer of backend api, which resulted in **+435%** throughput capacity and **66%** reduction of EC2 instance consumption. (hey - benchmarking tool)
* Created a **data stream** pipeline using **Kafka** and deployed it on **AWS** infrastructure. Setup monitoring of kafka and Redis using open source tools. (RedisInsight, Burrow, Kafka Topic UI, Confluent Kafka-REST, Prometheus)
* Leading data engineering team to push data science solutions in production.

**Software Engineer**

Employer: **[Truebil.com](Truebil.com)** | May, 18 - Oct, 19 | Mumbai

* Implemented backend of truebil auction app. Integrated it with Firebase realtime database for live bidding. (DRF, Mysql)
* Implemented async data stream solution to sync data with 3rd party crm service. (Django Signals, Gearman, CakePHP)
* UTM data integration with existing database to track users from ad marketing campaigns. (Django, Adscript, PHP)
* Integrated error analytics platform with all existing backend apps. (Sentry, NewRelic)
* Implemented asynchronous push notification system for internal apps. (Celery, Supervisord)
* Implemented hybrid pagination for result page api.
* Infra setup and monitoring of data science codebase. Integrated data-science solutions for better seller and buyer experience.
* Integrated different types of recommendation system with result page api to show most relevant cars.
* Mentored intern to implement price engine and seller visit module.
* Created django-rest-boilerplate following 12factor methodology with google authentication (JWT).  Wrote architect of stock management backend and guided intern to develop business requirements.
* Created Python-Gearman module with features of automatic log segregation of worker log files and register worker from single end-point.

**Software**  **Development**  **Intern**

Employer: **[Truebil.com](Truebil.com)** | Jan, 18 - Apr, 18 | Mumbai

* Charted user journey on the product by connecting all the (communication) touch points for a user. Technologies used: Python, PHP
* Optimized the development speed and pipeline by integrating Docker Container platform. Packaged several in-house technology stacks and products in containers, which ensured applications always work in any specified environment.
* Implemented auto-selecting city feature using GeoIP2 in backend api (Django) and frontend (PWA - React + Redux).

**Software Developemnt Intern**

Employer: **[Netsavvies.com](https://netsavvies.com)** | May, 17 - Jul, 17 | Ahmedabad

* Designed database schema for a new product.
* Implemented Role-Based Access Management System and Data-entry portal using Laravel 5 PHP Framework.

## EDUCATION

**DHIRUBHAI AMBANI INSTITUTE OF INFORMATION AND COMMUNICATION TECHNOLOGY​**  (DA-IICT) Gujarat, India

2014-2018 B.Tech in Information and Communication Technology

## COURSEWORK

Data structures, Algorithms, Operating Systems, DBMS, Computer Networks, Systems Software, Software Testing.

## SKILLS

**PROGRAMMING** 

Python, Django, GoLang, SQL, TypeScript, CakePHP, Laravel, PHP, C++, JAVA.

**TOOLS AND TECHNOLOGIES** 

Git, Docker, Redis, Postgres, MySQL, Nginx, Kafka, Pulumi.

**Language**

English, Hindi, Gujarati.
