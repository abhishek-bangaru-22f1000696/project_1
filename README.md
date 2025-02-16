## A1 Task: Install uv and Run datagen.py
What this task does:
- Installs uv (if not installed).
- Runs a script from a URL (datagen.py) with your email as an argument.
- Generates data files required for later tasks.

-----
## Task A2: Format Markdown Using Prettier
What this task does:
- Takes a Markdown file (/data/format.md).
- Formats it in-place using prettier@3.4.2.
- Uses npx (Node.js package runner) to execute Prettier.
---
## Task A3: Count the Number of Wednesdays in /data/dates.txt

What this task does:
- Reads the file /data/dates.txt, which contains a list of dates (one per line).
- Counts how many dates are Wednesdays.
- Writes the result to /data/dates-wednesdays.txt (only the number).

---
## Task A4: Sort Contacts in /data/contacts.json
What this task does:

- Reads the file /data/contacts.json, which contains a list of contacts.
- Sorts the contacts by last_name, then first_name.
- Writes the sorted list to /data/contacts-sorted.json.
---
## Task A5: Extract First Lines from the 10 Most Recent .log Files
What this task does:

- Finds all .log files inside /data/logs/.
- Sorts them by modification time (newest first).
- Extracts the first line from the 10 most recent log files.
- Writes the result to /data/logs-recent.txt (one line per log file).
---
## Task A6: Extract Titles from Markdown (.md) Files
What this task does:

- Scans all Markdown (.md) files in /data/docs/.
- Extracts the first H1 title (i.e., a line starting with # ).
- Creates an index file (/data/docs/index.json) that maps filenames to their titles.
---
## Task A7: Extract the Sender’s Email from /data/email.txt Using LLM
What this task does:

- Reads the email content from /data/email.txt.
- Uses GPT-4o-Mini (via AI Proxy API) to extract the sender’s email.
- Writes the extracted email to /data/email-sender.txt.
---
##  Task A8: Extract a Credit Card Number from an Image Using LLM
What this task does:

- Reads the image file /data/credit-card.png.
- Uses GPT-4o-Mini (via AI Proxy API) to extract the credit card number.
- Writes the extracted number (without spaces) to /data/credit-card.txt.
---
##  Task A9: Find the Most Similar Pair of Comments Using Embeddings
What this task does:

- Reads /data/comments.txt, which contains a list of comments (one per line).
- Uses text embeddings (via AI Proxy API, text-embedding-3-small) to find the most similar pair.
- Writes the two most similar comments to /data/comments-similar.txt (one per line).
---
## Task A10: Calculate Total Sales for "Gold" Tickets in an SQLite Database
What this task does:

- Reads the SQLite database file /data/ticket-sales.db.
- Queries the tickets table to sum the total units * price for "Gold" tickets.
- Writes the result to /data/ticket-sales-gold.txt.
