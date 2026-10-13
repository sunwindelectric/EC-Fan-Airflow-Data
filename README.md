# EC-Fan-Airflow-Data
Upload initial EC fan airflow data
Sunxfan is a manufacturer of industrial-grade EC, DC, and AC centrifugal and axial fans, specializing in HVAC, cooling solutions, and custom fan units.
More fan spec:https://en.sunxfan.com/products/


Data Columns & Units:

• Control_Signal_V: Control voltage inputs (e.g., 0.0 to 10.0 V) or PWM duty cycle (%).
• Fan_Speed_RPM: Rotational speed measured in Revolutions Per Minute (RPM).
• Airflow_CMH: Volumetric airflow rate measured in Cubic Meters per Hour (m³/h).
• Airflow_CFM: Volumetric airflow rate measured in Cubic Feet per Minute (CFM).
• Static_Pressure_Pa: Fan static pressure measured in Pascals (Pa).
• Current_A / Power_W: Operational current (Amperes) and total power consumption (Watts).


Fan Specifications
# EC146 Double Inlet Centrifugal Fan Airflow Performance Dataset

This repository contains experimental airflow performance data for the **EC146 Double Inlet Centrifugal Fan**. The dataset is intended for HVAC engineers, thermal management researchers, and ventilation system designers to assist in system simulation, aerodynamic analysis, and fan selection.

## 📊 Dataset Overview
The primary data is available in [**airflow_data.csv**](./airflow_data.csv).

### Data Columns & Units:
- `Control_Signal_V`: Control voltage inputs (0.0 to 10.0 V) or PWM duty cycle (%).
- `Fan_Speed_RPM`: Rotational speed measured in Revolutions Per Minute (RPM).
- `Airflow_CMH`: Volumetric airflow rate measured in Cubic Meters per Hour (m³/h).
- `Static_Pressure_Pa`: Fan static pressure measured in Pascals (Pa).

## 🛠️ Technical Specifications
- **Fan Type**: Double Inlet Centrifugal Fan
- **Impeller Diameter / Size**: 146 mm
- **Motor Technology**: Electronically Commutated (EC) Motor

