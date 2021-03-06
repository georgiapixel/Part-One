# Oxygen Storage {#id}
> Describe the oxygen ~~and carbon dioxide~~ stores in the body

The standard textbook 70kg male contains **~1.5L** of oxygen, split between:
* ~850ml in blood  
  There is 20.4ml of oxygen per 100ml of blood, divided up as:
  * 20.1ml bound to haemoglobin
  * 0.3ml dissolved
* ~250ml bound to myoglobin
* ~450ml contained in FRC (21% of 2.4L)   
This is why preoxygenation increases safe apnoea times, as the nitrogen washout increases the volume of oxygen stored.

##Oxygen-Haemoglobin Dissociation Curve{#curve}
The sigmoid shape of the oxygen-haemoglobin dissociation curve offers many physiological advantages:
* Buffering in case of low PaO<sub>2</sub>  
The plateau allows oxygen **content** to remain high, even if the PaO<sub>2</sub> falls
* Maintenance of diffusion gradient to tissues  
The steep section allows a large amount of oxygen to be delivered with only a small drop in PaO<sub>2</sub>, which allows the rate of oxygen delivery to be maintained (as the blood-tissue partial pressure gradient is steep) with an increase in oxygen demand.

<img src="resources\oxyhb-curve.svg">


* The sigmoid shape exists due to **cooperative binding**  
Each oxygen which binds to Hb causes conformational changes which allow it bind additional oxygen molecules more easily.
  * When the fourth oxygen molecule has bound, Hb is said to be in the **relaxed conformation** (R state)
  * When no oxygen is bound, Hb is said to be in the **tense state** (T state)


* The curve can be right or left-shifted by changes in temperature, pH, CO<sub>2</sub>, and 2-3 DPG

<img src="resources\oxy-hb-curve-shifts.svg">


* Note that the **mixed venous point is not on the arterial curve** (unlike how it is displayed above), as the venous dissociation curve is right-shifted relative to the arterial curve

###Haemoglobin Species
Haemoglobin is a four-tetramer molecule, and its species can be physiological or pathological:
* **Physiological**
  * **HbA**  
    * Most common
    * 2 alpha and 2 beta subunits (α<sub>2</sub>β<sub>2</sub>)
  * **HbA<sub>2</sub>**
    * Less common
    * 2 alpha and 2 delta subunits (α<sub>2</sub>δ<sub>2</sub>)
  * **HbF**
    * Foetal Hb
    * Higher affinity for oxygen due to lack of 2,3-DPG
    * 2 alpha and 2 gamma subunits (α<sub>2</sub>γ<sub>2</sub>)<br> <br>
* **Pathological**
  * **HbS**  
  Sickle-cell disease.
    * Abnormal beta subunit
    * Unable to deform as they pass through capillaries
      * Increases blood viscosity, thrombus, and ischaemia through capillary occlusion
        * Often causes splenic infarction
      * Reduced red cell lifespan to 10-20 days <br> <br>
  * **MetHb**  
  Methaemoglobinaemia.
    * Ferrous iron (Fe<sup>2+</sup>) is oxidised to ferric iron (Fe<sup>3+</sup>)
    * Cannot bind oxygen, and left-shifts the oxyHb curve for normal Hb which reduces oxygen offloading at tissues
    * Normally prevented by:
      * Glutathione in red cell reduces oxidising agents
      * Methaemoglobin reductase enzyme uses NADH to reduce MetHb
    * Occurs due to:
      * Oxidising agents overwhelm capacity of glutathione system, e.g.:
        * SNP
        * NO
        * Amide local anaesthetics
        * Sulfonamides
      * Failure of the methaemoglobinaemia reductase enzyme
        * G6PD      <br> <br>
  * **COHb**  
  Carboxyhaemoglobin.
    * Haemoglobin binds carbon monoxide with greater affinity than oxygen<br> <br>
  * **CyanoHb**  
    * Haemoglobin **irreversibly** binds cyanide molecules, causing a **functional anaemia**
    * Cyanide inhibits cytochrome oxidase in the electron transport chain, preventing oxidative phosphorylation occurring
    
###Oxygen Saturation
Oxygen Saturation can be defined in two ways:

* **Functional Saturation**  
$$ SpO_2 \ (\%) = { [HbO_2] \times\  100 \over [HbO_2] + [DeoxyHb] } $$  
However, additional haemoglobin species exist in varying amounts, and this definition may deceptively imply good oxygen delivery when this is not the case.

* **Fractional Saturation**  
$$ SpO_2 \ (\%) = { [HbO_2] \times\  100 \over [HbO_2] + [DeoxyHb] + [MetHb] + [COHb]} $$  
Fractional saturation includes carboxy- and met-haemoglobin, and so is a more accurate estimator of oxygen saturation.

Note that pulse oximetry doesn't measure either of these and is dependent on the calibration, but will typically measure functional saturation.


###Myoglobin
Muscle is highly metabolically active and has a large O<sub>2</sub> demand. Myoglobin serves as an O<sub>2</sub> store for muscle. It is similar to Hb in that it is a large O<sub>2</sub>-binding iron-containing protein myoglobin, and is different because it:
* Contains one globin chain and one haeme group (binding one O<sub>2</sub> molecule), and so **does not exhibit cooperative binding**  
The myoglobin dissociation curve therefore has a **rapid upstroke** and an **early plateau**.
* Has a **P<sub>50</sub> of 2.7mmHg**  
This allows it to take up oxygen from haemoglobin (as the partial pressure gradient favours diffusion into the cell), and unload it into the cell (so it can actually be used).
* Is found in skeletal and cardiac muscle

---
##References
1. Chambers D, Huang C, Matthews G. Basic Physiology for Anaesthetists. Cambridge University Press. 2015.
2. Brandis K. [The Physiology Viva: Questions & Answers](http://www.anaesthesiamcq.com/vivabook.php). 2003.