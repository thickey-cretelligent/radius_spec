# RADIUS Order Process Spec

## Overview
This specification defines the RADIUS Order flow for all non-automated Products using the "Cart".  The intent is to replace all existing order pages with a single consolidated checkout process. 
Note: To align with the concept of a "Project" in TRACKER, the Cart should be rebranded to "Project".  As such, references in this document to "Projects" refer to the Cart.

## 1. Subject Site Confirmation
- After Users save a new Subject Site, they are encouraged to **Confirm** the Subject Site beginning early in the process. [Site Confirmation](radius_client_site_confirmation_spec.md)
- Once confirmed, the Subject Site displays a prominent indicator.  
- Users can begin *Building a Project* by adding products and configuring options prior to site confirmation.
- Before initiating a Request for Proposal or placing an order, the system will prompt the user to confirm the Subject Site if not already done.

## 2. Product Selection
- Users can add or remove products from the Project at any time.
- Products are displayed in a ledger-style view within the Project/Cart view.
- Required input fields are reserved for collection during the Project checkout flow.

## 3. Product Categorization
- Products are grouped into two sections:
  - **Request Proposal**: Unpriced products needing a Proposal.
  - **Ready To Order**: Products with determined pricing.

## 4. Request Proposal Workflow
- Users are guided to select relevant Product Options (Those that currently exist on the individual order pages) 
- Users are guided to provide required input data to successfully Request Proposal [Needs Definition]
- Once required inputs are provided, users can click button labeled **“Request Proposal.”**
- Products with **ClickQuote** enabled run automatically.
- Non-ClickQuote enabled products or ClickQuote consults are routed to **Quote Manager** for manual consult.
- During the manual consult, the Product Proposal Status will be **In Review**
- Once Proposals are returned the Product Proposal Status will be **Proposal Ready** and the with Proposal amount and Turnaround time displayed prominently.
- User can click "Accept Proposal" which moves the Proposal from the **Request Proposal** Section to the **Ready to Order** Section. 

## 5. Ready To Order Workflow
- Users are guided through a set of both required and optional input fields relative to the array of Products selected. 
- Users are guided to specify Project Contacts in the Contact Center or return later to do so. [Contact Center](radius_contact_center_spec.md)
- Users are guided to supply Required Documents in the Document Center or return later to do so. [Document Center](radius_document_center_spec.md)
- Users can save progress and return later.
- User can select one or more **Ready to Order** Products and click Button labeled **Place Order**.
- Note: Users can place an order for items in this section without initiating Request for Proposal or waiting for other Proposals still "In Review".
- Note: Subsequent Product orders can continue to be added to the Project before the final Project invoice is delivered.

## 6. Project Saving & Activity Tracking
- Users can click **Save** or **Save and Close** at any time to preserve the current Project state.
- When updates occur (e.g., Proposal status changes to “Quote Ready”):
  - The **Subject Site** moves to the top of the RADIUS Subject Site list with an activity indicator.
  - Within the Subject Site, the relevant Project also displays an activity badge.

## 7. Project Navigation
- Users can return to any valid Project by first selecting the **Subject Site** and then selecting the desired **Project**.
