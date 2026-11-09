# Dataverse - Proposed Service Booking Schema

## Table: ServiceBookings

| Column | Data Type |
|---|---|
| CustomerName | Text |
| CustomerEmail | Email/Text |
| ServiceType | Choice |
| BookingDate | Date |
| PropertyAddress | Multiline Text |
| BookingStatus | Choice |
| AssignedStaff | Lookup |
| SpecialInstructions | Multiline Text |

## Proposed Booking Statuses
- Pending
- Confirmed
- In Progress
- Completed
- Cancelled

## Implementation Status
Proposed data model only.
Dataverse tables have not been deployed.
