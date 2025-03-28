# Example: Fetch Red Hat Insights Hosts with Pagination using Ansible

This is an **example** Ansible playbook that demonstrates how to fetch hosts from the **Red Hat Insights API** using **token authentication and pagination**.  

**Disclaimer:** This playbook is provided as an example for educational purposes. It may require modifications to fit specific use cases or security policies. Use it at your own discretion.

## Features
- Authenticates with Red Hat API using **OAuth 2.0 Client Credentials**.
- Fetches **hosts** from Insights API using **pagination**.
- Displays the **total number of hosts** retrieved.

## Pre-requisites
This playbook requires the following variables:

- **`hcc_client_id`**: Your Red Hat API Client ID.
- **`hcc_client_secret`**: Your Red Hat API Client Secret.

# Documentation & References
- [Red Hat Insights API Documentation](https://console.redhat.com/docs/api)
- [Red Hat Insights API Cheatsheet](https://developers.redhat.com/cheat-sheets/red-hat-insights-api-cheat-sheet)
- [Red Hat Insights Documentation](https://docs.redhat.com/en/documentation/red_hat_insights/1-latest)
