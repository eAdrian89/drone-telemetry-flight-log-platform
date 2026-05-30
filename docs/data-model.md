# Data Model

## Flight Session

Represents a single UAV usage session.

Fields:

- flightId
- deviceId
- operatorId
- startedAt
- endedAt
- durationSeconds
- location
- purpose
- status

## Telemetry Event

Represents a single telemetry-like event.

Fields:

- eventId
- flightId
- timestamp
- altitudeMeters
- distanceMeters
- speedMs
- batteryPercent
- gpsSatellites
- signalQuality

## Battery Event

Represents battery usage during a flight session.

Fields:

- eventId
- flightId
- batterySerialNumber
- timestamp
- batteryPercent
- temperatureCelsius
- cycleCount

## Media Asset

Represents a photo or video file generated during a flight.

Fields:

- assetId
- flightId
- fileName
- mediaType
- resolution
- durationSeconds
- sizeBytes
- capturedAt