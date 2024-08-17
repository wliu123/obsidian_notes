[[Logistics Delivery App Project Overview]]

## Purpose

The purpose of this section is to provide a general overview of the individuals that will be using this application and those who will be interacting with the users of the application from a 3rd party perspective.
## Key Points

- Drivers are the primary users of the application
- Warehouse personnel are indirect users of the application as drivers only use the app to pickup packages from the warehouse
- Packages belonging to the customer should be able to communicate with drivers 
## Detailed Information

Driver Persona:

Drivers will mostly be either English or Mandarin speaking drivers and will need the ability to read functions within the app in either languages along with the chat feature. Drivers should be able to 
perform the following:
- Scan the packages to gather information about the customer they're delivering to including (phone, address, name) 
- Drivers should be able to navigate to the address of the package
- Drivers should be able to take a photo of the completed delivery and mark that the package has been delivered
- Drivers have little technology proficiency so the app should be user friendly
- Should drivers be unable to delivery the package successfully, drivers should be able to still take a photo and mark incomplete delivery along with reason
- If driver is in an area with bad reception, driver should still be able to take the photo and submit for completion once driver is in an area of good reception
- Driver should be able to mark that driver is starting their route
- Driver should be able to communicate via text or phone with the customer at any time during the package delivery trip
- If driver is unable to successfully complete a package delivery and warehouse reaches out to driver with updated delivery information, driver will make the decision as to whether to complete the trip or leave it as unsuccessful. Failed trips should not disappear from queue

Warehouse Staff Persona:

Warehouse staff will typically just be providing the drivers with the packages for the day. The day prior, warehouse staff will always notify client of the number of packages to be delivered for the following day so that he is able to plan accordingly. Warehouse staff should also receive notifications from the drivers once drivers are starting their routes along with when there are completions or failures of deliveries.

Customer Persona:

Customers should not have access to the app and will only be the recipients of the package. Customers will only know the drivers information when the driver reaches out via text/phone call. Customers note to driver regarding package delivery information should be shown to driver in the app. If delivery of package is missed, customer must contact warehouse staff with correct information and warehouse staff is responsible for contacting driver.

## Decisions and Open Questions

- [ ] Customer and Drivers never interact unless driver reaches out first
- [ ] Failed trips still have the ability to be modified and are not removed from queue?

## Related Sections

- [[Info Gathering 8.14.24]]
- [[Project Scope]]

## Resources


---
tags: [persona, driver, customer, warehouse]
status: in-progress
assigned: William

---
Last Updated: 8/17/2024
