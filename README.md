# Switch Mode Power Supply in Computer Systems
# 1. Introduction:

A Switch Mode Power Supply (SMPS) is an electronic circuit that converts electrical power from one form to another using high-speed switching. It turns the power ON and OFF very quickly and uses inductors, capacitors, and transformers to smooth and control the output.Because it works at high frequency, an SMPS is small, lightweight, and more efficient than normal power supplies. It is used in chargers, TVs, computers, LED drivers, and almost all modern electronics.

<img width="800" height="450" alt="image" src="https://github.com/user-attachments/assets/6f36304e-1d6a-4646-a29c-b0ae48aac617" />

<img width="994" height="358" alt="Screenshot 2025-11-10 112625" src="https://github.com/user-attachments/assets/0d83a3e4-0e35-403e-a444-be18072dbfa6" />


In an SMPS:

i)A solenoid-type inductor stores energy during switching.

ii)A toroidal inductor filters noise and reduces EMI.

iii)The general inductance principle helps control current and keep the output stable.

# 2. Inductance:

# Explanation

Inductance is the property of an electrical conductor that opposes any change in current flowing through it.When current passes through a coil, it creates a magnetic field. If the current changes, the magnetic field also changes, and this changing field induces a voltage (called back EMF) that opposes the change.This behavior is known as electromagnetic induction.

<img width="709" height="358" alt="Screenshot 2025-11-09 212512" src="https://github.com/user-attachments/assets/7a9a9ba1-cb0e-4bf9-a42d-e06bcc839219" />

# Real time application in SMPS

<img width="686" height="386" alt="image" src="https://github.com/user-attachments/assets/d89b1636-59cb-4341-9140-a1de33f9a71c" />

Inductance in an SMPS helps store energy in the magnetic field when current flows through a coil. When the switching device turns OFF, the stored energy is released, which keeps the output current smooth. This prevents sudden changes in current and helps maintain a stable DC voltage. Without inductance, the SMPS output would fluctuate and become unstable.

# How Inductance Helps in Power Delivery

Inductance works like a temporary energy storage element.When the switch is ON, the inductor stores energy in its magnetic field.When the switch is OFF, the inductor releases that stored energy to the load.

This process ensures:

i)The power delivered is smooth, not jerky

ii)Voltage remains stable

iii)Current does not change suddenly

So inductance is responsible for steady and continuous power delivery.

# Why Inductance is Important Here
Without inductance, the output would fluctuate wildly, and the SMPS would not be able to maintain a steady voltage.

# 3. Solenoid:

# Explanation

A solenoid is a long coil of wire wound in a cylindrical shape.When current flows through it, a strong and nearly uniform magnetic field is produced inside the coil.

<img width="127" height="194" alt="Screenshot 2025-11-10 113746" src="https://github.com/user-attachments/assets/39d1792e-5bcb-4924-b4bc-a4bd669e9c77" />


<img width="653" height="316" alt="image" src="https://github.com/user-attachments/assets/45cf0d19-ee47-43e6-84d5-17e2f9e5fc6f" />

# Real time appliction in SMPS

<img width="420" height="180" alt="image" src="https://github.com/user-attachments/assets/4be3d270-0f24-49db-b32b-ee067428a4cf" />


The solenoid in an SMPS is used as the main power inductor. It is a cylindrical coil designed to provide the required inductance for boosting or dropping the voltage. The solenoid coil stores energy during switching and handles high current flow. Its simple shape makes it easy to design for the needed number of turns and core type. This solenoid inductor plays a key role in controlling the output voltage of the SMPS.

# How the Solenoid Coil Delivers Power

The solenoid coil is the main inductor in the SMPS.It takes the pulsed energy from the switch and stores it in its magnetic field.

This process ensures:

i)When current flows through the solenoid, magnetic energy is stored.

ii)When the switch turns OFF, this stored energy is released.

ii)The output capacitor collects and smooths this energy.

iii)The load receives clean and regulated DC power.

The solenoid coil therefore controls how much energy is stored and how much is delivered, helping to raise or lower the voltage depending on the SMPS type (buck or boost).

# Why Solenoid Type is Used

The cylindrical “solenoid” shape is easy to wind and allows control over number of turns, wire thickness, core material. This makes it ideal for power inductors.

# 4. Toroid:

# Explanation

A toroid is a coil wound around a circular ring-shaped core.The magnetic field is confined entirely within the ring, which reduces electromagnetic interference (EMI).

<img width="129" height="167" alt="Screenshot 2025-11-10 113754" src="https://github.com/user-attachments/assets/5eaccbb5-2c54-4d00-8b2e-515fcb02d3f8" />

<img width="660" height="325" alt="Screenshot 2025-11-09 214719" src="https://github.com/user-attachments/assets/11dc81ce-7c2d-4f32-b160-62a358e389e3" />

#  Real time appliction in SMPS

<img width="500" height="375" alt="image" src="https://github.com/user-attachments/assets/5673f04a-4af0-4d67-a13d-893394372949" />

The toroidal inductor in an SMPS is mainly used for filtering and reducing noise. Its ring-shaped core keeps the magnetic field completely inside the core, which reduces electromagnetic interference (EMI). This helps produce clean and smooth DC output. The toroid is very efficient and compact, making it ideal for noise filters and output chokes in SMPS circuits.

# How the Toroid Helps in Power Delivery

The toroid does not store large amounts of energy like the solenoid.Instead, it helps in cleaning and improving power quality.

This process ensures:

i)When current flows through the toroid coil, the magnetic field remains inside the ring.

ii)This closed magnetic path filters out unwanted high-frequency noise.

iii)It blocks interference and removes ripple from the output.

iv)The result is clean, stable, and smooth DC power to the load.

So, the toroid helps in noise-free and interference-free power delivery.

# Why Toroid is Used

Toroidal inductors have a closed magnetic path,so no magnetic leakage, very low noise, small size but high inductance. This makes them perfect for filtering applications.

# Conclusion:

In an SMPS, inductance, solenoid coils, and toroidal inductors work together to ensure efficient and stable power delivery. Inductance provides the basic principle that allows energy to be stored and released smoothly during high-speed switching. The solenoid coil acts as the main power inductor, controlling the energy flow required for voltage conversion. The toroid, with its closed magnetic path, filters out noise and minimizes electromagnetic interference, ensuring clean and steady output power. Together, these components make the SMPS compact, efficient, and reliable, allowing modern electronic devices to operate safely and effectively.

















