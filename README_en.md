# README 
(Layering Inputs with UltimateShift × Razer Synapse 2 × Pad)

This README explains how to use <strong>UltimateShift</strong>  
not by adding more buttons, but by <strong>switching worlds (layers)</strong>.  
This is <strong>not an official recommendation</strong> — it is a <strong>personal workflow</strong>.

---

## TL;DR (This is all you need)

### HYPER
- Mouse button <strong>5</strong>

### ULTRA
- Pad button <strong>L1</strong>

### ULTIMATE
- Hold <strong>Mouse5 + L1</strong>

So the logic is:

- <strong>NORMAL</strong> → default state  
- <strong>HYPER</strong> → while holding Mouse5  
- <strong>ULTRA</strong> → while holding L1  
- <strong>ULTIMATE</strong> → while holding both  

---

## Screenshot order (usc_img/001–011)

Screenshots are arranged as follows:

<code>usc_img/001.png → usc_img/002.png → ... → usc_img/011.png</code>

This README follows the <strong>exact same order</strong>.

---

## 1. Create F1 → F13 in NORMAL (temporary helper)

### Purpose

We want to bind <strong>F13</strong> in Synapse,  
but pressing F13 directly is inconvenient.

So we temporarily create a state where:

### <strong>F1 outputs F13</strong>

- In <strong>NORMAL</strong>, set <strong>F1 → F13</strong>
- Red frame means <strong>editing (not saved yet)</strong>
- Even if not saved, <strong>the change is already active</strong>

![](usc_img/001.png)

---

## 2. Bind Mouse button 5 → F13 in Razer Synapse 2

Open <strong>Razer Synapse 2</strong> and:

- Assign mouse button <strong>5</strong> to <strong>F13</strong>
- Select <strong>Keyboard Function</strong>
- Even if the bind field looks empty, press <strong>F1</strong>  
  → because of step 1, this inputs <strong>F13</strong>
- Save it as a <strong>single key</strong>

![](usc_img/002.png)  
![](usc_img/003.png)

---

## 3. Confirmation: Mouse button 5 outputs F13

At this point:

### <strong>Mouse button 5 → F13</strong>

UI details may differ.  
What matters is that <strong>button 5 sends F13</strong>.

![](usc_img/004.png)  
![](usc_img/005.png)

---

## 4. Configure HYPER (Trigger = F13 / Layer = F14)

Now create the <strong>HYPER world</strong> in UltimateShift.

### Settings

- <strong>HYPER = F14</strong>
- <strong>Trigger = F13</strong>

### Result

Pressing <strong>Mouse5</strong> instantly puts you in the  
<strong>HYPER layer</strong>.

Add bindings freely. Rename tabs if needed.

![](usc_img/006.png)  
![](usc_img/008.png)

---

## 5. Configure ULTRA (Pad L1 = ULTRA)

Now build <strong>ULTRA</strong> on the pad side.

### Settings

- <strong>Pad L1 = ULTRA</strong>
- (Optional) rename pad buttons for clarity
- Operate ULTRA as <strong>ULTRA = F15</strong> (or any unused key)

![](usc_img/009.png)  
![](usc_img/010.png)

---

## 6. ULTIMATE = highest layer (HYPER + ULTRA)

### Hold both

- <strong>Mouse5 (HYPER)</strong>
- <strong>L1 (ULTRA)</strong>

### Result

You are now in the <strong>ULTIMATE world</strong>.

Using <strong>L1 / R1</strong> as layer switches dramatically increases  
the number of usable actions.

![](usc_img/011.png)

---

## 7. Finish: assign actions per world

Now simply assign meanings per layer:

- <strong>NORMAL</strong> → default actions  
- <strong>HYPER</strong> → actions while holding Mouse5  
- <strong>ULTRA</strong> → actions while holding L1  
- <strong>ULTIMATE</strong> → actions while holding both  

![](usc_img/007.png)  
![](usc_img/008.png)  
![](usc_img/010.png)  
![](usc_img/011.png)

---

## Final Summary

### <strong>Mouse5</strong> → <strong>HYPER</strong>  
### <strong>L1</strong> → <strong>ULTRA</strong>  
### <strong>Mouse5 + L1</strong> → <strong>ULTIMATE</strong>

<strong>UltimateShift is not about adding buttons.</strong>  
It is about <strong>changing the world you are operating in</strong>.
