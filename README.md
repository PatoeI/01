# 01
โจทย์ Emag
y=tan(x)
## Arc Length of y = tan(x) from x = 0 to π/4

We use the arc length formula for functions:

$$\
L = \int_a^b \sqrt{1 + \left( \frac{dy}{dx} \right)^2} \, dx
\$$

For $$\ y = tan(x) = sec^2(x) \$$, we have:

$$\
\frac{dy}{dx} = \sec^2(x) \quad \Rightarrow \quad \left( \frac{dy}{dx} \right)^2 = \sec^4(x)
\$$

So the arc length is:

$$\
L = \int_0^{\frac{\pi}{4}} \sqrt{1 + \sec^4(x)} \, dx \approx 1.2779
\$$

หาประจุรวมบนเส้นโค้ง
Find the **total charge** distributed along the curve:

# ⚡ Arc Charge Density on $y = \tan(x)$

## 📌 Problem Statement

Find the **total charge** distributed along the curve:

> $y = \tan(x)$ for $0 < x < \frac{\pi}{4}$

Given that the linear charge density is:

> $\lambda(x) = x$ (in C/m)

---

## 🧮 Method: Arc-Length Integral with Variable Density

To find the total charge $Q$, we integrate the linear charge density along the arc length:


$Q = \int_{0}^{\frac{\pi}{4}} \lambda(x) \cdot ds$


Where:

- $ds = \sqrt{1 + \left(\frac{dy}{dx}\right)^2} \, dx$

Since $y = \tan(x)$, we get:

- $\frac{dy}{dx} = \sec^2(x) \Rightarrow \left(\frac{dy}{dx}\right)^2 = \sec^4(x)$

Therefore:


- $Q = \int_0^{\frac{\pi}{4}} x \cdot \sqrt{1 + \sec^4(x)} \, dx \approx 0.53872$








