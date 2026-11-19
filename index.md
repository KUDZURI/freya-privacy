---
title: Freya for Chrome — Privacy Policy
---

# Freya for Chrome Privacy Policy

**Last updated:** November 19, 2026

This policy applies to the Freya extension for Google Chrome. The extension is provided by kudzuri@gmail.com and connects Chrome to the Freya desktop software so users can select web page elements and run browser automation workflows.

## Data the extension handles

- **Browser and tab information.** The extension reads URLs and titles of open tabs to identify the tab to use. It sends the browser user-agent string and extension version to the local Freya component when it connects.
- **Element selection.** While selection mode is active, the extension processes pointer movements and clicks to highlight the element under the pointer and identify the element the user selects. It can send information about that element, its containing page, and its frame to Freya.
- **Website and workflow data.** Depending on the workflow, the extension can enter values supplied by Freya, read text and tables, capture screenshots, run workflow-supplied JavaScript in the target tab, and return results. Values entered in forms and content read or captured from pages may include personal or sensitive information, depending on the websites and workflow.
- **Downloads.** When a workflow waits for a download, the extension checks its status and can return the file name and local path.

## How data is used and shared

The extension uses this data to identify the target tab or element, carry out workflow steps, and return results or errors to Freya. It passes messages to the native messaging host on the same computer. Workflow steps such as submitting a form can send data to the website selected in the workflow.

Freya workflows may save results to files or pass them to other systems configured by the user or their organization. If Freya Orchestrator is used, workflow results or logs may be stored in that deployment, depending on its configuration and what the workflow records.

We use data obtained through Chrome APIs to provide or improve Freya's browser automation features. We do not sell this data, use it for advertising, or use it to determine creditworthiness or for lending. Our use and transfer of information received from Google APIs adhere to the [Chrome Web Store User Data Policy](https://developer.chrome.com/docs/webstore/program-policies/policies), including its Limited Use requirements.

## Storage and deletion

The extension stores the element selection state and working tab ID in Chrome's session storage. Chrome clears that storage when the browser restarts or the extension is removed, disabled, or reloaded.

Downloaded files and workflow results saved outside Chrome have their own retention settings. To access or delete those copies, use the relevant file location or application. For organization-managed deployments, contact the administrator responsible for the workflow or the Freya deployment.

## Contact

For privacy questions or requests concerning the Freya extension, contact kudzuri@gmail.com.
