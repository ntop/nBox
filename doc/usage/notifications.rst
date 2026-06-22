Notifications
=============

The nBox UI is able to notify the administrator about activities including:

- users starting and stopping applications and services
- software failures

This happens by logging events which are exported to external syslog servers.
These logs can be ingested by ntopng and notified via any notification endpoint
supported by ntopng, including Messaging Systems (e.g. Telegram, Slack, etc.)
email, webhooks, and many others.

.. image:: ../img/screenshots/telegram_notification.png

This requires the syslog format to be configured to JSON in the Notifications
preferences. The ntopng address (including the port used for listening
for syslog logs) should be also configured.

.. image:: ../img/screenshots/notifications_settings.png

Please check the ntopng documentation for further information about ingesting
events from nBox UI through syslog and configuring the Notification endpoints.

