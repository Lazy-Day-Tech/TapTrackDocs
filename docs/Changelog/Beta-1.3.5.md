# Beta-1.3.5

## What's New: 
- Added support for checking in/out multiple rental items within a single booking
  - Override feature (ignores counters and performs action)
  - Log which rafts for booking have been checked in and/or out
  - Will now preserve record view state after action
  - Improve BookingRecordView to work with smaller devices
  - Warning if attempting to check out a raft that is not associated to the booking
  - Added warning for if rental item for booking has already been checked-out
- Flags
  - Display which rafts have been recycled (Currently only supported in ManualInput due to rate limitations)
  - Add customer flags to ManualInput 