/**-----------------------------------------------------------.
> /                       Description                           /
> '------------------------------------------------------------/
Game: Grand Theft Auto V
Author: Pizzadox
SweetFX version: 1.5.1/Boulotaur2024 Injector - http://dropcanvas.com/iz7s1
Description: This is my estimated settings for GTA5**


---

---PPPPPPPPPPPPPPPPPPPPPPPPPPPPP---
---PPPPPPPPPPPPPPPPPPPPPPPPPPPPP---
---PPPPPPPPPPPPPPPPPPPPPPPPPPPPP---
---------------PPPPP-------PPPPP---
---------------PPPPP-------PPPPP---
---------------PPPPP-------PPPPP---
---------------PPPPPPPPPPPPPPPPP---
---------------PPPPPPPPPPPPPPPPP---
---------------PPPPPPPPPPPPPPPPP---

---

---PPPPPPPPPPP-PPPPP---------------
---PPPPPPPPPPP-PPPPP---------------
---PPPPPPPPPPP-PPPPP---------------

---

---PPPPPPPP----PPPPP---------------
---PPPPPPPP----PPPPP---------------
---PPPPPPPPPPP-PPPPP---------------
---PPPPP-PPPPP-PPPPP---------------
---PPPPP-PPPPPPPPPPP---------------
---PPPPP----PPPPPPPP---------------
---PPPPP----PPPPPPPP---------------

---

---PPPPPPPP----PPPPP---------------
---PPPPPPPP----PPPPP---------------
---PPPPPPPPPPP-PPPPP---------------
---PPPPP-PPPPP-PPPPP---------------
---PPPPP-PPPPPPPPPPP---------------
---PPPPP----PPPPPPPP---------------
---PPPPP----PPPPPPPP---------------

---

---PPPPPPPPPPPPPPPPP---------------
---PPPPPPPPPPPPPPPPP---------------
---PPPPPPPPPPPPPPPPP---------------
------PPPPP----PPPPP---------------
---PPPPPPPPPPPPPPPPP---------------
---PPPPPPPPPPPPPPPPP---------------
---PPPPPPPPPPPPPPPPP---------------

---

---PPPPPPPPPPPPPPPPP---------------
---PPPPPPPPPPPPPPPPP---------------
---PPPPPPPPPPPPPPPPP---------------
---PPPPP-------PPPPP---------------
---PPPPPPPPPPPPPPPPPPPPPPPPPP------
---PPPPPPPPPPPPPPPPPPPPPPPPPP------
---PPPPPPPPPPPPPPPPPPPPPPPPPP------

---

---PPPPPPPPPPPPPPPPP---------------
---PPPPPPPPPPPPPPPPP---------------
---PPPPPPPPPPPPPPPPP---------------
---PPPPP-------PPPPP---------------
---PPPPPPPPPPPPPPPPP---------------
---PPPPPPPPPPPPPPPPP---------------
---PPPPPPPPPPPPPPPPP---------------

---

---PPPPP-------PPPPP---------------
---PPPPP-------PPPPP---------------
---PPPPPPPPPPPPPPPPP---------------
---------PPPPP---------------------
---PPPPPPPPPPPPPPPPP---------------
---PPPPP-------PPPPP---------------
---PPPPP-------PPPPP---------------

---





> /**-----------------------------------------------------------.
> /                      Choose effects                         /
> '-----------------------------------------------------------**/

// Set to 1 for ON or 0 for OFF
#define USE\_SMAA\_ANTIALIASING 1 //[or 1](0.md) SMAA Anti-aliasing : Smoothens jagged lines using the SMAA technique.
#define USE\_FXAA\_ANTIALIASING 0 //[or 1](0.md) FXAA Anti-aliasing : Smoothens jagged lines using the FXAA technique
#define USE\_CA                1 //[or 1](0.md) Chromatic aberration. You can only use Chromatic Aberration OR the Explosion Shader. Not both at the same time.
#define USE\_EXPLOSION         0 //[or 1](0.md) Explosion : Scatters the pixels, making the image look fuzzy.
#define USE\_CARTOON           0 //[or 1](0.md) Cartoon : "Toon"s the image.(Interferes with SMAA, CRT, Bloom, HDR and Lumasharpen)
#define USE\_LEVELS            1 //[or 1](0.md) Levels : Sets a new black and white point. This increases contrast but causes clipping. Use Curves instead if you want to avoid that.
#define USE\_ADVANCED\_CRT      0 //[or 1](0.md) Advanced CRT : Simulates an old CRT TV display. Set gaussian blur along with it to get a halation effect
#define USE\_BLOOM             1 //[or 1](0.md) Bloom : Makes bright lights bleed their light into their surroundings (relatively high performance cost)
#define USE\_HDR               1 //[or 1](0.md) HDR : Not actual HDR - It just tries to mimic an HDR look (relatively high performance cost)
#define USE\_LUMASHARPEN       1 //[or 1](0.md) LumaSharpen : Also sharpens the antialiased edges which makes them less smooth - I'm working on fixing that.
#define USE\_GAUSSIAN          1 //[or 1](0.md) Gaussian Blur : can be used to... blur, but also bloom/hazy/glowy look, also unsharp masking
#define USE\_FILMGRAIN         0 //[or 1](0.md) Filmgrain effect
#define USE\_TECHNICOLOR       0 //[or 1](0.md) TECHNICOLOR : Attempts to mimic the look of an old movie using the Technicolor three-strip color process (Techicolor Process 4)
#define USE\_DPX               0 //[or 1](0.md) Cineon DPX : Should make the image look like it's been converted to DXP Cineon - basically it's another movie-like look similar to technicolor.
#define USE\_MONOCHROME        0 //[or 1](0.md) Monochrome : Monochrome makes the colors disappear.
#define USE\_LIFTGAMMAGAIN     1 //[or 1](0.md) Lift Gamma Gain : Adjust brightness and color of shadows, midtones and highlights (avoids clipping)
#define USE\_TONEMAP           0 //[or 1](0.md) Tonemap : Adjust gamma, exposure, saturation, bleach and defog. (may cause clipping)
#define USE\_VIBRANCE          1 //[or 1](0.md) Vibrance : Intelligently saturates (or desaturates if you use negative values) the pixels depending on their original saturation.
#define USE\_CURVES            1 //[or 1](0.md) Curves : Contrast adjustments using S-curves.
#define USE\_SEPIA             1 //[or 1](0.md) Sepia : Sepia tones the image.
#define USE\_VIGNETTE          0 //[or 1](0.md) Vignette : Darkens the edges of the image to make it look more like it was shot with a camera lens. May cause banding artifacts.
#define USE\_DITHER            1 //[or 1](0.md) Dither : Applies dithering to simulate more colors than your monitor can display. This lessens banding artifacts (mostly caused by Vignette)
#define USE\_BORDER            0 //[or 1](0.md) Border : Makes the screenedge black as a workaround for the bright edge that forcing some AA modes sometimes causes.
#define USE\_SPLITSCREEN       0 //[or 1](0.md) Splitscreen : Enables the before-and-after splitscreen comparison mode.

#define USE\_CUSTOM            0 //[or 1](0.md) Custom : Write your own shader by editing custom.h, and then enable it here.

> /**-----------------------------------------------------------.
> /                  SMAA Anti-aliasing settings                /
> '-----------------------------------------------------------**/

#define SMAA\_THRESHOLD 0.09           //[0.05 to 0.20] Edge detection threshold. If SMAA misses some edges try lowering this slightly. I prefer between 0.08 and 0.12.
#define SMAA\_MAX\_SEARCH\_STEPS 38     //[to 98](0.md) Determines the radius SMAA will search for aliased edges
#define SMAA\_MAX\_SEARCH\_STEPS\_DIAG 16  //[to 16](0.md) Determines the radius SMAA will search for diagonal aliased edges
#define SMAA\_CORNER\_ROUNDING 76       //[to 100](0.md) Determines the percent of antialiasing to apply to corners. 0 seems to affect fine text the least so it's the default.

// -- Advanced SMAA settings --
#define COLOR\_EDGE\_DETECTION 1        //[or 1](0.md) 1 Enables color edge detection (slower but slightly more acurate) - 0 uses luma edge detection (faster)
#define SMAA\_DIRECTX9\_LINEAR\_BLEND 0  //[or 1](0.md) Using DX9 HARDWARE? (software version doesn't matter) if so this needs to be 1 - If not, leave it at 0.
> //Enable this only if you use a Geforce 7xxx series or older card, or a Radeon X1xxx series or older card.


> /**-----------------------------------------------------------.
> /                  FXAA Anti-aliasing settings                /
> '-----------------------------------------------------------**/
#define FXAA\_QUALITYPRESET 39      //[to 39](1.md) Choose the quality preset. 39 is the highest quality.
#define fxaa\_Subpix 0.3            //[0.000 to 1.000] Choose the amount of sub-pixel aliasing removal.
#define fxaa\_EdgeThreshold 0.04    //[0.000 to 1.000] Edge detection threshold. The minimum amount of local contrast required to apply algorithm.
#define fxaa\_EdgeThresholdMin 0.4  //[0.000 to 1.000] Darkness threshold. Trims the algorithm from processing darks.

> /**-----------------------------------------------------------.
> /                       Chromatic aberration                  										/
> '-----------------------------------------------------------**/
#define outfocus  0.005                     //[0.00 to 1.000] How strong the effect should be.


> /**-----------------------------------------------------------.
> /                     Explosion settings                      /
> '-----------------------------------------------------------**/
#define Explosion\_Radius    1.0     //[0.2 to 100.0] Amount of effect you want.


> /**-----------------------------------------------------------.
> /                      Cartoon settings                       /
> '-----------------------------------------------------------**/
#define CartoonPower         4.0     //[0.1 to 10.0] Amount of effect you want.
#define CartoonEdgeSlope     6.0     //[0.1 to 8.0] Raise this to filter out fainter edges. You might need to increase the power to compensate. Whole numbers are faster.


> /**----------------------------------------------------------.
> /                       Levels settings                      /
> '----------------------------------------------------------**/

#define Levels\_black\_point 14.80    //[to 255](0.md) The black point is the new black - literally. Everything darker than this will become completely black. Default is 16.0
#define Levels\_white\_point 229.90   //[to 255](0.md) The new white point. Everything brighter than this becomes completely white. Default is 235.0

//Colors between the two points will stretched, which increases contrast, but details above and below the points are lost (this is called clipping).


> /**----------------------------------------------------------.
> /                    Advanced CRT settings                   /
> '----------------------------------------------------------**/
#define CRTAmount            0.95    //[0.00 to 1.00]  Amount of CRT effect you want

#define CRTResolution        1.0     //[1.0 to 8.0]    Input size coefficent (low values gives the "low-res retro look"). Default is 1.2
#define CRTgamma             2.3     //[0.0 to 4.0]    Gamma of simulated CRT (default 2.2)
#define CRTmonitorgamma      2.3     //[0.0 to 4.0]    Gamma of display monitor (typically 2.2 is correct)
#define CRTBrightness        1.1     //[1.0 to 3.0]    Used to boost brightness a little. Default is 1.0
#define CRTScanlineIntensity 2.0     //[2.0 to 4.0]    Scanlines intensity (use integer values preferably). Default is 2.0
#define CRTScanlineGaussian  1       //[or 1](0.md)        Use the "new nongaussian scanlines bloom effect". Default is on

#define CRTCurvature         1       //[[or 1](0.md)          "Barrel effect" enabled (1) or off (0)
#define CRTCurvatureRadius   2.0     //[0.0 to 2.0]       Curvature Radius (only effective when Curvature is enabled). Default is 1.5
#define CRTCornerSize        0.0100  //[0.0000 to 0.0020] Higher values, more rounded corner. Default is 0.001
#define CRTDistance          2.00    //[0.00 to 4.00]     Simulated distance from viewer to monitor. Default is 2.00
#define CRTAngleX            0.00    //[-0.20 to 0.20]    Tilt angle in radians (X coordinates)
#define CRTAngleY           -0.15   //[-0.20 to 0.20]    Tilt angle in radians (Y coordinates). (Value of -0.15 gives the 'arcade tilt' look)
#define CRTOverScan          1.00    //[1.00 to 1.10]     Overscan (e.g. 1.02 for 2% overscan). Default is 1.01
#define CRTOversample        0       //[or 1](0.md)           Enable 3x oversampling of the beam profile (warning : performance hit)


> /**-----------------------------------------------------------.
> /                  Bloom settings                             /
> '-----------------------------------------------------------**/
#define BloomThreshold 22.29 //[0.00 to 50.00] Threshold for what is a bright light (that causes bloom) and what isn't.
#define BloomPower 1.531     //[0.000 to 8.000] Strength of the bloom
#define BloomWidth 0.0110    //[0.0000 to 1.0000] Width of the bloom


> /**-----------------------------------------------------------.
> /                  HDR settings                               /
> '-----------------------------------------------------------**/
#define HDRPower 1.35  //[0.00 to 8.00] Strangely lowering this makes the image brighter
#define radius2  0.84  //[0.00 to 8.00] Raising this seems to make the effect stronger and also brighter


> /**-----------------------------------------------------------.
> /                  LumaSharpen settings                       /
> '-----------------------------------------------------------**/
// -- Sharpening --
#define sharp\_strength 0.60   //[0.10 to 3.00] Strength of the sharpening
#define sharp\_clamp    0.034  //[0.000 to 1.000] Limits maximum amount of sharpening a pixel recieves - Default is 0.035

// -- Advanced sharpening settings --
#define pattern 2        //[1|2|3|4] Choose a sample pattern. 1 = Fast, 2 = Normal, 3 = Wider, 4 = Pyramid shaped.
#define offset\_bias 1.0  //[0.0 to 6.0] Offset bias adjusts the radius of the sampling pattern.
> //I designed the pattern for offset\_bias 1.0, but feel free to experiment.

// -- Debug sharpening settings --
#define show\_sharpen 0   //[or 1](0.md) Visualize the strength of the sharpen (multiplied by 4 to see it better)


> /**-----------------------------------------------------------.
> /                  Gaussian Blur settings                     /
> '-----------------------------------------------------------**/
#define GaussEffect 2        //[0|1|2|3]        0 = Blur, 1 = Unsharpmask (expensive), 2 = Bloom, 3 = Sketchy. Default is 2
#define GaussQuality 2       //[0|1|2|3]        Warning: 2 and 3 are expensive. Default is 1
#define GaussSigma 3       //[to 4](1.md)         The higher the wider blur/bloom is (only effective when Bloom selected)
#define GaussBloomWarmth 2   //[0|1|2]          "Temperature" of the bloom - 0 = neutral, 1 = warm, 2 = hazy/foggy
#define GaussThreshold 0.50  //[0.00 to 1.00]   [DX10/11 only] Threshold for what is a bright light (that causes bloom) and what isn't.
#define GaussExposure 43.0   //[0.00 to 100.00] [DX10/11 only] Exposure of the effect (the lower the brighter)
#define GaussStrength 0.15  //[0.00 to 1.00]   Amount of effect blended into the final image


> /**-----------------------------------------------------------.
> /                  Film grain settings                        /
> '-----------------------------------------------------------**/
#define FilmGrainIntensity 0.6  //[0.00 to 1.00] Intensity of grain. Default is 0.46
#define FilmGrainExposure 20     //[to 100](0.md)     Grain Exposure. Default is 40 (Lower -> darker noise)
#define FilmGrainSize 6          //[to 10](0.md)      Size of the grain. Default is 2 (Higher -> thinner noise)


> /**-----------------------------------------------------------.
> /                  TECHNICOLOR settings                       /
> '-----------------------------------------------------------**/
#define TechniAmount 0.14         //[0.00 to 1.00]
#define TechniPower  6.0         //[0.00 to 8.00]
#define redNegativeAmount   0.88 //[0.00 to 1.00]
#define greenNegativeAmount 0.88 //[0.00 to 1.00]
#define blueNegativeAmount  0.88 //[0.00 to 1.00]


> /**-----------------------------------------------------------.
> /                  Cineon DPX settings                        /
> '-----------------------------------------------------------**/
#define Red   9.0  //[1.0 to 15.0]
#define Green 9.0  //[1.0 to 15.0]
#define Blue  9.0  //[1.0 to 15.0]

#define ColorGamma    2.4  //[0.1 to 2.5] Adjusts the colorfulness of the effect in a manner similar to Vibrance. 1.0 is neutral.
#define DPXSaturation 2.8  //[0.0 to 8.0] Adjust saturation of the effect. 1.0 is neutral.

#define RedC   0.36  //[0.60 to 0.20]
#define GreenC 0.36  //[0.60 to 0.20]
#define BlueC  0.34  //[0.60 to 0.20]

#define Blend 0.15    //[0.00 to 1.00] How strong the effect should be.


> /**-----------------------------------------------------------.
> /                  Monochrome settings                        /
> '-----------------------------------------------------------**/
#define Monochrome\_conversion\_values float3(0.18,0.41,0.41) //[0.00 to 1.00] Percentage of RGB to include (should sum up to 1.00)


> /**-----------------------------------------------------------.
> /                  Lift Gamma Gain settings                   /
> '-----------------------------------------------------------**/
#define RGB\_Lift  float3(1.050, 1.040, 1.035)  //[0.000 to 2.000] Adjust shadows for Red, Green and Blue
#define RGB\_Gamma float3(1.010, 1.025, 1.035)  //[0.000 to 2.000] Adjust midtones for Red, Green and Blue
#define RGB\_Gain  float3(0.980, 1.005, 1.005)  //[0.000 to 2.000] Adjust highlights for Red, Green and Blue

> /**-----------------------------------------------------------.
> /                  Tonemap settings                           /
> '-----------------------------------------------------------**/
#define Gamma 1.0                         //[0.000 to 2.000] Adjust midtones
#define Exposure 0.00                     //[-1.000 to 1.000] Adjust exposure
#define Saturation 0.1                   //[-1.000 to 1.000] Adjust saturation
#define Bleach 0.03                       //[0.000 to 1.000] Brightens the shadows and fades the colors
#define Defog 0.000                       //[0.000 to 1.000] How much of the color tint to remove
#define FogColor float3(0.00, 0.00, 2.55) //[0.00 to 2.55, 0.00 to 2.55, 0.00 to 2.55] What color to remove - default is blue




> /**-----------------------------------------------------------.
> /                  Vibrance settings                          /
> '-----------------------------------------------------------**/
#define Vibrance     0.50  //[-1.00 to 1.00] Intelligently saturates (or desaturates if you use negative values) the pixels depending on their original saturation.
#define Vibrance\_RGB\_balance float3(1.14, 1.15, 1.16) //[-10.00 to 10.00,-10.00 to 10.00,-10.00 to 10.00] A per channel multiplier to the Vibrance strength so you can give more boost to certain colors over others


> /**-----------------------------------------------------------.
> /                  Curves settings                            /
> '-----------------------------------------------------------**/
#define Curves\_mode     0   //[0|1|2] Choose what to apply contrast to. 0 = Luma, 1 = Chroma, 2 = both Luma and Chroma. Default is 0 (Luma)
#define Curves\_contrast 0.43 //[-1.00 to 1.00] The amount of contrast you want

// -- Advanced curve settings --
#define Curves\_formula     3 //[1|2|3|4|5|6|7|8|9|10] The contrast s-curve you want to use.
> //1 = Sine, 2 = Abs split, 3 = Smoothstep, 4 = Exp formula, 5 = Simplified Catmull-Rom (0,0,1,1), 6 = Perlins Smootherstep
> //7 = Abs add, 8 = Techicolor Cinestyle, 9 = Parabola, 10 = Half-circles.
> //Note that Technicolor Cinestyle is practically identical to Sine, but runs slower. In fact I think the difference might only be due to rounding errors.
> //I prefer 2 myself, but 3 is a nice alternative with a little more effect (but harsher on the highlight and shadows) and it's the fastest formula.


> /**-----------------------------------------------------------.
> /                  Sepia settings                             /
> '-----------------------------------------------------------**/
#define ColorTone float3(1.0, 1.0, 1.0) //[0.00 to 2.55, 0.00 to 2.55, 0.00 to 2.55] What color to tint the image
#define GreyPower  0.0                    //[0.00 to 1.00] How much desaturate the image before tinting it
#define SepiaPower 0.59                    //[0.00 to 1.00] How much to tint the image


> /**-----------------------------------------------------------.
> /                  Vignette settings                          /
> '-----------------------------------------------------------**/
#define VignetteType       1  //[1|2|3] 1 = Original, 2 = New, 3 = TV style
#define VignetteRatio   1.00  //[0.15 to 6.00]  Sets a width to height ratio. 1.00 (1/1) is perfectly round, while 1.60 (16/10) is 60 % wider than it's high.
#define VignetteRadius  1.00  //[-1.00 to 3.00] lower values = stronger radial effect from center
#define VignetteAmount -0.40  //[-2.00 to 1.00] Strength of black. -2.00 = Max Black, 1.00 = Max White.
#define VignetteSlope      6  //[to 16](2.md) How far away from the center the change should start to really grow strong (odd numbers cause a larger fps drop than even numbers)
#define VignetteCenter float2(0.500, 0.500)  //[0.000 to 1.000, 0.000 to 1.000] Center of effect for VignetteType 1. 2 and 3 do not obey this setting.


> /**-----------------------------------------------------------.
> /                  Dither settings                            /
> '-----------------------------------------------------------**/
#define dither\_method      2  //[or 2](1.md) 1 = Ordered dithering (very good and very fast), 2 = Random dithering (different but slightly slower dithering)

//Note that the patterns used by Dither, makes an image harder to compress.
//This can make your screenshots and video recordings take up more space.


> /**-----------------------------------------------------------.
> /                  Border settings                            /
> '-----------------------------------------------------------**/
#define border\_width float2(1,100)     //[to 2048, 0 to 2048](0.md) (X,Y)-width of the border. Measured in pixels.
#define border\_color float3(0, 0, 0)  //[to 255, 0 to 255, 0 to 255](0.md) What color the border should be. In integer RGB colors, meaning 0,0,0 is black and 255,255,255 is full white.

> /**-----------------------------------------------------------.
> /                  Splitscreen settings                       /
> '-----------------------------------------------------------**/
#define splitscreen\_mode   1  //[1|2|3|4|5|6]  1 = Vertical 50/50 split, 2 = Vertical 25/50/25 split, 3 = Vertical 50/50 angled split,
> > // 4 = Horizontal 50/50 split, 5 = Horizontal 25/50/25 split, 6 = Curvy vertical 50/50 split


> /**-----------------------------------------------------------.
> /                  Key settings                               /
> '-----------------------------------------------------------**/
// This is the section where you can define your own key mapping
// See the following URL to find out what keycode a key has:
// http://www.cambiaresearch.com/articles/15/javascript-char-codes-key-codes

// key\_toggle\_sweetfx = 145
// key\_screenshot     = 44
// key\_reload\_sweetfx = 19


> /**-----------------------------------------------------------.
> /                  Misc settings                              /
> '-----------------------------------------------------------**/
// You can load and chain other DirectX wrappers (ENB, Helix, Windower...)
// If the external wrapper is already named d3d9.dll, rename it into
// something else like "d3d9\_enb.dll" (note that even if this is commented it actually works)

// external\_d3d9\_wrapper = none
// external\_dxgi\_wrapper = none