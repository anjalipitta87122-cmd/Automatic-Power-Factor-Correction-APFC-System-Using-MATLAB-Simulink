# Automatic-Power-Factor-Correction-APFC-System-Using-MATLAB-Simulink
Developed a MATLAB/Simulink-based Automatic Power Factor Correction (APFC) system for three-phase power networks. Implemented real-time power factor monitoring, reactive power compensation, capacitor bank switching, and MATLAB-based control logic to improve system efficiency and maintain power factor close to unity.

System Design

The simulation consists of a three-phase source, voltage-current measurement blocks, power factor calculation subsystem, MATLAB-based APFC control logic, capacitor bank switching network, and RLC loads. A custom MATLAB Function Block generates switching signals (S1–S4) that dynamically connect or disconnect capacitor banks based on the measured power factor.

Working Principle

The system continuously evaluates active power, reactive power, and power factor under varying load conditions. When the power factor drops below the desired threshold due to inductive loading, the controller activates appropriate capacitor banks to compensate reactive power demand. This closed-loop control mechanism improves power factor, reduces current drawn from the source, and enhances overall system efficiency.

Key Features
Developed using MATLAB R2024a & Simulink
Three-phase power system modeling
Real-time power factor monitoring
Automatic capacitor bank switching
Closed-loop control implementation

Results
The proposed APFC system successfully improved the power factor from approximately 0.89 to nearly unity, reducing reactive power consumption and improving power quality, voltage regulation, and overall system performance.

Skills Demonstrated
MATLAB R2024a • Simulink • Power Systems • APFC • Reactive Power Compensation • Control Systems • Three-Phase Networks • Electrical System Modeling
