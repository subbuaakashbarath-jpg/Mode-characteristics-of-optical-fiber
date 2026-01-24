# Mode-characteristics-of-optical-fiber
# AIM
To study the mode characteristics of fiber optic cable and observe the lower order Linearly Polarized (LP) modes.

---

# Equipments Required
1. LASER Source (633 nm – 1mW)  
2. Source to Fiber Coupler  
3. Single Mode Fiber  
4. Fiber Holding Stand  
5. Opaque Screen  

---

# Theory
The central spot carries 95% of the intensity for laser beams with Gaussian profile.  

\[
I = I_0 e^{-2(r / w)^2}
\]

where \(e = 2.718\) is the base of the natural logarithm.  

- An accepted definition of a radius of a Gaussian beam is at 0.135 times its peak value \(I_0\).  
- This radius is called **spot size**. The spot diameter is \(w\).  

**Spot Diameter (d) micron** = Focal length of the Lens (f) mm × Laser beam full divergence angle (DA) mrad.  

To achieve maximum coupling efficiency, the fiber core diameter must be larger than the spot diameter.  

\[
NA = \frac{\text{Laser Beam Diameter (B.D.)}}{2 \times \text{Lens Focal Length (f)}}
\]

The source coupler consists of two base plates:  
- One base plate contains a focusing lens and a female connector receptacle.  
- The other base plate attaches to the laser.  
- An O-ring is sandwiched between the plates, with threaded screws interconnecting them.  
- A screwdriver can adjust angular orientation by turning the screws.  

**Modes and V-number:**  
- The number of modes propagating through the fiber depends on the **V-number**.  
- If \(V < 2.045\), only a single mode propagates (HE11 or LP01 mode).  
- If \(V > 2.045\), multiple modes propagate.  
- For \(V = 4.91\), four Linearly Polarized modes propagate through the fiber.  

---

# Procedure
1. Place the optical breadboard on a flat table surface.  
2. Fix the cylindrical head of the He-Ne laser source onto the breadboard securely.  
3. Mount the laser to the fiber coupler with its base plate oriented toward the laser exit.  
4. Switch on the He-Ne laser and align the beam spot centrally on the coupling lens assembly. Tighten screws.  
5. Check for back reflection from the rod lens of the coupler. Adjust screws until the reflected spot aligns with the laser exit.  
6. Confirm central alignment using a white card sheet. Adjust screws if the spot is off-center.  
7. Connect the multimode optical patch cord to the coupler and secure the other end in the fiber holding stand.  
8. Observe the bright laser spot exiting the fiber. Adjust fiber tip height to ~50 mm above the paper sheet.  
9. View the multimode speckle pattern on the screen. Adjust screws to refine the pattern. Replace with single mode fiber.  
10. For single mode fiber, observe blur patterns with lobes (two, three, or four) by fine-tuning the coupler screws.  

---
<img width="618" height="722" alt="image" src="https://github.com/user-attachments/assets/b611cde3-a1f1-4bf4-ac7a-9de89f4b6f53" />

# Tabulation and Calculation

<img width="960" height="1280" alt="image" src="https://github.com/user-attachments/assets/c2fea947-5fe8-4a6a-8a2d-9bd1cddf3710" />

<img width="1280" height="1204" alt="image" src="https://github.com/user-attachments/assets/81989834-888f-43f0-a4e8-5e79cf4f4c74" />


# Observation 
Parameters of given fiber:  
- Core radius \(A = 4.5 \, \mu m\)  
- Numerical Aperture \(NA = 0.11\)  
- Wavelength \(\lambda = 633 \, nm\)  

\[
V = \frac{2 \pi \cdot A \cdot NA}{\lambda} = 4.91
\]

- From the figure, only **4 LP modes** propagate.  
- Total number of modes:  

\[
\frac{V^2}{2} = \frac{(4.91)^2}{2} \approx 12.05
\]

---

# Result
The fiber supports **4 Linearly Polarized (LP) modes** at the given parameters.
