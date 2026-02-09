# **Keychain Model**

![All](https://lh3.googleusercontent.com/pw/AP1GczPvbtmXD3ft2MWQqVfBC-_EbDgAz1Bkx8CEWXoXuCs6V-rcBOxEyCtkhkJZrBzppiTN-xMPFBN2rgbFvWyEEu0dZlruIDv4H8J1FHiyA95IQwsTMhTxgUZxO1Zn_WV_b37QUOvCw6eaBpf02HEPts1XHSND_itI28KcpCaN7vBc8PXPFVFs4kX3RGAAFH2dtliBnyTsvn_KwkB3-vhmmTujPRLhWAdcj9Xtm504qzKBCIXj3PXr70bW-pQosz4TTbnrEtmvqV_RIKjoYEiLX-R-t2xYFhm9PGlkuqlYXQqYS-5VsDfRAGdB4XULnFESssYbEgC8soegdqxKpKEcMRpt4RfAZ2RbdRQW0RCcFonaEQ2uRDablDwZO6tTxSb78m9f1KtGQfGnr5abxwUt5oGv-rVPZBPcOD7xeBgXgRHOpkMgOX79RvrVc16BFUwx3Hx8NXtQAs1_KuGJz_hSTj4_OvhAxB8xmpluiDyopnpQ33U7M5pJ0h9ZPYQXQ8noikwyo0VF1FRXRVUokFdl7-_7KZXx2fkwVyLgjmtHvuQijgZFzaINiIKHqsv-I5jxQLr5tPkbHl2bdWB1h8XbupBFEQMGVQss2AjwFwFdN-wm2_MQEEupe534JGjyZYnLTXzoS6F0mhLlJKzHmtfnOokK2JQ_zLhUZIDP1CJOuOimu7fDXW1MBTCKO8YoBn2F1FV_o4l1mfRchosKdhYmmz_N09HuKLmBBokBPjm6sGVHY6yC8aeCUTZUWpBU9fK5IoeDSS7AQMKzvHNjbgcBylWU4wGH_5cGiyCubkx-JJxHLm7n28uuITZI3zXyf_KaKwUz9bSK7D8-Gj_LV6MVUrs0gVUIO5DR-RLxQH90xpDMdOQ_kcVMy2KoawHZFSzLIMv3NyttMJV6mAaT9QAOeiysdfJ4GNzYK_IFVJkmCztrE0xJB7-x9t0=w3173-h1244-s-no?authuser=0)

## **Overview**
The aim of this project is to develop and print a functional keychain design using an FDM printer that is mechanically reliable while practicing relationships and parametric CAD workflow. 

## **Goal**
Design a durable, compact keychain that can be reliably printed using an FDM printer and withstand daily handling without inter-layer delamination under typical bending and impact loads

## **Success Criteria**
→ The loop of the keychain must be able to fit standard keyrings.

→ The keychain must be able to withstand normal handling without the layers separating. 

→ The keychain must be able to comfortably rest in one hand, with its overall dimensions constrainted to fit within the standard adult palm without heavily restricting finger movement.

## **Process**
I referenced the image below as an inspiration behind the design of my keychain. 

![The Comedian's Badge](https://static.wikia.nocookie.net/headhuntersholosuite/images/1/1f/Comedian%27s_button.jpg/revision/latest?cb=20200827152035)

*After I worked on v.1.0, I referenced an external video so that I could better understand how to fully take advantage of constraints prior to extruding.*

- [Fusion 360 Tutorial for Absolute Beginners - Lars Christensen](https://www.youtube.com/watch?v=A5bc9c3S12g)

## **Engineering Considerations**
→ The loop fillet was identified to be at a higher risk snapping under real-world tests, such as carrying them in a pocket, dropping them from waist height, or the forces between the loop fillet and the keyring. Geometry was adjusted accordingly to reduce the bending stress. 

→ Print orientation was chosen so that layer lines were aligned with the primary load path through the loop, reducing the chances of layer separation.

→PLA was selected for ease of printing and dimensional stability, with the understanding that its brittleness requires conservative geometry and generous fillets to prevent it from deforming. 

→Overall dimensions were constrained to fit comfortably within the adult palm to avoid sharp edges and awkward handling during daily use.

## **Iteration Changes**

*Date of Print: 12/17/2025*

![Print#1](https://lh3.googleusercontent.com/pw/AP1GczOggGp57Kjtf8Zf10B7u_xKdm3C5_LMj24dX6aLUn7ge6XtqW-jG8v4NnUX4Z8Dzs86wjA14byNxRJs0tqzqKH3Ukyyg2ZdNPX42McmKEfYMcGTL_Utp0Q2XS5SwxHq-W_85vt8wWv6XDVXkl-XErnSbgq9bMytUttyKbk57ZywVu_eECRTs78DwEYRKuVyvyRJ5UlAFNd37KFKZ4S03_EYAehVIdaNW8KZPAo87BHQl3089WmjvQVgi1_Auf5DrgqT5KZpEhF9joRFiZ5BjgbuenJYbNKzKvWldBT3vmidVAdWl_ulzkG1ucl9WPJvKpMqoUMQv40MhlQo_QL4mx3ZJRHB5_kNxHIcYlGSYVx5YAZxNvOZqmvu0HIq0jX7ROdKiYrR1kmOnVMyBMlsuFRRnIwwe6nGekVbIbBAObHaieTetgp8AM6biJ8uA5EQ43WAMW5pYtyxnJ_uaPCwKr93hajcgbfxfOo73GojuvZLJjWwf_bHzprAXMPRwvEwgILmYyhhhc0SEjInd2Ng5GoPp-Kz43om1CoC-2XTruWsEK3xqYe-CBvBrQDf5Gx9ls-jPG-KmLlSDl4ZWAeK2MsP9rHzfVR8oRS2L36HL84KS88f1ABtg5TYimyAvWRm1q6-6JrdjDh_OWq-FaRKvx7Wty9WPYV4TSClzjFuvGXCh-_F4NkrbZniwsuSrTQXnEdHa-zsNJGNa_grELli9Wyl-BetNFFe7TvR-iqCUUFpyF0kzFX_1zdnJQKzUW6nrrjztRmbJlU75jBIia4oqN-UAi5uUKjQEQssVou2kJE3R8fnSPrBlWqv12FzXKVi6I4pPpA2AdfMCruh1PamKh7iwqfsW0twHlcbGFnQPJa3_XttXBbgB6vKFItDrYvhwt4CzpSiXUCtsz-pebnP70tEwgmXlGnN8ZAvZtkCQqkNzqpWpvkCXTE=w1462-h1950-s-no?authuser=0)

*Date of Print: 1/5/2026 (white); 1/21/2026 (gray)*

![Print#2](https://lh3.googleusercontent.com/pw/AP1GczMaxD13XhhU6PpJo8VCPQLMGMCxXVuLBHHKfGIXmGP-CxrVWsKlbFqJTQRFLWrqBLG5-HKzbSEYRpXEX6HuqnIE3AFhlk7bRvPxcs7zU-9ewfG7UL8xZjHAAlCLjR7hyNGwiva_Q_KUpnKJOKUrhT1zIFsjyrUwyorwGLwa5lVUd4lFxNKfZ1lXrOSZXpmNjjHbELr8A3FeJXfUsx6r7C16wwEekmEnsPYAxXxuzk5zbk-5JK5o1bT0Lfl6F41Nr8Qi5aeGhZyUwyG0oFhGxA0DEUvdp73IhYW4vb570wm-2RtRcMENLfqE-EjQvMdFnL0rdlkOt-6ovbbpyK0NLhQE7DKkgilBVLdU63MOCJbkKjv4sh8en_mO8R1jz_EbOmtPxCAm4nKfOTxIrnlWyTjFwNflwBOFoDO7xNvj3r9h88XoO2mYEOUlGENXMe_t2DZxz7Q5Wl-D29m-zBGNElN78MQ5WFpJ290sTLg3mUZFs76n8OUtnC4iHGeoxAFVX74fjhfowWXXv2osBcWrdvz87cMtlkmuNnzb98NneH-lPewtkSAGibE7LOXSDUFGYlsTsYBBEhZ-4tqlpYiM0YTvltKVGxWya5OG55YtAfKMZQ1ptixZNdGvmGVByPZJs4G3yBSAatyERv9aPs8_UfAJ---Oj-cJrF8CCsoIpbXBEYdlkmwkJrqROZpITghcMBJ2PxphRbseV5BPLHiINRBqv-MFUT9HESdSytA9P963CDobrE_3TU01QATTMiqdkCSP41usMEoj3GlgAHUNBMxZfPJl7UReGyDwmO9gzceLpnNrQsHxwG14v9tMwYkX93p90BoGK1GV1CkSQCyVlQHYQzwlI0sSm7hOUPdeEO8J7iTIf4NNjfWgA4udW2J4Q4IzKCE8Wsw4NklIL_QvGVt3oJ0-BzAzYkEkDHcIBMOVsUZMOIdw2J8=w2685-h1163-s-no?authuser=0)

*Prints on 2/2/2026*

![Print#3](https://lh3.googleusercontent.com/pw/AP1GczOvATW0bpGKRkVfi_n65JzXb1dgF5rcnTsOeG0RG8WzszssrUCvhG4wqAmFIfBhiqOuMMF-9031HCchC1Y8LVngaYI5vIw9qpNc88FB1Ro99705IaKo9OfF9oyEbcjGGXiuWcWRSNm2zkvIc51Qfrut_uqtJAnvGMY9mG9ZM7fC0mPX-sR657y3gD6elz87cAyDyoN1XF-8U4Ccljs-4drgJw2NWotefTe3-DfbcVqN0HJN0IoLM3K9RxJcYFDHVcwb1YcxcnRFR9d01ppegu_k3Nk_d77xb5XmKkF_aP8yQ6s5I_T02q2g_Lyzm0eNi1qRGYEsNo81aAvCj9ge0ySebGAogwfSUx654hMnraVhzL-fcVcOg6z5t6QMho2pxblioCaCtZ7afCXhkN9q4x-YIJspo9DbGQI_0wA2oaclgfiL6bZOpfDR5GHlfEHyG_Max4zoDG-NokEgFUzLwCuetLYsTN7Ge3cms1f6RDNIz9GqPNV6-6ho4lRdcWnMg2x6RcX3SNNXCgzSS5drw1ybjLiQDQJozUjwvwYPTCMrIVJSBF5JpQ9NLBgYetd1lSLNKI0LQ6Qfj-D766Rr5I3G5BFaxD6RFUz6ZH-vhyw3NNhDGL1ELKu_LbUbe2v0NtryEOLkKgV6jo2J4kZjOuI8yF726q_jgSprsoFQxkR_QCxEL3gzYkum0cojVCc0nAch9Y5ZxhG8UCsxOQb7Ad1zlpUmlYvYUFgR5WhH8g_1GmFcr_JraVMZrVI8LFC1LlPj_WG6kaAVzZfceq_0eoFtioZgHgDKpNGcT0v4TyQFKziOQnz9GG7o_vBWXl1PN6uxn87fGuT8dXnxKAAOGGnCutNrADjxGOJS4qCtpWcrsXFQT7n6UIELH6yfKWJelPlPlzlFr0IPbtpjuHJtY2K2m6b3hEw1gkC6m6Abgq4PSoiY8-joCPY=w2763-h942-s-no?authuser=0)

*Prints on 2/3/2026*

![Print#4](https://lh3.googleusercontent.com/pw/AP1GczOTniAtXXWTK6sbjDYpeyZfjVFzAYO3ezSihNnW8fSHd2L1HYhRizBuLv1aB8fibpcG72WGyTEEiJ7D1PbEe9BDFS509rABI11XMve9byFi-pieAghyc1Y4efW_iHiQry-cZRasPMYzgtRp46QW2POOJtON2BdH5HqQXLdg8oHnIc06wWQCVaglEOWe39OhRjuyYcfqWmbs0E_5jxjV7WYiHRSeY23TtuL0FY_qPAb4KIiLjgXqpc8J-1JKKWOfvLgw2da6YJK81Q_gZxqjSiC06Z5fp4mB5bgC3Xw9QGLr3m0h8GV8tws9jieAxo_KweCHHWCZ94P0PLznJzeZFCVsWqupIhnLuWuYFcHNh55oDdM8Pg8Ne-TBQ42wQsK966uNMDMaYObgfqjagCHZUqP0WUqixcPRVxPJaRi--sZNWYeG2V2PYn1CT6mIp75GbHKgFVvp8jr6s2QDi3O1zCvyb35Zgn94VYZwbxW_IcMErxqOiw3c0xA9u6023BcFcFfEHhYFcbdhst10Y-UzeQOb2AdemR-YCy9Opvc4n5QrbzARLoRsPyFBTD8eyx1OHA4PKM6o5JXt3JqhmDKHLdfP5hmhi_1AQCDPNEWIPH4Y5a-u6s0geoaottDhr2Y25ngt5wgoddtvQfrNu6b_2kEEQN8nzQim9YD3F0ifsrduJRu1XieQ4dkOWmwxNv_6ebud-C0cUZGIgQFTXm0T9WVKaXKqruF8H_J7CjigUXsreOdjAhcBMUt_hiqVA2HgAP6B7qW4xYaK4XtBcE5KDN6UP86jiOb9w1Qdo1tNag-k9Hn_t2a_-XE9-VpAZBVcfwn4cayVI72r1Bdhk94UbKk0pgx1QaIlWNRCil-xt4UGRd5Nk8s272Odk-AWfaooPHUkARFjsu7y_h8XNYfuV32JF3Jcpi3Z4mSqZ_Nz_FHFtWK-DZ6ubwE=w2145-h1037-s-no?authuser=0)

## **Testing and Observations** 

### *v.1.0* 

→ The keychain barely fit in my palm; the objective was to make sure that I could easily grasp it within my palm.

→ The sketch was not fully constrained prior to extruding it. 

→ The first print iteration resulted in the bottom layers not lying flat on top of the bed.

>>Troubleshooting indicated that the bed may not have been completely levelled or that the z-offset was not properly adjusted with respect to the bed.

### *v.2.0* 

→ The keychain was able to better fit into my palm. 

→ The sketch was fully constrained prior to extruding it with help from the external tutorial. 

>> I split the keychain into 3 components: Base; Eyes, Mouth; Blood Splatter to properly extruding the separate components of the keychain.

### *v.2.1*

→ The keyring in v.2.0 broke at the loop fillet as a result of realsitic use conditions, such as resting them in my pocket and a deformed loop that broke when dropped on the floor. I increased the thickness of the loop by ~2x to reduce bending stress. 

→ 2/2: The extruder would arbitrarily pause mid-print. I let the print rest prior to removing it from the bed plate to prevent a deformed loop. 

>> Troubleshooting indicated that the issue may be that the filament is too hot to use after staying at 205℃ for too long, so I let the printer rest before I continued printing.

→ 2/3: I aimed to perfect the print before I moved on to other projects. I determined that a Z-offset of -1.050 would be ideal position for the nozzle. I also preheated the filament to 140℃ rather than letting it fully rest before beginning to print the keychain.

## **Manufacturing Notes**

→ Printed in PLA on Neptune 4.

→ Geometry was sound; primary issue was slicer/material tuning rather than CAD error.

## **Lessons Learned**

→ How to properly level and set the z-offset of an FDM printer. 

→ Unconstrained sketches propagate downstream ambiguity and complicate iteration control.

→ Pre-heat the printer.

## **Next Steps**

→ Introduce user-defined parameters to control overall size, loop thickness, and base depth to improve parametric flexibility. 
