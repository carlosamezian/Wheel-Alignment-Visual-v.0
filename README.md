# Wheel-Alignment-Visual-v.0
This simulator translates raw degrees and minutes into a live physics model, demonstrating how minor adjustments to a single wheel can lead to significant vehicle pull and accelerated tire wear.

🚀 Key Features

    6-Variable Physics Engine: Real-time calculation of "Net Pull" based on the interaction of independent Left/Right Camber, Left/Right Toe, and Rear Thrust Angle.

    Laser-Guided Heading: A dynamic projection system showing the vehicle's vector of intent vs. its actual displacement.

    Functional Steering HUD: A real-time steering wheel gauge that rotates to show the "counter-steer" required to maintain a straight path.

    Tire Life Heat-Mapping: Visual indicators on the tire contact patches that change color (Red/Green) based on excessive wear patterns caused by out-of-spec geometry.

    Professional Reporting: A diagnostic table that categorizes Front Set and Rear Set data, providing automated adjustment recommendations to neutralize drift.

💻 Tech Stack

    Language: JavaScript (ES6+)

    Engine: HTML5 Canvas API (rendering at 60 FPS)

    Logic: Custom trigonometry-based drift and rotation algorithms.

    UI/UX: CSS3 Grid & Flexbox with a professional "Dark Mode" dashboard aesthetic.

🧠 The Physics Behind the Pull

The simulation isn't just "moving an image"; it calculates a Net Drift Vector using:

    Toe Pull: Balancing the pressure between Left and Right Toe angles.

    Camber Thrust: Simulating the "rolling cone" effect where a tilted tire pulls the chassis toward the side of most positive camber.

    Thrust Line Offset: Calculating the "dog-tracking" effect caused by a misaligned rear axle.
