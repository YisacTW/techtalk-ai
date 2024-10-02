Bug Fixes
=========

Invoice Email Delivery Issues
-----------------------------
* Fixed an issue where invoice emails were not being sent to customers in some cases.
* Improved email delivery reliability by implementing a retry mechanism for failed sends.
* Added logging for better tracking and troubleshooting of email delivery problems.

Delivery Tracking Delays
------------------------
* Resolved delays in updating delivery status on the customer-facing tracking page.
* Optimized database queries to reduce latency in real-time tracking updates.
* Implemented caching for frequently accessed tracking data to improve performance.

POS Syncing Errors with Square
------------------------------
* Fixed synchronization issues between BizFlows and Square POS systems.
* Addressed data inconsistencies that occurred during high-volume transactions.
* Improved error handling and added detailed error messages for easier troubleshooting.

General Improvements
--------------------
* Enhanced overall system stability and performance.
* Implemented additional security measures to protect user data.
* Updated third-party dependencies to their latest stable versions.

If you encounter any issues or have questions about these bug fixes, please contact our support team at support@bizflows.com.
