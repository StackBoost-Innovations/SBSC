=== StackBoost - For SupportCandy ===
Contributors: StackBoost
Tags: supportcandy, helpdesk, support, ticket system
Requires at least: 6.0
Tested up to: 6.9
Stable tag: 1.6.2
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

StackBoost enhances SupportCandy with advanced workflow, UI controls, and powerful add-on modules.

## Features

StackBoost includes several modules that can be enabled or disabled based on your needs.

### Core Enhancements
*   **Ticket View Popup:** Right-click any ticket in the list to see a quick "Details Card" popup.
    *   **Smart Layout:** Automatically switches to a side-by-side view if the content is too tall.
    *   **Interactive History:** Expand and collapse conversation history directly within the popup.
    *   **License Fallback:** gracefully degrades to standard fields if the PRO license is inactive.
*   **General Cleanup:** Automatically hide empty columns or the priority column to reduce clutter in the ticket list.
*   **Ticket Type Hiding:** Restrict which ticket types are visible to non-agent users in the submission form.
*   **After Hours Notice:** Display a customizable warning notice on the ticket form when users attempt to submit a ticket outside of configured business hours.

### Conditional Column Hiding
Create powerful, context-aware rules to control column visibility in the ticket list based on the active view (filter).

*   **SHOW ONLY:** Make a column visible *only* in a specific view and hide it everywhere else by default.
*   **HIDE:** Explicitly hide a column in a specific view.
*   **SHOW:** Create exceptions to override implicit hiding rules.

*Example:* Show the "Billing Code" column *only* when the "Accounting" view is active.


### Diagnostics & Logging
A robust system for troubleshooting.
*   **Centralized Logging:** A master switch controls logging across all modules.
*   **Module-Level Control:** Enable file logging for specific modules (e.g., UTM, Directory) while keeping others silent.
*   **Browser Console Logs:** View debug information directly in the browser console when enabled.

## 3rd-Party Libraries

This plugin utilizes the following 3rd-party open-source libraries:
*   **SelectWoo (v1.0.8):** A fork of Select2 by WooCommerce, used for enhanced select boxes. [Repository](https://github.com/woocommerce/selectWoo)
*   **DataTables (v2.3.6):** Used for advanced table sorting and filtering in premium modules. [Website](https://datatables.net/)
*   **Tippy.js (v6.0):** Used for tooltips. [Website](https://atomiks.github.io/tippyjs/)
*   **Popper.js (v2.0):** Used as a positioning engine for Tippy.js. [Website](https://popper.js.org/)
*   **jQuery UI:** Used for date pickers and drag-and-drop interfaces. [Website](https://jqueryui.com/)

## Source Code

The full source code and build tools for this plugin are publicly maintained on GitHub:
[https://github.com/stackboost/stackboost-for-supportcandy](https://github.com/stackboost/stackboost-for-supportcandy)

## Installation

1.  Upload the `stackboost-for-supportcandy` folder to the `/wp-content/plugins/` directory.
2.  Activate the plugin through the 'Plugins' menu in WordPress.
3.  Navigate to the **StackBoost** menu to configure your settings.
4.  (Optional) Enter your license key in **StackBoost > General Settings** to activate Pro or Business features.

## Requirements

*   WordPress 6.0+
*   PHP 7.4+
*   SupportCandy (Free or Pro)
