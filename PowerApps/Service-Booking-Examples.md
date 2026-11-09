# Service Booking Management - Power Apps

## Project Overview
Proposed Power Apps Canvas App for managing
cleaning service bookings and customer requests.

## Suggested Screens
- Booking Dashboard
- New Booking Form
- Customer Details
- Booking Status
- Service Management

## Power Fx Examples

### Create Booking

```powerfx
Patch(
    ServiceBookings,
    Defaults(ServiceBookings),
    {
        Title: txtCustomerName.Text,
        ServiceType: txtServiceType.Text,
        BookingDate: dpBookingDate.SelectedDate,
        Status: "Pending"
    }
)
```

### View Pending Bookings

```powerfx
Filter(
    ServiceBookings,
    Status = "Pending"
)
```

## Implementation Status
Illustrative formulas only.

ServiceBookings and the referenced controls
must be configured in Power Apps before use.
