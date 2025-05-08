# BigQuery-and-Google-Analytics-4
Conversion calculation by date and traffic channel (Level Medium):
I created a query to retrieve a table with information about conversions from the beginning of the session to the purchase. The resulting table contains the following fields:
event_date — the start date of the session, obtained from the event_timestamp field.
source — the source of the site visit.
medium — the medium of the site visit.
campaign — the name of the site visit campaign.
user_sessions_count — the number of unique sessions by unique users on the corresponding date and for the corresponding traffic channel.
visit_to_cart — conversion from the start of a session on the site to adding a product to the cart (on the corresponding date and for the corresponding traffic channel).
visit_to_checkout — conversion from the start of a session on the site to an attempt to place an order (on the corresponding date and for the corresponding traffic channel).
Visit_to_purchase — conversion from the beginning of a session on the site to a purchase (on the corresponding date and for the corresponding traffic channel).

Comparison of conversion between different landing pages (Level Medium +):
To perform this task, I obtained the page path (the path to the page without the domain address and without link parameters) from the page_location in the session start event.
For each unique page path of the session start, I calculated the following metrics based on data from 2020:
Number of unique sessions per unique users
Number of purchases
Conversion from session start to purchase

Checking the correlation between user engagement and purchases (Level Hard):
For each unique session, determined:
Whether the user was engaged during this session.
The total time the user was active during the session from each session event.
Whether a purchase occurred during the session.
Calculated the correlation coefficient value
