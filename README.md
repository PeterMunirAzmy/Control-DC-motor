  <h1>Position Control System with PID</h1>

   <h2>Table of Contents</h2>
    <ul>
        <li><a href="#project-objective">Project Objective</a></li>
        <li><a href="#how-the-project-works">How the Project Works</a></li>
        <li><a href="#design-procedures">Design Procedures</a></li>
        <li><a href="#materials-and-components">Materials and Components</a></li>
        <li><a href="#coding">Coding</a></li>
        <li><a href="#pid-tuning">PID Tuning</a></li>
        <li><a href="#conclusion">Conclusion</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>

   <h2 id="project-objective">Project Objective</h2>
    <p>
        The main objective of this project is to create a position control system through a closed-loop feedback mechanism. The key goals are:
    </p>
    <ul>
        <li>To convert a DC motor into a servo motor through a position control system.</li>
        <li>To understand the effect of PID parameters on system performance.</li>
        <li>To learn how to tune the controller parameters for optimal performance.</li>
    </ul>
    <p>
        The system should be able to achieve any angular position set point.
    </p>

   <h2 id="how-the-project-works">How the Project Works</h2>
    <ol>
        <li>The angle value is changed by 45 degrees through Arduino code.</li>
        <li>The driver receives the signal and transfers it to the motor as a voltage from an external power source.</li>
        <li>The motor rotates the encoder with a certain number of steps as per the Arduino's value and sends the feedback to the Arduino to compare it with the required value and correct it using the values of K<sub>p</sub>, K<sub>i</sub>, and K<sub>d</sub>.</li>
    </ol>

   <h2 id="design-procedures">Design Procedures</h2>
    <ul>
        <li>Brainstorming about the design, electronic components, and the circuit diagram.</li>
        <li>Purchasing the materials and electronic components.</li>
        <li>Assembly of components.</li>
        <li>Writing the code for the system.</li>
        <li>Tuning PID parameters to achieve the best system response.</li>
    </ul>

   <h2 id="materials-and-components">Materials and Components</h2>
    <ul>
        <li>Arduino board</li>
        <li>DC motor</li>
        <li>Encoder</li>
        <li>Motor driver</li>
        <li>Power supply</li>
        <li>Wires and connectors</li>
    </ul>

   <h2 id="coding">Coding</h2>
    <p> Position_Control/Position_Control.ino </p>

   <h2 id="pid-tuning">PID Tuning</h2>
    <p>
        Tuning the PID parameters (K<sub>p</sub>, K<sub>i</sub>, and K<sub>d</sub>) is crucial for achieving optimal system performance. Start with the Ziegler-Nichols method or trial and error to find the best values for your system.
    </p>

   <h2 id="conclusion">Conclusion</h2>
    <p>
        This project demonstrates the conversion of a DC motor into a servo motor using a position control system. By understanding and tuning the PID parameters, the system can achieve precise angular positions within the desired range.
    </p>

   <h2 id="contact">Contact</h2>
    <p>If you have any questions or need further assistance, please contact Peter Munir at <a href="mailto:peter.munir2000@gmail.com">peter.munir2000@gmail.com</a>.</p>
</body>
</html>
