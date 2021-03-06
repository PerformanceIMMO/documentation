## Liste des évènement de l'entité `Ticket`

- `CallEmittedTo`  
{  
  "processUid": [SafeUUID](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#safeuuid),  
  "aggregateUid": [SafeUUID](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#safeuuid),  
  "operator": [Operator](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#operator-enum),  
  "sentDate": [DateTime](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#datetime),  
  "recipient": [Persona](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#persona-enum),  
  "comment": [Option](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#option)[String],  
  "medium": [ContactMedium](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#contactmedium-enum),  
  "date": [DateTime](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#datetime),  
  "eventType":"CallEmittedTo"  
}

- `CallReceived`  
{  
  "processUid": [SafeUUID](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#safeuuid),  
  "aggregateUid": [SafeUUID](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#safeuuid),  
  "operator": [Operator](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#operator-enum),  
  "sentDate": [DateTime](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#datetime),  
  "caller": String,  
  "callPurpose": String,  
  "comment": [Option](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#option)[String],  
  "medium": [ContactMedium](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#contactmedium-enum),  
  "date": [DateTime](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#datetime),  
  "eventType":"CallReceived"  
}

- `ProviderAssigned`  
{  
  "processUid": [SafeUUID](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#safeuuid),  
  "aggregateUid": [SafeUUID](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#safeuuid),  
  "operator": [Operator](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#operator-enum),  
  "sentDate": [DateTime](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#datetime),  
  "provider": [Provider](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#provider-enum),  
  "purpose": [ProviderAssignationPurpose](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#providerassignationpurpose-enum),  
  "date": [DateTime](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#datetime),  
  "eventType":"ProviderAssigned"  
}

- `CallAnsweredByProvider`  
{  
  "processUid": [SafeUUID](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#safeuuid),  
  "aggregateUid": [SafeUUID](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#safeuuid),  
  "operator": [Operator](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#operator-enum),  
  "sentDate": [DateTime](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#datetime),  
  "provider": [Provider](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#provider-enum),  
  "comment": [Option](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#option)[String],  
  "date": [DateTime](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#datetime),  
  "eventType":"CallAnsweredByProvider"  
}

- `CallNotAnsweredByProvider`  
{  
  "processUid": [SafeUUID](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#safeuuid),  
  "aggregateUid": [SafeUUID](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#safeuuid),  
  "operator": [Operator](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#operator-enum),  
  "sentDate": [DateTime](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#datetime),  
  "provider": [Provider](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#provider-enum),  
  "comment": [Option](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#option)[String],  
  "date": [DateTime](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#datetime),  
  "eventType":"CallNotAnsweredByProvider"  
}

- `MissionAccepted`  
{  
  "processUid": [SafeUUID](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#safeuuid),  
  "aggregateUid": [SafeUUID](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#safeuuid),  
  "operator": [Operator](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#operator-enum),  
  "sentDate": [DateTime](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#datetime),  
  "provider": [Provider](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#provider-enum),  
  "comment": [Option](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#option)[String],  
  "date": [DateTime](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#datetime),  
  "eventType":"MisionAccepted"  
}

- `MissionRefused`  
{  
  "processUid": [SafeUUID](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#safeuuid),  
  "aggregateUid": [SafeUUID](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#safeuuid),  
  "operator": [Operator](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#operator-enum),  
  "sentDate": [DateTime](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#datetime),  
  "provider": [Provider](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#provider-enum),  
  "comment": [Option](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#option)[String],  
  "date": [DateTime](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#datetime),  
  "eventType":"MissionRefused"  
}

- `TicketReopened`  
{  
  "processUid": [SafeUUID](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#safeuuid),  
  "aggregateUid": [SafeUUID](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#safeuuid),  
  "operator": [Operator](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#operator-enum),  
  "sentDate": [DateTime](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#datetime),  
  "date": [DateTime](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#datetime),  
  "purpose": [Option](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#option)[String],  
  "eventType":"TicketReopened"  
}

- `LogTrialAdded` Évènement générique du journal  
{  
  "processUid": [SafeUUID](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#safeuuid),  
  "aggregateUid": [SafeUUID](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#safeuuid),  
  "operator": [Operator](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#operator-enum),  
  "provider": [Option](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#option)[[Provider]](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#provider-enum),    
  "sentDate": [DateTime](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#datetime),  
  "logTrial": [LogTrial](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#logtrial),    
  "logTrialAddedDate": [DateTime](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#datetime),  
  "eventType":"LogTrialAdded"  
}

- `MessageAdded`  
case class AddMessage(processUid: SafeUUID,
                      aggregateUid: SafeUUID,
                      operator: Operator,
                      sentDate: DateTime,
                      message: String,
                      messageAddedDate: DateTime) extends OtherTicketCommand

- `TicketCanceled`  
case class CancelTicket(processUid: SafeUUID,
                        aggregateUid: SafeUUID,
                        operator: Operator,
                        sentDate: DateTime,
                        date: DateTime) extends OtherTicketCommand

- `ArrivedOnSite`  
case class ArriveOnSite(processUid: SafeUUID,
                        aggregateUid: SafeUUID,
                        provider: Provider,
                        operator: Operator,
                        sentDate: DateTime,
                        date: DateTime) extends OtherTicketCommand

- `GoneFromSite`    
case class GoFromSite(processUid: SafeUUID,
                      aggregateUid: SafeUUID,
                      provider: Provider,
                      operator: Operator,
                      sentDate: DateTime,
                      date: DateTime) extends OtherTicketCommand

- `InterventionStarted`  
{  
  "processUid": [SafeUUID](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#safeuuid),  
  "aggregateUid": [SafeUUID](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#safeuuid),  
  "operator": [Operator](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#operator-enum),  
  "sentDate": [DateTime](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#datetime),  
  "provider": [Provider](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#provider-enum),  
  "startedDate": [DateTime](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#datetime),  
  "eventType":"InterventionStarted"  
}

- `InterventionFinished`  
case class FinishIntervention(processUid: SafeUUID,
                              aggregateUid: SafeUUID,
                              finishedDate: DateTime,
                              operator: Operator,
                              provider: Provider,
                              sentDate: DateTime) extends OtherTicketCommand


### Évènements de clôture

- `TicketClosed`  
{  
  "processUid": [SafeUUID](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#safeuuid),  
  "aggregateUid": [SafeUUID](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#safeuuid),  
  "operator": [Operator](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#operator-enum),  
  "brakedownNature": [Option](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#option)[String],    
  "sentDate": [DateTime](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#datetime),  
  "provider": [Option](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#option)[[Provider]](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#provider-enum),  
  "stillOnSite": [StillOnSite](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#stillonsite-enum),  
  "report": [Option](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#option)[String],  
  "result": [Option](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#option)[String],  
  "closingDate": [DateTime](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#datetime),  
  "eventType":"TicketClosed"  
}

-  `TicketArchived`  
{  
  "processUid": [SafeUUID](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#safeuuid),  
  "aggregateUid": [SafeUUID](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#safeuuid),  
  "operator": [Operator](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#operator-enum),  
  "comment": [Option](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#option)[String],
  "sentDate": [DateTime](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#datetime),  
  "closingDate": [DateTime](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#datetime),  
  "eventType":"TicketArchived"  
}

- `PermanentlyFixed`  
{  
  "processUid": [SafeUUID](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#safeuuid),  
  "aggregateUid": [SafeUUID](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#safeuuid),  
  "operator": [Operator](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#operator-enum),  
  "brakedownNature": [Option](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#option)[String],    
  "sentDate": [DateTime](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#datetime),  
  "provider": [Option](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#option)[[Provider]](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#provider-enum),  
  "stillOnSite": [StillOnSite](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#stillonsite-enum),  
  "report": [Option](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#option)[String],  
  "closingDate": [DateTime](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#datetime),  
  "eventType":"PermanentlyFixed"  
}

- `PartiallyFixed`  
{  
  "processUid": [SafeUUID](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#safeuuid),  
  "aggregateUid": [SafeUUID](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#safeuuid),  
  "operator": [Operator](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#operator-enum),  
  "brakedownNature": [Option](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#option)[String],    
  "sentDate": [DateTime](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#datetime),  
  "provider": [Option](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#option)[[Provider]](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#provider-enum),  
  "stillOnSite": [StillOnSite](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#stillonsite-enum),  
  "report": [Option](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#option)[String],  
  "closingDate": [DateTime](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#datetime),  
  "eventType":"PartiallyFixed"  
}

- `TicketClosedImpossibleRepair`  
{  
  "processUid": [SafeUUID](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#safeuuid),  
  "aggregateUid": [SafeUUID](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#safeuuid),  
  "operator": [Operator](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#operator-enum),  
  "brakedownNature": [Option](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#option)[String],    
  "sentDate": [DateTime](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#datetime),  
  "provider": [Option](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#option)[[Provider]](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#provider-enum),  
  "stillOnSite": [StillOnSite](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#stillonsite-enum),  
  "report": [Option](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#option)[String],  
  "closingDate": [DateTime](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#datetime),  
  "eventType":"TicketClosedImpossibleRepair"  
}

- `PostponedFix`  
{  
  "processUid": [SafeUUID](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#safeuuid),  
  "aggregateUid": [SafeUUID](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#safeuuid),  
  "operator": [Operator](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#operator-enum),  
  "brakedownNature": [Option](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#option)[String],    
  "sentDate": [DateTime](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#datetime),  
  "provider": [Option](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#option)[[Provider]](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#provider-enum),  
  "stillOnSite": [StillOnSite](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#stillonsite-enum),  
  "report": [Option](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#option)[String],  
  "closingDate": [DateTime](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#datetime),  
  "eventType":"PostponedFix"  
}

- `ClosedBeyondCallCenterScope`  
{  
  "processUid": [SafeUUID](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#safeuuid),  
  "aggregateUid": [SafeUUID](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#safeuuid),  
  "operator": [Operator](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#operator-enum),  
  "sentDate": [DateTime](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#datetime),  
  "closingDate": [DateTime](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#datetime),  
  "eventType":"ClosedBeyondCallCenterScope"  
}

- `ClosedAfterSeveralUnsuccessfulRecalls`  
{  
  "processUid": [SafeUUID](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#safeuuid),  
  "aggregateUid": [SafeUUID](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#safeuuid),  
  "operator": [Operator](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#operator-enum),  
  "sentDate": [DateTime](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#datetime),  
  "closingDate": [DateTime](https://github.com/PerformanceIMMO/documentation/blob/master/Models.md#datetime),  
  "eventType":"ClosedAfterSeveralUnsuccessfulRecalls"  
}

### Évènements de compensation

- `TicketUpdated`  
case class UpdateTicket(processUid: SafeUUID,
                        aggregateUid: SafeUUID,
                        operator: Operator,
                        locationRef: LocationReference,
                        ticket: TicketInfos,
                        sentDate: DateTime,
                        date: DateTime) extends OtherTicketCommand
