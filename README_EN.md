# PID_Simulator

[中文版](README.md) | English

A PID Controller Tuning Simulator with Advanced Features Built with MATLAB

![PID Simulator Interface](image.png)

## Features

- **Real-time PID Parameter Tuning**: Adjust PID parameters (Kp, Ki, Kd) using interactive sliders
- **System Configuration**: Configure system inertia (J) and damping (b) parameters
- **Input Signal Types**: 
  - Step Response
  - Sine Wave Tracking
- **Advanced PID Functions**:
  - Derivative on Measurement
  - Integral Separation
  - Integral Limiting (Anti-windup)
- **Noise Simulation**: Add feedback noise to simulate real-world conditions
- **Low-pass Filtering**: Apply filters to derivative term or entire feedback signal
- **Real-time Visualization**: View system response and individual PID component contributions

## Usage

1. Open MATLAB
2. Run the script:
   ```matlab
   pid_tuner_gui
   ```
3. Use the sliders on the right panel to adjust PID parameters, system characteristics, and advanced features
4. Select input signal type from the dropdown menu at the bottom left
5. Click "Start Simulation" button to run the simulation
6. View the system response in the main plot and PID component details in the separate window

## Parameters

### PID Parameters
- **Proportional (Kp)**: Range 0-500, Default: 50
- **Integral (Ki)**: Range 0-200, Default: 20
- **Derivative (Kd)**: Range 0-100, Default: 5

### System Parameters
- **System Inertia (J)**: Range 1-50, Default: 10
- **System Damping (b)**: Range 0.1-50, Default: 2

### Advanced Features
- **Integral Separation Threshold**: Range 0.01-2, Default: 0.2
- **Integral Limit**: Range 1-100, Default: 20
- **Feedback Noise Amplitude**: Range 0-0.5, Default: 0.01
- **Filter Cutoff Frequency (Hz)**: Range 1-200, Default: 20

## Requirements

- MATLAB (with Control System Toolbox)

## Author

liuskywalkerjskd

## License

See [LICENSE](LICENSE) file for details.
