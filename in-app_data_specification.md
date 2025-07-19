# RADIUS In-App Data 
---
## RADIUS Site Details Feature
- User can expand or collapse the Site Details Panel by clicking on the "Site Details" button in the [Subject Site](https://github.com/thickey-cretelligent/radius_spec/blob/c1b3af976efcb49c87963799a8f45b02c79ad068/radius_subject_site_navigation.md).
- Site Details are displayed in an expansion panel that extends to the right of the Subject Site.
- The Site Detail Panel is composed of Parcel selection tabs and multiple categorical accordion drawers.
  - Parcel Selection
    - Navigating Parcels within the Site Details panel utilizes an array of map pins as displayed on the map to identify the Subject Site(s). This is notable in the multi-parcel experience only. 
    - Data Drawers (In this order)
      - Site Overview
      - Parcel
      - Structure
      - Land Use
      - Owner
      - Tax
      - FEMA
      - Demographics
- UX Note: Opening a Drawer closes all other open drawers.  The experience should match the Product Menu.

## RADIUS Premium Data Feature
- The top Site Detail drawer labeled **Site Overview**, is open by default and visible to all clients including Discovery/Free users.
  - The internal styling of the data in this section should allow for partial or complete display of the subsequent sections above the fold, even while using a smaller form factor laptop.  
- Subsequent Site Detail drawers are closed by default and can only be opened by Paid Subscribers, Essentials and up.
  - Alertnatively, the drawer can be open, but the data is obfuscated and a message is overlayed presenting an upgrade path.
- UX Note: Clients are offered a path to upgrade
  - Contact Customer Support (At Launch)
  - In-App upgrade with Credit Card
  
## RADIUS Premium Data Report
- The RADIUS Data can be assembled into a report and vended to the user based on a fixed cost.
- This Report is free for paid subscribers.

## Site Search Flow
- The Site Search flow should leverage the Site Details panel in place of the existing **Site Attributes** display.  This may require some subtle changes to the various use cases.  
