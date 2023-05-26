Introduction:
Schedule future notifications and reminders in Laravel.To prevent users receiving all of the old scheduled notifications at once, the command will only send mail within the configured tolerance. By default this is set to 24 hours, so only mail scheduled to be sent within that window will be sent.

Cases:
Reminder system (1 week before appt, 1 day before, 1 hour before, etc)
Follow-up surveys (2 days after purchase)
On-boarding Email Drips (Welcome email after sign-up, additional tips after 3 days, upsell offer after 7 days)
Short-Term Recurring reports (send every week for the next 4 weeks)
