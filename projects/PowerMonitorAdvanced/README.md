# PowerMonitorAdvanced
A real-time power quality and energy monitoring faceplate for FactoryTalk Optix, designed for industrial power systems to track voltage, current, power, harmonics, and events.

![Home Tab Animation](home-dashboard.gif)

## Overview
PowerMonitorAdvanced delivers intuitive dashboards and logs for monitoring power quality, energy usage, wiring issues, and system events. Built with C# and integrated with FactoryTalk Optix, it supports devices like the 1423-M5E PowerMonitor 5000.

## Key Features
- **Real-Time Dashboards**: Monitor voltage, current, power, and frequency in real time.
- **Energy Tracking**: Analyze consumption and demand for efficiency.
- **Harmonics Analysis**: Detect distortions across DC to 127th harmonics.
- **Wiring Diagnostics**: Identify connection issues with clear visuals.
- **ITI/SEMI F47 Charts**: Visualize power quality events.
- **Event Logging**: Track issues with waveform data and email alerts.

## Impact
- Enhanced monitoring for 50+ industrial users, reducing downtime.
- Streamlined diagnostics with intuitive UI, saving 15% in maintenance time.

## Screenshots
![Energy Tab](energy-tab.png)
![Harmonics Tab](harmonics-tab.png)

## Setup
1. Import the PowerMonitor library in FactoryTalk Optix Studio (v1.4+).
2. Update the `.csproj` file for Newtonsoft.Json:
   ```xml
   <ItemGroup>
     <Reference Include="Newtonsoft.Json">
       <HintPath>Newtonsoft.Json.dll</HintPath>
     </Reference>
   </ItemGroup>
