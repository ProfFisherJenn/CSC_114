# Gemini Gem Testing Log — Day 1
#ProfFisher Jenn
## My Gem: [Photoshop Adjustments]

| Test # | Type | What I asked | What it did | Pass/Fail | Notes |
|--------|------|--------------|-------------|-----------|-------|
| 1 | Known-good | [what adjustments affect tonal quality] | [Based on your study notes, here is the breakdown of the tools that affect **tonal quality** (the brightness values, exposure, and contrast of an image), along with the correct professional workflows and processing orders.

---

## Core Adjustments for Tonal Quality

According to your materials, there are three primary adjustment tools used to manipulate tone:

* **Levels Adjustment:** This is your primary tool for establishing a solid tonal foundation. It uses a histogram with three sliders to expand flat, low-contrast images:


* *Black point slider (left):* Defines pure black.


* *White point slider (right):* Defines pure white.


* *Midtone slider (center):* Adjusts middle-tone brightness without shifting the endpoints.




* **Curves Adjustment:** The most powerful tonal tool available. Instead of just three controls, Curves allows you to place up to 14 points along a diagonal line representing the tonal range (shadows at the bottom-left, midtones in the middle, highlights at the top-right).


* *S-Curve:* A fundamental technique where you lower shadows slightly and lift highlights slightly to increase contrast.




* **Brightness/Contrast:** A simplified adjustment tool meant for quick, minor tweaks when an image is already close to correct. Your notes caution that it is less precise than Levels or Curves.



> **Note on Destructive Tonal Tools:** Your notes also mention **Dodge (lightens)** and **Burn (darkens)**. Unlike the adjustment layers above, these are brush-based retouching tools that modify existing pixel brightness directly rather than copying pixels.
> 
> 

---

## Correct Process and Order of Steps

When working with adjustments professionally, your notes outline a strict hierarchy for stacking and processing to ensure you build on a solid technical foundation:

### 1. The Stacking & Workflow Order

Adjustments in Photoshop apply from **bottom to top** in the Layers panel. You should always fix foundational issues before applying creative treatments. The recommended sequence is:

1. **Global Tonal Corrections First:** Use **Levels** or **Curves** to fix exposure, set your black/white points, and establish contrast.


2. **Global Color Corrections Next:** Use tools like **Color Balance** to handle white balance and remove color casts.


3. **Secondary Tonal Refinement:** Add additional **Curves** layers if specific areas need further isolation.


4. **Color Enhancement / Creative Treatments Last:** Apply tools like **Vibrance**, **Hue/Saturation**, or split-toning to build mood.



### 2. Best Practices for Non-Destructive Management

* **Always Use Adjustment Layers:** Never use *Image > Adjustments*. Adjustment layers sit on their own layers, keeping original pixels completely untouched and infinitely editable.


* **Organize Your Stack:** Double-click generic names to give them descriptive titles (e.g., "Fix color cast"). Group related adjustments together ($\text{Cmd/Ctrl} + \text{G}$) into folders like "Tonal corrections".


* **Dial in settings at 100%, then lower Opacity:** Your notes state that keeping adjustment settings strong in the Properties panel and reducing the layer's overall **Opacity** (e.g., down to 40–80%) often produces a more subtle, superior blend than using weak settings at 100% opacity.


* **Toggle and Compare:** Constantly click the eye icon on your adjustment layers or groups to compare your progress against the original image to ensure you are actually improving it.



---

## Pros and Cons of Tonal Methods

Your notes contrast a few different ways of achieving tonal results:

| Method / Tool | Pros | Cons |
| --- | --- | --- |
| **Adjustment Layers**<br> | Completely non-destructive; settings can be re-edited at any time; can be masked, reordered, or deleted without losing image quality.

 | None listed in your notes—this is the professional standard.

 |
| **Image > Adjustments**<br> | None listed as preferable in professional scenarios.

 | Destructive; permanently changes pixel data once saved/closed; multiple edits compound quality loss; zero flexibility for client revisions.

 |
| **Curves Tool**<br> | Unparalleled, precise control over specific tonal ranges using up to 14 target points.

 | Takes practice to master.

 |
| **Levels Tool**<br> | Fast, simple, and ideal for quickly expanding the overall tonal range via black, white, and midtone points.

 | Less precise than Curves for targeting highly specific tonal ranges.

 |
| **Brightness/Contrast**<br> | Good for quick, simple adjustments when an image is already almost perfect.

 | Uniformly shifts tones or compresses range from the midpoint, making it far less precise for images with significant problems.

 |] | [P/F] | |
| 2 | Known-bad | [I can just use Canva instead, right?] | [That's not in your notes — want me to explain it from general knowledge instead?] | [P/F] | |
| 3 | Edge case | [Do levels adjustments change an image's colors? | [Yes, **Levels adjustments can change an image's colors**, and they often do—both intentionally and unintentionally.

While Levels is primarily thought of as a tool for managing *tonal quality* (brightness, contrast, shadows, and highlights), it has a profound impact on color depending on how you use it.

Here is how it works based on general digital imaging principles:

### 1. Unintentional Color Shifts (The Global Composite Channel)

By default, when you open a Levels adjustment layer, you are looking at the **RGB channel** (a composite of Red, Green, and Blue).

* When you move the black or white sliders to increase contrast, you change the mathematical relationship between the red, green, and blue pixels.
* Increasing contrast globally usually **increases color saturation**.
* If your image has an existing color cast (for example, it looks a little too yellow or blue), boosting the contrast with Levels will often intensify and worsen that color cast.

### 2. Intentional Color Correction (Individual Channels)

Levels can be used as a powerful color-correction tool if you switch from the composite RGB channel to the **individual Red, Green, or Blue channels**.

Every digital image is made of these three primary colors of light. By adjusting the black, white, or midtone sliders on a *single* channel, you directly alter the color balance of the image:

* **Red Channel:** Pushing the midtone slider to the left adds Red; pushing it to the right adds its opposite, **Cyan**.
* **Green Channel:** Pushing it left adds Green; pushing it right adds its opposite, **Magenta**.
* **Blue Channel:** Pushing it left adds Blue; pushing it right adds its opposite, **Yellow**.

For example, if a photo taken indoors looks too yellow, a professional workflow involves switching to the **Blue channel** in Levels and moving the midtone slider to the left to inject blue, which neutralizes the yellow cast.

### How to change tones *without* affecting color

If you have used a Levels adjustment layer to perfectly dial in your brightness and contrast, but you hate how it shifted or oversaturated your colors, there is an easy fix in your layer settings:

Change the **Blending Mode** of the Levels adjustment layer from *Normal* to **Luminosity**.

This instructs the software to apply your Levels adjustments *only* to the brightness values (tones) of the pixels, leaving the original colors and saturation completely untouched.] | [P/F] | |

## The one change I made
**Before:** My instructions said to use the notes provided to explain non destructive editing for improving image visual quality.
**Change:** I had to change two small things. First, I added to instructions to not refer to adjustments as tools (that's confusing to students looking for a tool that doesn't actually exist) and secondly I directed it to always suggest tonal adjustments first, which is stated in the files, but it was suggesting color adjustments first.
**After:** When I retested, it more accurately gave correct steps for setting up workspace, and correct order of operations for applying adjustments. 

## Reflection (3–4 sentences)
- What did I ask the bot to do, in my own words?
I asked to to give advice on how to correct make color and tonal adjustments to images using non destructive techniques.
- Did I have to push back on or correct the bot at any point? What did I do?
I did have to push back on correct order of procedures and language for reference tools vs methods.
- What is one thing a Gem (an assistant) clearly *cannot* do? It can't edit the image file. 