# Site Verification Specification

## Site Verification
Site Verification is performed immediately after Site Identification by an internal resource.  


### Site Verification Requirements
* Verify that all adjacent parcels with similar Ownership have been identified.
* Verify that all Business Operations are contained within the parcel boundaries.
* Verify that all Parking Areas are contained within the parcel boundaries.
* Verify that Required Site Data is populated and accurate. (See Service Input Data Requirements Matrix)

### RADIUS Site Confirmation
Client is prompted to **Confirm** the site location prior to placing orders or requests for proposal.  Provide the client with similar Site Requirements in RADIUS.  
- Site Confirmation should be displayed prominently on the Saved Site.
- Client Confirmation and Internal Site Verification must be performed on each Site.

### Proposal Phase
Consult Proposals should not be generated, delivered to the client, or awarded until the Site Verification has been completed.

- Following Site identification, the site should be displayed with a Red Triangle indicating that actions are required to proceed with Proposal generation or Award.
  - Requirements to clear the Red Triangle: 
    - Site Verified
    - Land-Use Specified
    - Client Price Populated
    - Service Turn around time populated
  - The Red Triangle hover message should list the Site Verification and Land use population as required elements to clear the Red Triangle.

-  OT User must browse to Site Details to perform Site Verification Requirements and mark the Site as Verified using the Site Verification button on the Site Page.

- The button should open a dialog that details the Site Verification Requirements and provides the user with "Verify" and "Cancel" buttons.  
  - Clicking "Verify" marks the Site as Verified, clearly indicating the OT User that performed Site Verification.
  - Clicking "Cancel" closes the dialog without changes.

- The "Generate Proposal" and "Award Proposal" buttons in Quote Manager are enabled once the Site is verified and client price and turn-around have been populated.

### Order Kick-Off
Orders are delivered to Production with a status of "Not Started". Site Verification must be completed prior to updating the status to "In Progress".  

- For Orders (i.e. Click Quote), the Order cannot be moved from “Not Started” to “In Progress” until the Site has been Verified.

- The Proposal should not be able to be awarded independently either.

---

## Site Verification process (est total time 3-10 minutes)

For all projects, we should provide the minimum data needed with the maximum level of accuracy. We should strive to make the process as fast as possible while not dropping below the minimum accuracy level required. We should not provide data that is not determinable to be correct unless there is a significant benefit for Cretelligent to do so, no matter how easy it is to access the data.

For all projects, the minimum required verification is listed below:

1. Locate the primary parcel. Review it to determine if it appears to be the same use that the client provided (i.e. The ordering party is Wendy’s. Is the parcel a fast food restaurant or adjacent to a fast food restaurant. Vacant land for a potential new build that is in a location that a fast food restaurant would be?). If yes, move to step 2, if no, check if the ownership name includes a name that would appear to be associated with the ordering party. If no, check if there is an address that is similar to the one provided within the same town that may indicate a typo by the client. If no, contact the client to determine if they have additional information as it does not appear that the parcel data they provided is correct.

2. Review all adjacent properties to determine if it is the same or similar ownership name. If yes, determine if the parcel appears to be used in conjunction with the primary parcel. If yes, repeat the same review for adjacent parcels of this parcel. Once all the parcels have been reviewed in this way, move to step 3.

3. Using the aerial view of this property, determine if all business activities for the existing business appear to be captured within the farthest extents of the green boundary lines. If no, review the name of the owner again to see if there are similarities that may have been missed in the first review. If no, review the tax mailing address. If it’s the same as the primary parcel include it. If no, contact the client to determine if this parcel should be included.

4. Finally, once all of the above are complete, review the aerial photo to determine if the employees and customers appear to have enough room to park within the green boundary. This will vary based on the use type. For example, if the facility is a self storage facility, there will need to be 1-2 spaces for employees and 3-4 spaces for client parking. For industrial, there need to be spaces for employees relative to the size of the building. For retail there need to be even more spaces relative to the size of the building. Use your best judgement. If you are not able to determine where the parking is located, use street view to see where you would park if you were visiting the facility. When parking is located under the building it can be difficult to determine by an aerial view. If parking appears to be on a parcel with a different ownership, our client may have a parking easement on another owner’s property. Contact the client to see if that parcel should be included with our reports.

Once all parcels are verified, and you’ve determine your have aggregated all of the subject property document the following data:

5. Total acreage (auto calculated in OT/Radius is adequate)

If an ESA or PCA is part of the quote, add the following:

6. Estimated sq ftg of the facility. Most of the time this can be easily determined. Look at the aerial view and a street view. Then review the footprint sq footage provided in OT. If it is a single story building the sq ftg should equal the footprint. If it is multiple stories, first look to see if the county data is populated. If it is, see if it appears to be reasonable based on the footprint size and the number of stories on the aerial. If you can’t make a determination, contact the client.

7. Current use of the facility. If the client has provided it, compare it to the aerial or street view. If different, contact the client for clarification. Based on their clarification, make a note in the site notes at this time to explain. A new field will be added called SPECIAL SITE DESCRIPTION that will be automatically sent to the vendor(s). This is where the clarification should be placed in the future.

If multi family residential, the following is required:

8. Total number of units (this must be provided by the client)
9. The total percentage of units required to be visited (this is based on the bank or agency requirements)

Next, if the following are easily verifiable, they should be entered as they are helpful to further refine the quote:

10. Total stories
11. Whether there is a large parking deck
12. Total number of buildings
13. Total number of units
14. Year built

