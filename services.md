---
# Page settings
layout: default
keywords:
comments: false

# Hero section
title: Services
description: "FHIRLab - What is in the sandbox"

# Author box
author:
    title: "by Google Gemini"
    title_url: 'https://en.wikipedia.org/wiki/Gemini_(language_model)'
    external_url: true
    description: "content created by LLM"

# Micro navigation
micro_nav: true

# Page navigation
page_nav:
    prev:
        content: Community
        url: '../community'
    next:
        content: Vision
        url: '../vision'

# gemini prompt: provide an introduction to FHIR terminology for staff in software engineering and information technology. Focus on savings of integration and ease of deployment. Offer links to standards and example instances of servers.


# Grid navigation
grid_navigation:
    - title: HAPI
      excerpt: Our Clinical Data Repository (CDR).
      cta: Work with medical data ...
      url: '#'
    - title: Ontoserver
      excerpt: Our Terminology Server (TX).
      cta: Work with medical terminology ...
      url: '#'

---

The FHIRLab FHIR Sandbox for the Philippines envisions a robust, accessible, and collaborative platform that accelerates the adoption and implementation of FHIR standards in the country's healthcare ecosystem. By providing a safe and controlled environment for experimentation, development, and testing, the sandbox empowers healthcare providers, IT professionals, and researchers to innovate and improve patient care.

# Core Components

FHIRLa

## **Clinical Data Repository**

   FHIRLab's CDR is the [HAPI Server](HAPI).
   
   * A centralized repository of standardized health data. 
   * Stores patient records, lab results, medications, and other relevant clinical information.
   * Enables data-driven insights and supports clinical decision-making.

## **Terminology Server**

   FHIRLab's Terminology Server is the [Ontoserver](Ontoserver).

   * Provides a central source of standardized healthcare terminology.
   * Includes code systems, value sets, and concept maps.
   * Ensures consistent data representation and interoperability.   

## **Validator**

   FHIRLab's Validator is the [HL7 Validator](Validator).

   * Verifies the accuracy and completeness of FHIR resources.
   * Checks compliance with FHIR standards and local implementation guidelines.
   * Helps developers identify and correct errors in their FHIR implementations.   

## **Testing Tool**

   FHIRLab's Testing Tool is [Inferno](Inferno).

   * Offers a range of tools for testing FHIR-based applications.
   * Includes test data generators, performance testing tools, and security testing tools.
   * Facilitates the development of robust and secure FHIR solutions.


