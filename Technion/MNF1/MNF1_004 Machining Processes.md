---
aliases:
  - machining processes
  - turning
  - milling
  - straight turning
  - facing
---
# Introduction
Machining processes are a critical component of manufacturing, used to shape and finish materials into precise and functional components. These processes involve removing material from a workpiece using various cutting tools and techniques to achieve desired dimensions, tolerances, and surface finishes. Machining is fundamental to the production of parts for a wide range of industries, including automotive, aerospace, electronics, and medical devices.

| **Machining Process** | **Description**                                                                                                                       | Notes           |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------- | --------------- |
| **[[#Turning]]**      | Performed on a lathe, turning involves rotating the workpiece against a single-point cutting tool to produce cylindrical shapes.      |                 |
| **[[#Milling]]**      | In milling, a rotating multi-point cutting tool moves against the workpiece to remove material and create flat or contoured surfaces. |                 |
| **Drilling**          | Drilling creates round holes in a workpiece using a rotating drill bit.                                                               | Not in syllabus |
| **Grinding**          | Grinding uses an abrasive wheel to remove small amounts of material and achieve high surface finish and precision.                    | Not in syllabus |
| **Broaching**         | Broaching involves pushing or pulling a multi-tooth cutting tool (broach) through a workpiece to remove material in a single pass.    | Not in syllabus |
| **Sawing**            | Sawing cuts material into smaller pieces using a saw blade with teeth.                                                                | Not in syllabus |
# Turning

![](https://www.youtube.com/watch?v=-J3wN1ruDZM)

Turning is a fundamental machining process used in manufacturing to create cylindrical parts by removing material from a rotating workpiece using a cutting tool. This process is one of the most widely used and versatile methods in the manufacturing industry due to its ability to produce precise and intricate shapes with excellent surface finishes. Turning is typically performed on a lathe, which holds and rotates the workpiece against a single-point cutting tool that shapes the material.

## Key Parameters and Equations

>Examples of machining operations that can be performed on a lathe and similar machine tools.

![[MNF1_004/Pasted image 20240627203834.png|book]]
>(a) Schematic illustration of a turning operation, showing depth of cut, $d$, and feed, $f$. Cutting speed is the surface speed of the workpiece at the tool tip. (b) Forces acting on a cutting tool in turning. $F_{c}$ is the cutting force; $F_{t}$ is the thrust or feed force (in the direction of feed); and $F_{r}$ is the radial force that tends to push the tool away from the workpiece being machined.

- **Cutting Speed $V_{c}$** is the speed at which the *outer surface* of the workpiece moves past the cutting tool, measured in meters per minute (m/min). It can be calculated as
	$$\boxed {
V_{c}=\pi DN
 }$$
	where $D$ is the diameter of the workpiece and $N$ is the rotational speed.

- **Feed Rate $f$** is the distance that the cutting tool advances into the workpiece with each *revolution*, measured in millimeters per revolution $(\pu{mm.rev^{-1}})$.

- **Depth of Cut $d$** is the thickness of the material removed in one pass of the cutting tool, measured in millimeters $(\pu{mm})$.
- **Cutting Time $t$** is the time it takes to cut an $L$ long workpiece. It is given by
	$$\boxed {
t=\dfrac{L}{fN}
 }$$

>[!example] Example: 
For a workpiece with a diameter of $0.1$ meters rotating at $\pu{600rpm}$:
$$V_{c}=\pi \cdot 0.1 \cdot 600 \approx  \pu{188.4m.min^{-1}}$$

## Material Removal Rate

**Material Removal Rate ($MR R$)** quantifies the volume of material removed from a workpiece per unit time. A higher MRR indicates a more efficient process, but it must be balanced with considerations of tool wear, surface finish, and accuracy.
$$\begin{gathered}
\boxed {
MRR=fdV_{C}=\pi fdDN 
 }\\[1ex]
[M R R]=\pu{mm^{3}.min^{-1}}
\end{gathered}$$


## Cutting Force

The **cutting force $F_c$** is the force exerted by the cutting tool on the workpiece during a machining operation. It is calculated using the formula
$$\boxed {
F_{c}=K_{s}fd
 }$$
where $K_s$ is the **specific cutting force** or **specific energy**, measured in $\pu{N.mm^{-2}}$;$f$ is the feed rate; $d$ is the depth of cut;

## Power 

The power $P$ required for the cutting process is calculated using the formula
$$\boxed {
P=F_{c} V_{c}
 }$$
where $F_c$ is the cutting force; $V_{c}$ is the cutting speed;

## Straight Turning and Facing
**Straight turning** is a machining process performed on a lathe where a single-point cutting tool moves *parallel* to the axis of a rotating cylindrical workpiece. The primary purpose of straight turning is to reduce the diameter of the workpiece to achieve a desired dimension and surface finish.

![[MNF1_004/Pasted image 20240627203436.png|book]]

**Facing** is a machining process also performed on a lathe, where the cutting tool moves *perpendicular* to the axis of a rotating cylindrical workpiece. The goal of facing is to produce a flat surface at the end of the workpiece.
![[MNF1_004/Pasted image 20240627203443.png|book]]

# Milling
Milling is a machining process that involves the use of rotary cutters to remove material from a workpiece. The milling process can create a variety of features including flat surfaces, slots, and complex contours. The workpiece is usually held stationary while the cutting tool rotates and moves across the material to achieve the desired shape.

Types of milling operations:
1. **Face Milling**: Produces flat surfaces by cutting with the end of the milling cutter.
2. **Peripheral Milling/Slab Milling**: Involves cutting along the periphery of the cutter, used for creating deep slots, threads, and gear teeth.
3. **End Milling**: Utilizes an end mill cutter to produce complex shapes, slots, and holes.

## Key Parameters and Equations

![[MNF1_004/Pasted image 20240703124529.png|book]]
>(a) Illustration showing the difference between conventional milling and climb milling. (b) Slab-milling operation, showing depth of cut, $d$; feed per tooth, $f$; chip depth of cut, $t_{c}$ and workpiece speed, $v$. (c) Schematic illustration of cutter travel distance, $l_{c}$, to reach full depth of cut.

- **Cutting Speed $V_{c}$** is calculated in the same way as [[#Turning#Key Parameters and Equations|turning]]:
	$$
V_{c}=\pi DN
 $$
	where $D$ is the diameter of the workpiece and $N$ is the rotational speed.

- **Feed Rate $f$**: The feed rate is the distance the tool advances during one revolution of the spindle. As opposed to turning, we like to analyze the cutting process *per teeth* - so we define $f_{t}$ - **feed per tooth**. Therefore:
	$$\boxed{f=N f_{t} n }$$
	where $N$ is the spindle speed ($\pu{rev.min^{-1}}$); $f_{t}$ is feed per tooth $(\pu{mm.tooth}^{-1})$; and $n$ is number of teeth on the cutter.

- **Depth of Cut $d$** is the thickness of the material removed in one pass of the cutting tool, measured in millimeters $(\pu{mm})$.

Note that the thickness of the chip in slab milling varies along its length, because of the relative longitudinal movement between the cutter and the workpiece.

- **Chip Thickness $h$** (in the book, this is denoted with $t_{c}$) is the thickness of the material cut by a single tooth of the milling cutter. It can be influenced by several factors, including the feed per tooth $f_{t}$, the radial depth of cut, and the entry angle of the tooth into the material $\theta$.
	$$h=f_{t}\cos\theta$$

>[!TODO] להשלים



# Exercises
## Question 1
A $\pu{121mm}$ long, round, hollow workpiece is going under a facing operation to straighten its face. To do this, only a $\pu{1mm}$ depth of cut is needed, which reduces it to a length of $\pu{120mm}$. The feed rate is $\pu{0.7mm.rev^{-1}}$, and the possible rotational speeds of the machine are:
$$N=100,\, 350,\, 450,\, 600,\, 800,\, 950,\, 1100,\, 1300,\, \pu {1500 rpm }$$
![[MNF1_004/Pasted image 20240628153921.png|book]]
>Schematic of the workpiece after the desired facing cut

In addition, the outer diameter is $D_{o}=\pu{60mm}$, while the inner one is $D_{i}=\pu{30mm}$.
### Part a
Given two cutting tools, $A$ and $B$, with the given optimal cutting speed:
$$\begin{aligned}
V_{A}=220\pm \pu{70m.min^{-1}} &  & V_{B}=85\pm \pu{35m*min^{-1}}
\end{aligned}$$
Which cutting tool should be used to make the desired cut?

**Solution**:
First, we will try to guess which rotational speed $N$ we need to choose for each tool. We know that
$$V_{c}=\pi DN$$
but, $D$ isn't constant along the cutting process! Therefore we will choose to use the average diameter, $D_{\text{avg}}=\pu{45mm}$ (again, just to approximate $N$).

- For cutting tool $A$:
	The optimal rotational speed is approximately:
	$$N=\dfrac{V_{A}}{\pi D_{\text{avg}}}\approx \pu{1500rpm}$$
	Now, if we actually try to use the $N=\pu{1500rpm}$ rotational speed, by substituting the maximum and minimum of $D$, we get:
	$$V_{A}=\pi D_{}N=282.74,\, 141.37\,\pu{m.min^{-1}}$$
	Which is outside the optimal bounds for $A$.
- For cutting tool $B$:
	The optimal rotational speed is approximately:
	$$N=\dfrac{V_{B}}{\pi D_{\text{avg}}}\approx \pu{600rpm}$$
	Now, if we actually try to use the $N=\pu{600rpm}$ rotational speed, by substituting the maximum and minimum of $D$, we get:
	$$V_{B}=\pi D_{}N=113.1,\, 56.55\,\pu{m.min^{-1}}$$
	Which is within the optimal bounds for $B$.

Therefore, we can conclude that cutting tool $B$ is the correct choice.

### Part b
How long will the cutting operation be, using the cutting tool we chose?

**Solution**:
For cutting tool $B$, $N=\pu{600rpm}$. The length of the cut actually depends on the diameter (because its a facing operation):
$$L=\dfrac{D_{o}-D_{i}}{2}=\pu{15mm}$$
Therefore, we get:
$$\begin{gathered}
t=\dfrac{L}{fN} \\[1ex]
\boxed {
t=\pu{2.1s}
 }
\end{gathered}$$

### Parc c
Given that the machine used, outputs (in terms of cutting power) $\pu{5kW}$. Is the chosen cutting tool still viable?
Given: the material's specific cutting force is $\pu{2500 N.mm^{-2}}$.

**Solution**:
We know that the maximum cutting speed for cutting tool $B$ is $V_{b,\max_{}}=\pu{113.1m.\min_{}^{-1} }$. Therefore, the maximum cutting force is given by:
$$F_{c,\max_{}}= K_{s}fd=\pu{1750 N}$$
And the maximum power:
$$\begin{gathered}
P_{\max_{}}=F_{c,\max_{}} V_{c,\max_{}}=\pu{197925N.m.min^{-1}} \\[1ex]
P_{\max_{}}=\pu{3298.75W}<\pu{5kW}
\end{gathered}$$
Therefore, cutting tool $B$ is still viable.
