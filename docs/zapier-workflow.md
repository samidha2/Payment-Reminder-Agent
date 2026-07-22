# Payment Reminder Automation

## Trigger

Schedule by Zapier

Runs every day at 9:00 AM.

---

## Step 1

Lookup Spreadsheet Rows

Filter:

Status = Pending

---

## Step 2

Loop through each row.

---

## Step 3

If Type = Maintenance

Send email to

sadicsha.khandait@associates.scit.edu

---

## Step 4

If Type = Project

Send email to

mehak.chhabra@associates.scit.edu

---

## Step 5

Wait for payment confirmation.

---

## Step 6

Search Gmail replies.

Extract

- Invoice ID

- Transaction ID

---

## Step 7

Update Google Sheet

Status → Completed

Transaction_ID → Retrieved ID