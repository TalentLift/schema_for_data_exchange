---
layout: default
title: Documentation
permalink: /documentation/
---

<div class="max-w-4xl mx-auto pb-12 px-6">

  <!-- Header Section -->
  <h1 class="text-2xl font-bold text-gray-800">Data Exchange Framework Documentation</h1>
  <p class="mt-4 text-gray-600">
    Welcome to the Data Exchange Framework Documentation. Here, you’ll find detailed information on our standardized data schema, guidelines for integrating the schema into your systems, and best practices for using it effectively. This documentation is intended to support organizations in adopting and implementing the schema as part of their data management strategies for displaced communities.
  </p>
  
  <!-- Table of Contents -->
  <div class="mt-8">
    <h2 class="text-xl font-semibold text-gray-800">Table of Contents</h2>
    <ul class="list-disc list-inside text-gray-600">
      <li><a href="#schema-overview" class="text-blue-600 hover:text-blue-800">Schema Overview</a></li>
      <li><a href="#implementation-guide" class="text-blue-600 hover:text-blue-800">Implementation Guide</a></li>
      <li><a href="#database-setup" class="text-blue-600 hover:text-blue-800">Setting Up a Database</a></li>
      <li><a href="#api-integration" class="text-blue-600 hover:text-blue-800">API Integration</a></li>
      <li><a href="#privacy-security" class="text-blue-600 hover:text-blue-800">Privacy and Security</a></li>
      <li><a href="#community-contributions" class="text-blue-600 hover:text-blue-800">Community Contributions</a></li>
      <li><a href="#governance" class="text-blue-600 hover:text-blue-800">Governance and Change Management</a></li>
      <li><a href="#faq" class="text-blue-600 hover:text-blue-800">FAQ</a></li>
    </ul>
  </div>

  <!-- Schema Overview Section -->
  <div id="schema-overview" class="mt-12">
    <h2 class="text-xl font-semibold text-gray-800">Schema Overview</h2>
    <p class="mt-4 text-gray-600">
      The Data Exchange Framework Schema is a standardized model designed to harmonize data collection and sharing across different organizations. It provides clear definitions for fields, data types, and relationships, enabling consistent data management for displaced individuals and skilled immigration pathways.
    </p>
    <p class="mt-4 text-gray-600">
      Explore the full schema structure, including objects like <strong>Education</strong>, <strong>Work Experience</strong>, and <strong>Language Proficiency</strong>, along with the relationships between these entities.
    </p>
    <p class="mt-4">
      <a href="{{ '/schema/' | relative_url }}" class="text-blue-600 hover:text-blue-800">View the Full Schema</a>
    </p>
  </div>

  <!-- Implementation Guide Section -->
  <div id="implementation-guide" class="mt-12">
    <h2 class="text-xl font-semibold text-gray-800">Implementation Guide</h2>
    <p class="mt-4 text-gray-600">
      Whether you’re starting with a new database or adapting the schema to an existing system, this implementation guide will help you get started. Below are the different options available:
    </p>
    <ol class="mt-4 list-decimal list-inside text-gray-600">
      <li><strong>Creating a New Database:</strong> Use our schema as the foundation for your new database. Recommended for organizations building from scratch.</li>
      <li><strong>Adopting the Schema in an Existing Database:</strong> Map your existing fields to our standardized schema to ensure compatibility.</li>
      <li><strong>Using the Schema in APIs:</strong> Implement the schema as a shared interface to facilitate data exchange with other organizations.</li>
    </ol>
    <p class="mt-4 text-gray-600">
      For step-by-step instructions, refer to our <a href="#database-setup" class="text-blue-600 hover:text-blue-800">Database Setup Guide</a> and <a href="#api-integration" class="text-blue-600 hover:text-blue-800">API Integration Guide</a>.
    </p>
  </div>

  <!-- Database Setup Section -->
  <div id="database-setup" class="mt-12">
    <h2 class="text-xl font-semibold text-gray-800">Setting Up a Database</h2>
    <p class="mt-4 text-gray-600">
      Follow these steps to set up your database using the Data Exchange Framework Schema:
    </p>
    <ul class="mt-4 list-disc list-inside text-gray-600">
      <li>Study the schema file: <a href="{{ '/schema/' | relative_url }}" class="text-blue-600 hover:text-blue-800">Schema File</a></li>
      <li>Convert it to YAML file for NoSQL setups</li>
      <li>Set up validation rules to ensure data integrity.</li>
    </ul>
  </div>

  <!-- API Integration Section -->
  <div id="api-integration" class="mt-12">
    <h2 class="text-xl font-semibold text-gray-800">API Integration</h2>
    <p class="mt-4 text-gray-600">
      Implementing the schema as part of an API allows for real-time data exchange and synchronization between systems. Use the schema as a standardized interface for receiving and sending candidate data.
    </p>
  </div>

  <!-- Privacy and Security Section -->
  <div id="privacy-security" class="mt-12">
    <h2 class="text-xl font-semibold text-gray-800">Privacy and Security</h2>
    <p class="mt-4 text-gray-600">
      Protecting the privacy and security of candidate data is of utmost importance. Follow industry best practices, including data encryption, role-based access controls, and anonymized data sharing when appropriate.
    </p>
  </div>

  <!-- Community Contributions Section -->
  <div id="community-contributions" class="mt-12">
    <h2 class="text-xl font-semibold text-gray-800">Community Contributions</h2>
    <p class="mt-4 text-gray-600">
      This schema is a collaborative product, and we welcome contributions from the community. If you have suggestions for improvement or wish to participate in the working group’s efforts, feel free to reach out to us.
    </p>
  </div>

  <!-- Governance Section -->
  <div id="governance" class="mt-12">
    <h2 class="text-xl font-semibold text-gray-800">Governance and Change Management</h2>
    <p class="mt-4 text-gray-600">
      The governance of the Data Exchange Framework is managed through a structured change management process that ensures all stakeholders have a say in major updates. This process is led by the chair and co-chair of the working group and involves member discussions, decision-making, and voting on changes.
    </p>
    <p class="mt-4">
      For detailed information on the governance structure and change request process, visit the <a href="{{ '/governance/' | relative_url }}" class="text-blue-600 hover:text-blue-800">Governance and Change Management Page</a>.
    </p>
  </div>

  <!-- FAQ Section -->
  <div id="faq" class="mt-12">
    <h2 class="text-xl font-semibold text-gray-800">Frequently Asked Questions (FAQ)</h2>
    <p class="mt-4 text-gray-600">
      Find answers to common questions and troubleshooting tips in our FAQ section.
    </p>
  </div>

</div>
