# Report Switches Status

This Home Assistant blueprint reports all switches and binary sensors that are currently ON within specified groups.

## Inputs

- **Group with switches**: Group of switch entities to monitor.
- **Group with binary sensors**: Group of binary sensor entities.
- **Notify target**: Notification script or service.
- **Time to run**: Time of day to run the automation.

## Example

This blueprint sends a summary message of which devices are ON every day at a specified time.


