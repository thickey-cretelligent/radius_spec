# RADIUS Order Flow: Project-Based Ordering

## 1. Subject Site Confirmation
- Users are encouraged to confirm a Subject Site early in the process.
- However, users can begin building a Project (adding products, configuring options) without confirmation.
- Before initiating a quote or placing an order, the system will prompt the user to confirm the Subject Site if not already done.

## 2. Product Management
- Users can add or remove products from the Project at any time.
- Products are displayed in a ledger-style view within the Project.

## 3. Product Categorization
- Products are grouped into two sections:
  - **Quote Required**: Unpriced products needing a quote.
  - **Priced Products**: Products with visible pricing.

## 4. Order Initiation
- Users initiate the order process from the Project view.
- A progressive input form collects required Project and Product data:
  - The form adapts based on user selections.
  - Only relevant fields are shown at each step.
  - Users can save progress and return later.

## 5. Quoting Workflow
- If the Project contains only priced products, users can proceed directly by clicking **“Place Order.”**
- If the Project contains quoted products, the flow adapts:
  - Users click **“Request Quote.”**
  - Products with **ClickQuote** enabled run automatically.
  - Non-ClickQuote enabled products or ClickQuote consults are routed to **Quote Manager (QM)** for manual consult.
- Once quotes are returned:
  - A **“Ready to Order”** section appears, listing all priced and successfully quoted products.
  - Users can place an order for these items without waiting on remaining quotes.

## 6. Quote Review & Order Placement
- After quoting:
  - Users see **Quote details** and **Estimated Delivery** for each successful proposal.
  - Users can click **“Place Order”** to proceed with all priced and quoted products.

## 7. Project Saving & Activity Tracking
- Users can click **“Save and Close”** at any time to preserve the current Project state.
- When updates occur (e.g., Proposal status changes to “Quote Ready”):
  - The **Subject Site** moves to the top of the RADIUS Subject Site list with an activity indicator.
  - Within the Subject Site, the relevant Project also displays an activity badge.

## 8. Project Navigation
- Users can return to any Project via the **Project Navigator**.
- From there, they can review quotes, make changes, or proceed with ordering.
