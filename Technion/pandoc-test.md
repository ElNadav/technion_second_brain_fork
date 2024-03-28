---
aliases:
---

# כותרת 1

לורם איפסום דולור סיט אמט, קונסקטורר אדיפיסינג אלית נולום ארווס סאפיאן - פוסיליס קוויס, אקווזמן לורם איפסום דולור סיט אמט, קונדימנטום קורוס בליקרה, נונסטי קלובר בריקנה סטום, לפריקך תצטריק לרטי.

לורם איפסום דולור סיט אמט, קונסקטורר אדיפיסינג אלית נולום ארווס סאפיאן - פוסיליס קוויס, אקווזמן לורם איפסום דולור סיט אמט, קונדימנטום קורוס בליקרה, נונסטי קלובר בריקנה סטום, לפריקך תצטריק לרטי.
לורם איפסום דולור סיט אמט, קונסקטורר אדיפיסינג אלית נולום ארווס סאפיאן - פוסיליס קוויס, אקווזמן לורם איפסום דולור סיט אמט, קונדימנטום קורוס בליקרה, נונסטי קלובר בריקנה סטום, לפריקך תצטריק לרטי.

## תת כותרת 2

רשימה ממוספרת:

1. לורם איפסום דולור סיט אמט, קונסקטורר אדיפיסינג אלית נולום ארווס סאפיאן - פוסיליס קוויס,
2. אקווזמן לורם איפסום דולור סיט אמט, קונדימנטום קורוס בליקרה, נונסטי קלובר בריקנה סטום,
3. לפריקך תצטריק לרטי.

רשימת נקודות:
- לורם איפסום דולור סיט אמט, קונסקטורר אדיפיסינג אלית נולום ארווס סאפיאן - פוסיליס קוויס,
- אקווזמן לורם איפסום דולור סיט אמט, קונדימנטום קורוס בליקרה, נונסטי קלובר בריקנה סטום,
- לפריקך תצטריק לרטי.

# בלוק קוד

פייתון:

```python {.breaklines}
import numpy as np
import sympy as sp
import matplotlib.pyplot as plt

def composite_trapezoidal(f, a, b, n):
    h = (b - a) / n
    s = f(a) + f(b)
    for i in range(1, n):
        s += 2 * f(a + i * h)
    return s * h / 2

def composite_simpsons(f, a, b, n):
    h = (b - a) / n
    s = f(a) + f(b)
    for i in range(1, n):
        if i % 2 == 0:
            s += 2 * f(a + i * h)
        else:
            s += 4 * f(a + i * h)
    return s * h / 3

def richardson_extrapolation_simp(f, a, b, n):
    I1 = composite_simpsons(f, a, b, n)
    I2 = composite_simpsons(f, a, b, 2*n)
    return (16*I2 - I1) / 15

f = lambda x: (x+1)/(4*x+3)
a = 0
b = 6
```

מה לגבי `code` בתוך שורה?

# מתמטיקה

סתם `gathered`:

$$\begin{gathered}
0=-w+{h}_{1}-{h}_{2} \\
w={h}_{1}-{h}_{2}
\end{gathered}$$

סתם טבלה (`array`):
$$\begin{array}{c|c|c|c|c}
\text{state} & p[\pu{kPa}] & T[^{\circ}\pu{C}] &  h[\pu{kJ/kg}]  & s[\pu{kJ/kg*K}] \\
\hline 1  & 800 & 500  & 3480.6 & 7.8673 \\ 
\hline 2 & 200 & 309.74 &  3091.75  & 7.9245
\end{array}$$

# קולאאוס (Callout)


>[!notes] הערה: 
 >לורם איפסום דולור סיט אמט, קונסקטורר אדיפיסינג אלית נולום ארווס סאפיאן - פוסיליס קוויס, אקווזמן לורם איפסום דולור סיט אמט, קונדימנטום קורוס בליקרה, נונסטי קלובר בריקנה סטום, לפריקך תצטריק לרטי.


 כחלק מפסקה:
 >[!notes] הערה: 
 >לורם איפסום דולור סיט אמט, קונסקטורר אדיפיסינג אלית נולום ארווס סאפיאן - פוסיליס קוויס, אקווזמן לורם איפסום דולור סיט אמט, קונדימנטום קורוס בליקרה, נונסטי קלובר בריקנה סטום, לפריקך תצטריק לרטי.
 
 כחלק ממספור:
 
 1. בלה בלה בלה
	  >[!notes] הערה: 
 >לורם איפסום דולור סיט אמט, קונסקטורר אדיפיסינג אלית נולום ארווס סאפיאן - פוסיליס קוויס, אקווזמן לורם איפסום דולור סיט אמט, קונדימנטום קורוס בליקרה, נונסטי קלובר בריקנה סטום, לפריקך תצטריק לרטי.
 

קולאאוס מסוג אחר:

>[!theorem] משפט: 
 >לורם איפסום דולור סיט אמט, קונסקטורר אדיפיסינג אלית נולום ארווס סאפיאן - פוסיליס קוויס, אקווזמן לורם איפסום דולור סיט אמט, קונדימנטום קורוס בליקרה, נונסטי קלובר בריקנה סטום, לפריקך תצטריק לרטי.
 
# תמונה

תמונה:

![[NUM1/NUM1_011/Screenshot_20240322_182502_OneDrive.jpg|book]]

תמונה כחלק מפסקה (`inline`):
![[THE1/THE1_005/Pasted image 20240223092520.png|book]]

תמונה עם caption:

![[GCH1/GCH1_004/Screenshot_20230127_102808_Microsoft 365 (Office).jpg|book]]
>וואו זה מאוד מעניין.

תמונת `svg`:

![[THE1/THE1_HW008/THE1_HW008 תרגיל בית 8 2024-03-24 00.41.23.excalidraw.svg]]

תמונת `svg` עם caption:

![[THE1/THE1_HW008/THE1_HW008 תרגיל בית 8 2024-03-24 14.23.59.excalidraw.svg]]
>וואו זה מאוד מעניין.

תמונה בתוך קולאאוט:
>[!notes] הערה: 
 >וואו קבלו קטע:
 >![[IMT1/IMT1_005/Pasted image 20230514202911.png|book]]
 
תמונה בתוך קולאאוט עם caption:
>[!notes] הערה: 
 >וואו קבלו קטע:
 >![[DEQ1/DEQ1_001/Screenshot_20230426_235017_Chrome.jpg|book]]
 >>וואו איזה מעניין