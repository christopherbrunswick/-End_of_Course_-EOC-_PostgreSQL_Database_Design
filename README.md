# -End_of_Course_-EOC-_PostgreSQL_Database_Design

# Assignment-1
Suppose that you are tasked with designing a (simplified) database for a national shipping and logistics company. This company operates throughout the continental United States. A customer will buy a shipment from a sales_person, where a shipment is defined as one entire tractor trailer load full of goods. A shipment requires the use of a tractor and either one or two trailers hitched in tandem, which are owned by someone called a contractor. Shipments are transported by drivers, and each shipment can have one or two drivers.

  STEP 1 - Specification of Data Requirements
  Part 1 - Entity Set Descriptions
  
  Shipments: A shipment is defined as the transportation of an entire tractor trailer load of goods from an origin to a destination; a shipment does not refer to individual boxes (like USPS, UPS, or Amazon). A shipment entity is defined by the following attributes:
  - shipment_ID
  - pickup_date
  - pickup_time
  - delivery_date
  - delivery_time
  - billed_date 
  - paid_date
  - origin_address
  - destination_address
  - commodity
  - shipment_notes
  
 Customers: A customer is someone who pays to have goods shipped. A customer is defined by the following attributes:
 
