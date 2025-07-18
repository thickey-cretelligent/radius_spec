# RADIUS Order Flow: Project-Based Ordering

Note: To align with the concept of a "Project" in TRACKER, the Cart should be rebranded to "Project".  

## 1. Subject Site Confirmation
- Users are encouraged to **confirm** a Subject Site early in the process.
- Once confirmed, the Subject Site displays a prominent indicator.  
- However, users can begin building a Project by adding products and configuring options without confirmation.
- Before initiating a quote or placing an order, the system will prompt the user to confirm the Subject Site if not already done.

## 2. Product Management
- Users can add or remove products from the Project at any time.
- Products are displayed in a ledger-style view within the Project.
- Required input fields are collected during the Project checkout flow. 

## 3. Product Categorization
- Products are grouped into two sections:
  - **Request Proposal**: Unpriced products needing a Proposal.
  - **Ready To Order**: Products with determined pricing.

## 4. Order Initiation
- Users initiate the order process from the Project view.
- A progressive input form collects required Project and Product data:
  - The form adapts based on user selections.
  - Only relevant fields are shown at each step.
  - Users can save progress and return later.

## 5. Quoting Workflow
- **Ready To Order** Products can be Ordered immediately by clicking **“Place Order.”**
- For **Request Proposal** Products, the flow adapts:
  - Users click button labeled **“Request Proposal.”**
  - Products with **ClickQuote** enabled run automatically.
  - Non-ClickQuote enabled products or ClickQuote consults are routed to **Quote Manager** for manual consult.
  - During the manual consult, the Product Proposal Status will be **In Review**
- Once Proposals are returned:
  - The Product Proposal Status will be "Proposal Ready" 
  - The Product is now listed in the **“Ready to Order”** section with Proposal amount and Turnaround time displayed prominently.
  - Users can place an order for items in this section without waiting for other Proposals still "In Review".

## 6. Project Saving & Activity Tracking
- Users can click **Save** or **Save and Close** at any time to preserve the current Project state.
- When updates occur (e.g., Proposal status changes to “Quote Ready”):
  - The **Subject Site** moves to the top of the RADIUS Subject Site list with an activity indicator.
  - Within the Subject Site, the relevant Project also displays an activity badge.

## 7. Project Navigation
- Users can return to any Project via the **Project Navigator**.
- From there, they can review quotes, make changes, or proceed with ordering.
