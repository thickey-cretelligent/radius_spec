# Site Verification Specification

### 

### Site Verification requirements

* Verify that all adjacent parcels with similar Ownership have been identified.
* Verify that all Business Operations are contained within the parcel boundaries.
* Verify that all Parking Areas are contained within the parcel boundaries.
* Verify that Required Site Data is populated and accurate. (See Service Input Data Requirements Matrix)

### 

### Proposal Phase

Consult Proposals should not be generated, delivered to the client, or awarded until the Site Verification has been completed.



### Order Kick-Off

Orders are delivered to Production with a status of "Not Started". Site Verification must be completed prior to updating the status to "In Progress".  

For Orders (i.e. Click Quote), the Order cannot be moved from “Not Started” to “In Progress” until the Site has been Verified.

The Proposal should not be able to be awarded independently either.



#### Software Specification

Platform:  TRACKER

Pages: Quote Manager, Site Details

Functions: Generate Proposal, Award Proposal, Site Verification



Following Site identification, OT User must browse to Site Details to perform Site Verification Requirements and mark the Site as Verified using the Site Verification button on the Site Page.  The button should open a dialog that details the Site Verification Requirements and provides the user with "Verify" and "Cancel" buttons.  Clicking "Verify" marks the Site as Verified, clearly indicating the OT User that performed Site Verification, and enables the "Generate Proposal" and "Award Proposal" buttons in Quote Manager once the order client price and turn-around has been populated.



The Red Triangle should be visible until the Land Use is populated and the “Site Verification” check box is checked.



The Red Triangle hover message should list the Site Verification and Land use population as required elements to clear the Red Triangle.



