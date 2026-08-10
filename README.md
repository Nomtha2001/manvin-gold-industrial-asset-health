# MANVIN GOLD — Industrial Asset Health & Reliability Monitoring
A Power BI-based industrial asset health and maintenance decision-support prototype for mining and process-plant environments.

# Current Status
Working prototype using simulated industrial telemetry.
MANVIN GOLD demonstrates how industrial equipment data can be transformed into actionable information for maintenance, reliability, operations and process-safety decision-making.

# What MANVIN Monitors
* Bearing temperature
* Vibration
* Pressure
* Motor current
* SO₂ gas
*Asset health
*Failure alerts
*Equipment condition
*Maintenance recommendations

# Decision-Support Workflow
  Monitor → Detect → Prioritize → Investigate → Act

The objective is to identify developing equipment risks earlier so maintenance teams have an opportunity to investigate and intervene before an equipment problem develops into an unexpected production interruption.

# Power BI Control Room
The dashboard provides visibility into:
* Total assets
* Active alarms
* Asset condition
* Asset health
* Failure alerts
* Maintenance recommendations
* Sensor-condition data
* Equipment and location filtering

Example:
Conveyor 4
* Health: 55%
* Alert: FAILURE PREDICTED
* Recommendation: STOP &amp; REPAIR — PREDICTED FAILURE

This demonstrates the transition from:
Telemetry → Condition Assessment → Alert → Maintenance Decision

# Potential Operational Value
# Equipment Reliability
-Helps identify assets requiring attention and supports condition-based maintenance.

# Reduced Unplanned-Downtime Risk
-Earlier identification of abnormal conditions can provide an opportunity for intervention before equipment failure.

# Maintenance Planning
-Helps maintenance teams prioritize inspections and maintenance activities.

# Production Continuity
-Supporting equipment availability can contribute to more stable production operations.

# Process Safety
-Indicators such as temperature, vibration, pressure and SO₂ can support identification of potentially unsafe conditions.

# Decision Support
-Converts equipment measurements into a structured condition and maintenance view.

The current prototype does not claim measured reductions in downtime or maintenance cost. These outcomes would require validation using historical plant, maintenance and failure data.

# Technology Stack
# Technology	    Role
Power BI	     Industrial dashboard and visualization
DAX         	 Asset-health and maintenance decision 
SQL Server	   Data storage and querying
Python	       Telemetry processing and automation
Azure IoT      Industrial IoT connectivity roadmap
WhatsApp	     Prototype operational alerting

# Future Development
With historical equipment and maintenance data, MANVIN can be extended to support:
* Asset health trends
* Failure history
* Root Cause Analysis (RCA)
* Reliability analysis
* MTBF
* MTTR
* Failure-pattern detection
* Advanced predictive maintenance
* Downtime analysis
* Maintenance-cost analysis
* Reliability by equipment

# Industrial IoT Architecture
Sensors / PLCs → Industrial Gateway → Azure IoT → Data Layer → Analytics → Power BI → Operational Alerts

The long-term objective is to connect live industrial telemetry with analytics and maintenance decision support.

# Portfolio Objective
MANVIN GOLD demonstrates how industrial telemetry, data engineering, analytics, cloud connectivity and visualization can be combined into an industrial asset-health and maintenance decision-support solution.

Detect earlier → Investigate faster → Plan maintenance better → Reduce failure risk → Improve equipment reliability.
