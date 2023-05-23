# Changelog

## 20230519

- __Added__ health facility adding, editing, and deleting features for
admin users.
- __Added:__ Certificates for TB-DOTS can now be generated after compliance
by rural health units and hospitals.
- __Added__ functionality for admin users that allows them to add, edit,
and delete health facilities.
- __Changed:__ Reply letters are now rendered with the names of respective
chief executives like governors and mayors.
- __Fixed__ display of health facility's province and city/municipality in
the MBFHFI tool for requestors.

## 20230512

- __Added__ certificate templates for ABTC and TB-DOTS.
- __Added__ a skip button that can be clicked after accomplishing an
assessment tool in order to skip waiting time before redirection to the
home page.
- __Changed:__ Provinces, cities, and municipalities are now considered
their own entities within the app, instead of simply being attributes of
health facilities. This allows them to be used for other purposes aside
from health facilities, such as address fields for reply letters.
- __Changed__ the mask/placeholder for the contact number field for
requestors into a string of letter x's for privacy reasons.
- __Fixed__ an issue wherein landline numbers for health facilities were
incorrectly stored in the database after being uploaded via CSV files
exported from the National Health Facility Register.
- __Fixed__ links when viewing certification requests to point to the
correct assessment tool that was accomplished for the request, instead of
the TB-DOTS tool only.

## 20230505

- __Added__ functionality for the Secretariat to approve or reject requests
from health facilities before review by their respective Certifiers.
- __Added:__ Reply letters, which are stored as PDF files, are now being
attached to particular emails.
