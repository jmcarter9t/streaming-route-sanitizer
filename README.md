# Streaming Route Sanitizer

Connected vehicle technology uses in-vehicle wireless transceivers to broadcast and receive basic safety messages (BSMs)
that include accurate spatiotemporal information to enhance transportation safety. These devices rely on integrated
Global Positioning System (GPS) measurements to improve driving safety.  Databases, some publicly available, of BSM
sequences, called trajectories, are being used to develop safety and traffic management applications. BSMs do not
contain explicit identifiers that link trajectories to individuals; however, the locations they expose may be sensitive
and associated with a very small subset of the population; protecting these locations from unwanted disclosure is
important. Public sector policies require research data that is made publically available should be recorded in such a
manner that subjects cannot be identified, directly or through identifiers linked to the subjects. A procedure that
minimizes the risk of associating trajectories with individuals, or de-identification, is necessary to meet open data
requirements. 

Streaming-route-sanitizer is a US Department of Transportation Joint Program Office (JPO) connected vehicle data project designed
to de-identify streams of connected vehicle BSMs. It is being developed to operate as a component of the [Operational Data Environment (ODE)](https://github.com/usdot-jpo-ode).

