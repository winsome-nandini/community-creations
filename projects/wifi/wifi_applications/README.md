### Description

Added a new IoT project: **Automatic Vehicle Speed Limiter for School and Hospital Zones**.

Automatic Vehicle Speed Limiter for School and Hospital Zones is an intelligent transportation safety system designed to automatically regulate and enforce vehicle speed limits within sensitive areas such as schools, hospitals, residential communities, and pedestrian zones. The project combines RFID-based zone identification, real-time speed monitoring, embedded control, and cloud connectivity to improve road safety and reduce accidents caused by overspeeding.

The system utilizes RFID tags installed at the entry and exit points of restricted zones. An onboard RC522 RFID reader detects these tags and communicates with the Silicon Labs SiWx917 Wireless MCU, which continuously monitors vehicle speed using a Hall-effect sensor mounted on the motor shaft. When a vehicle enters a restricted zone, the controller retrieves the predefined speed limit and automatically activates speed-governance mode. If the vehicle exceeds the configured limit, the system dynamically regulates motor power using PWM-based control through the motor driver, preventing further acceleration beyond the permitted speed.

The integrated Wi-Fi capability of the SiWx917 enables future cloud connectivity for real-time monitoring, speed analytics, violation tracking, and smart-city transportation integration. The architecture is designed to support intelligent traffic management, pedestrian safety, school-zone protection, hospital-zone enforcement, and next-generation connected transportation systems.

---

### Project GitHub URL

https://github.com/winsome-nandini/Automatic-Vehicle-Speed-Limiter-for-School-Hospital-Zones

---

### Checklist

* [x] I have read the [Contributor License Agreement](https://github.com/SiliconLabsSoftware/agreements-and-guidelines/blob/main/contributor_license_agreement.md).
* [x] The linked GitHub repository is public and accessible.
* [x] The linked GitHub repository includes a license file.
* [x] I added my entry to the correct category listing table under projects/ (appended at the bottom; did not reorder existing rows).

---

### Additional Notes

This project focuses on intelligent speed governance and road safety through automated vehicle speed regulation in school and hospital zones. The system combines RFID-based zone detection, real-time speed monitoring, embedded control using the Silicon Labs SiWx917 platform, Hall-effect sensor feedback, and PWM-based motor control to enforce configurable speed limits without driver intervention.

The architecture is designed to support smart transportation systems, connected vehicle infrastructure, traffic safety enhancement, accident prevention, and future smart-city deployments through Wi-Fi-enabled monitoring and cloud-based analytics. Future enhancements include GPS-based geofencing, Vehicle-to-Infrastructure (V2I) communication, emergency vehicle override mechanisms, AI-driven traffic analytics, and remote speed-limit management through cloud services.
