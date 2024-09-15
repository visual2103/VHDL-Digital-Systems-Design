<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
   
</head>
<body>
    <h1>Washing Machine Control System ⚙️</h1>
    <h2>Project Overview</h2>
    <p>This project designs a simple control system for a washing machine, with both manual and automatic modes. The system handles:</p>
    <ul>
        <li><strong>Manual Mode:</strong> Allows setting temperature (30°C, 40°C, 60°C, 90°C), spin speed (800, 1000, 1200 RPM), pre-wash, and extra rinse. The total run time depends on selected parameters.</li>
        <li><strong>Automatic Modes:</strong> Includes presets for Quick Wash, Shirts, Dark Colors, Dirty Laundry, and Anti-Allergic. Each mode has predefined settings and durations.</li>
    </ul>
    
  <h2>Key Features</h2>
    <ul>
        <li><strong>Initial State:</strong> Inactive with the door open.</li>
        <li><strong>User Interface:</strong> Buttons for selecting manual or automatic modes, setting parameters, and starting the machine.</li>
        <li><strong>Display:</strong> Shows program duration and remaining time using a 7-segment display.</li>
        <li><strong>Locking Mechanism:</strong> Door locks during operation and opens one minute after the program ends.</li>
        <li><strong>Stages:</strong> Includes washing, rinsing, and spinning with respective signals for each stage.</li>
    </ul>
    
  <h2>Components</h2>
    <ul>
        <li><strong>Frequency Divider:</strong> Generates timing signals.</li>
        <li><strong>Debouncer:</strong> Ensures clean button inputs.</li>
        <li><strong>7-Segment Display:</strong> Shows time and status.</li>
        <li><strong>Counter:</strong> Manages timing and stage indicators.</li>
    </ul>
    
  <h2>Setup and Usage</h2>
    <ul>
        <li><strong>Setup:</strong> Use Vivado to open the project, connect to the Nexys 4 board, and program the device.</li>
        <li><strong>Operation:</strong> Select manual or automatic mode, configure parameters, and start the machine. The remaining time and program status are displayed on the 7-segment display.</li>
    </ul>
    
  <h2>Future Enhancements</h2>
    <ul>
        <li>Integration with real washing machines.</li>
        <li>Addition of a pause button.</li>
        <li>Improved user interface with fewer switches.</li>
    </ul>
</body>
</html>
