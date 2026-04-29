# CalendarEventRecurrence

Details about how a recurring event will be scheduled. If the event is to be scheduled indefinitely, this will lack an \"end\" property.

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**days_of_week** | [**list[CalendarDayOfWeek]**](CalendarDayOfWeek.md) | Which days of the week the event will be scheduled, only valid/present for \&quot;weekly\&quot; recurring events | [optional] 
**end** | [**CalendarEventRecurrenceEnd**](CalendarEventRecurrenceEnd.md) |  | [optional] 
**frequency** | [**CalendarEventFrequency**](CalendarEventFrequency.md) |  | 
**interval** | **int** | How often the event will be scheduled, in units of \&quot;frequency\&quot; | 
**timezone** | **str** | The timezone the event will be scheduled in, in Area/Location format | 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


