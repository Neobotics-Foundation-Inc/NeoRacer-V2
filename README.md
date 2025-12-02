# NeoRacer-V2
3D-printable open-source chassis for autonomous racing in robotics education and research

---

<img width="1536" height="979" alt="grafik" src="https://github.com/user-attachments/assets/b32d2113-be08-45b6-8e23-587c1f945737" />

(Current as of December 2nd, 2025)
---

NeoRacer V2 follows these design criteria:
- 3D printable chassis: NeoRacer V2 shall be as accessible as possible, with low production costs. Hence, it should be easy to print and assemble, which allows low-cost access, maintenance, and repairs
- Compact footprint: NeoRacer V2 is dedicated to robotic research on the small scale. To allow competitions in confined spaces as well as to follow the concept of low cost and ease of use, it aims to be on the 1:12 scale of model cars
- Standardized and well available components: All non-printable parts of NeoRacer V2 shall be standard components that can be procured worldwide at low costs
- Stability: Despite the limitations of 3D printed components, NeoRacer V2 shall be as sturdy as possible, to allow operation for at least dozens of hours without failures
- Performance: NeoRacer V2 needs sufficient payload capacity for the hardware required for autonomous racing, and it needs to have enough power to reach around 25 km/h

---

Specifications*

- Footprint: 30x20x10 cm (LxWxH), without bumpers (they add 8.5 cm in length)
- Wheelbase: 23 cm
- Track width: 18 cm
- Supported wheel sizes: 70-90 mm diameter
- Ground clearance: 1-2 cm (depending on the wheel size)
- Swing axles with +-10° (rear) and +-8.5° (front) movement interval
- Suspension: Compression springs with ~15 mm diameter; length at resting height 26 mm (adjustable to accomodate different spring rates and weights; the current design allows up to 36 mm length at resting height)
- Minimum turn radius: approx. 45 cm (max. steering angle is 35°; Ackermann condition is met with an error <0.5° up to a steering angle of 32°)
- Caster angle: +10°
- Steering axis inclination: 20°
- Scrub radius: approx. +4.5 mm (will depend on the tires)
- Toe angle: Front adjustable with washers (no bump steer); rear neutral
- Camber angle: neutral at resting height; follows exactly the axle movement (swing axles)
- Rear-wheel drive with Cardan joint
- Gearbox: 3-stage herringbone gears; ratio 6.07:1
- Drivetrain supported with ball bearings; Cardan joints and differential use sleeve bearings
- Max speed: 23.3 km/h (with 75 mm tire diameter and 10k max motor rpm - that is a realistic load rpm for standard 775 brushed DC motors powered from a 3S LiPo)

*Subject to change - the chassis design is still work in progress

---

Considerations for reliable long-term operation of the drive train

- The drive train uses herringbone gears, which can be easily produced with 3D printing and allow smoother operation than spur gears. They are self-centering and have smooth transitions from tooth to tooth.
- The gears are designed with a module of 1, which is large enough for 3D printing, and the smallest gear has 15 teeth, which is comparably large, thereby allowing small forces acting per tooth.
- All gears have a height of 15 mm, again, this is comparably large, which distributes the acting forces over a large area.
- The gear pairs use teeth count combinations without common demoninator, which distributes wear as evenly as possible over all teeth of the gears.
- The gears are interconnected with TPU linkers, which act as torque dampers to reduce stress from sudden impacts due to abrupt speed changes between the input and the output of the gearbox.
- The differential uses four crown gears between the two output gears to distribute the load on as many teeth as possible
- The wheels are connected to the differential's output with Cardan joints, which uses metal pins as the actual joint
- The whole drive train is supported with bearings. The main gears use ball bearings. The differential and the Cardan joints use sleeve bearings.
