# **Keychain Model**

*Fig. 1: Final iteration comparison between the keychain models printed using Elegoo Neptune 4 Printer.*

![All](https://lh3.googleusercontent.com/pw/AP1GczOsJFn27k4KJYoBYqREZNCHdQzUJ2dRoHW2vAhjqcLqd37JvgCHa4G_oosCy6UrV_D7L5QzV5GZg0tIufbKVvTjDPgssrjan3aiK1Ntsau_mJH2LEt5u7Vm2Q5ZZnydeMfJuSKXOkPVXlyYKTulQi0HSbBvMIPBiWWIQjM6K7Lm2uaTKNSwVsiM51djsRER_GwXrlUM9K1V62VFHT7DoJgYhK_5SsdIBuIOslTG_Ef-3EZmmTYr07jMbM-CHiPR_tnrF77OR7tUwsVVvopVKo4-3fuQ3KgMjpQMsX3ADQ2a1sXJINrEMiKbuPL6tFAUqFuWSS_SDJuc4iBdKwFp-WPGEPOUSPcH_APPP8SdZGlwoQ8f_nz25zBpKnEks9infD2Fj76lf9pNtWIoF6yMxMFQvprs9YgkcMuFYWcFuXNQMr84xvTMzbzwwMmPD422nq7CbIht8qQms6h1u6JiLCKB_dbR6sDZXlNbvwRhpP2gTf4cg5IL8_zSCgyRFSF1gBeA_QqmviI7U6KKPbI3_7IMYAlJKqxlrlJLe7TBx4Bkx2xtM-0pvcWq_IVVDEucceaW6yKsSLvuNLA-RWerco5TDxZ9fSZuibdYicLF2jShiitUBrm4Wm0-zWBosmtCeLR1Dc7kGKQcNfbCfRPQm829NjuI8h72VYkDmv1iHKH5OKD2sY4LMHMmAJKcUgd9lipduUm-wE2entpceD77MYHY5IPYhIBQLvczqT4BMVXRRoMmuEI-R375N5RAx7ZXZVX5mcH6JpoinIB2XgNDqRhBDek6N7a8i4KL6cEX6zynP9_hPAwvubjMlse6dy6lP7S3JbsVxlCgLYeb8t8Ptc0VIqlnaaBvDNiiSHcwSrasmB7YGeZlUXJRptOml7XOChkXqKvIjlHTCtzIvSghUoNUA3zBqnM3dUK774_rg8f1lqOBmuL3eHmfiw=w3173-h1244-s-no?authuser=0)


## **Overview**
The project invovles developing and printing a functional keychain using a FDM printer that is mechanically reliable under daily handling conditions while practicing relationships and parametric CAD workflow. 

## **Goal**
Design a durable, compact keychain that can be reliably printed using an FDM printer and withstand daily handling - including pocket carry, impact loads, and keyring interface forces - without inter-layer delamination under typical bending and impact loads.

## **Success Criteria**
• Keyring loop dimensioned to accept standard keyrings without interference.

• The keychain must be able to withstand normal handling without layer separation.

• Overall dimensions constrained to fit comfortably within adult palm without restricting grip or causign discomfort during daily use. 

## **Conceptual Basis**
I referenced the image below as an inspiration behind the design of my keychain. 

![The Comedian's Badge](https://static.wikia.nocookie.net/headhuntersholosuite/images/1/1f/Comedian%27s_button.jpg/revision/latest?cb=20200827152035)

*After I worked on v.1.0, I referenced an external video so that I could better understand how to fully take advantage of constraints prior to extruding.*

- [Fusion 360 Tutorial for Absolute Beginners - Lars Christensen](https://www.youtube.com/watch?v=A5bc9c3S12g)

## **Engineering Considerations**
• __Loop Geometry and Stress Concentration:__ was identified to be at a higher risk snapping under real-world tests, such as carrying them in a pocket, dropping them from waist height, or the forces between the loop fillet and the keyring. Geometry was adjusted accordingly to reduce the bending stress. 

• __Print Orientation:__ was chosen so that layer lines were aligned with the primary load path through the loop, reducing the chances of layer separation.

• __Material Selection:__ PLA was selected for ease of printing and dimensional stability, with the understanding that its brittleness requires conservative geometry and generous fillets to prevent it from deforming. 

• __Ergonomic Constraints:__ were constrained to fit comfortably within the adult palm to avoid sharp edges and awkward handling during daily use.

## **Iteration Log**

## **Testing and Observations** 

### *v.1.0* 

*Date of Print: 12/17/2025*

*Fig. 2: Keychain v.1.0. Print was not fully rested upon the print bed, too big to use, application-wise.*

![Print#1](https://lh3.googleusercontent.com/pw/AP1GczMv6a0eQT7jdg-GX9uzD4ZRUVzJvU72TdH41EdGSKLava9yLJKwPpNoUVN6XlwhB7spTQMI3RKPEmAkG5xrrzwYhLRPfv_uh-jcdBI8bhFQam9c-OmbRe1_tdb34equ2x068hek75PVIxoSHWawkfFvGXs8mJzhA9087i--JPrxqj20VUKMgmiZjM7wU8B8LNpYgEUBGbLs2W9xPt3omMjFVUDLrzql4_AvNrK_zo9BWVS2Vc3g80UCzb1FuaUgNGZ0MBhIlheXD_zQdcxeDpAS_Eu7EICcRFsIcHd2FBkprkVN2GlyLLUM3bwHyy-Q1xA36inJ0g12tnZ8834MjetQstzoWgBEbvS-OcnQjIqI0xqcw_bHkQSqXthfLa4NQgVCOP-NlqT4Fmkd8Wx742FX_TtMhn_NNSWoRJGCpr1iDhu7iE_SZ72ENfyDCIpV4oMLXtAs2KxsoM0ghCWWaFR9yQLd62wmYLinytBfzG61CcbECxghtk9ibRfBoYOT_HFVmceLJCfl0L5aRgtl6hx1VAqxAHJVIrBD9Oeyr_FVnmjRKCH6PD8oslo_SmilCRZphwWyDIerxAJFcchrWuhWLFnscFD7jPRvzGnHqqGr1v1UHXsg6Iqmgg-0ycLnGKD_HqPd8uSQW8Dze8GuzlBB8WoLU-C58W9JLDEACOTjJWskgCkafCoKqJIn5fSq0j__cW5lgyVA9hFzOdoh66_8_lqzej_poE1yT9yk9-507npCP0brRrJEW99WfIN6yoCHwawHa_Y6Gxb8sVmPutPZ1uVHSBuUpD5-TYEl8lyB16w61kbaELBJy9FWlD1kWGXvQyc80EehXgZgsA6vi4EmeWvO0T1nXYWDDObJQDDaWFHOrbnKPuBTjh8J1EddD7IcAqHnopnKo9BkZWqfQ5tuQeLlVNI0XvV47IzBtLxI-9F0mGgn1quIVA=w1672-h2230-s-no?authuser=0)

• Oversized relative to ergonomic target; bottom layers did not adhere flat to the print bed. 

• Sketch was not fully constrained prior to extruding it. 

• Bottom layers failed to lie flat on the print bed.
> Troubleshooting indicated that the bed may not have been completely levelled or that the z-offset was not properly adjusted with respect to the bed.

### *v.2.0* 

*Date of Print: 1/5/2026 (white); 1/21/2026 (gray)*

*Fig. 3: Keychain v.1.1. Print was rested, smaller for daily use, but the keyring loop was no thin for daily usage. Broke after repeated testing that involved placing in my pocket, carrying it around on the carabiner. Need to increase the thickness of the loop.*

![Print#2](https://lh3.googleusercontent.com/pw/AP1GczMzockFD-4ca9KhYqdWRs_6FvJPJcG3VP4BqHV5-J0H_w6eMeBF6oAmhmJQ5k8zZBZ-53uOUh66cK5e9ynAuQtf-uMqbF1KiU-G9Hk5V3pVr9FF4GZRyh_tTcZhGdUDpvdNLpXCsohods6izZ5H8LsVbeBfdwOyEjQfdpt3-Vxiem5G2K026lyz2LM64Wd7ZzB3NWp5nVDYmZGk4GvQsz4OhptF0UN2JLXOifgiwHht0TqGEDmcZ-I8sWIlkYNcr8HjYfkmxc80yUay3oM0IL7oQP4npiIja0MJAN3dhRZ0tZgM2FC1zGdv7tpay-Hyz28mCDKFscfuz5GUaJzMna-Jgy7yxubC821wSOqErJ2NDE6mEHifAsFBqYPUOvBSEyQe92Inv4idnTSg6em245uqSnPJxMz7fxDUOtxqEHKBqxW8fxEWiARoM8Y9C0DnBr7cobs-KdTTzrMD65UnlB0_y0vcveNfQEVNQz6PkYGMGdECPoWBWR3FyCkATL1TLwAoHGA_n0UY4QUSt9PDO-xnbHzsJ71uaUTeLv5qsunpeLnfOU7LLFQ0WR0Ites7Dk20UMYqi5KTQ66DpsrXIWBNuedawzvRbg0tB2mpdU6rEkypShvVy87mBf-d-1tBeQb3KFr00k2T0WUwAwRsgcPy1EyjIy239Ih1IDN7qUVEymI7LJvu-fq1KWRxuO0wJ9f09MBp6rrZMH1-wI8FlCsEBhjozHLe9q41hKmtxf-lllXcBfcekjZlUkhI3Svzp4DJqLewQaCaZU_wx2UQIEVln2v211OwFh-NWYQVOmJUDPhowLsXJXs5TTCf-elFMI-hS2_uGUMQ5Q-lLV1l4nbv33J4_FKbN5mo-KyftWr8nULKfzqrEPZzjnLLkfRAyly8oEOVF1Hjsy2-PvNKkoyZCHtDBdOj4JGrPCVGSjaKYuZC9cdSghzkLg=w2685-h1163-s-no?authuser=0)


• Ergonomic dimensions improved; keyring loop insufficient thickness for sustained daily use. 

• Sketch was fully constrained prior to extruding it with help from the external tutorial. 
> I split the keychain into 3 components: Base; Eyes, Mouth; Blood Splatter to allow for independent extrusion. 

### *v.2.1*

*Prints on 2/2/2026*

*Fig. 4: Keychain v.1.2. Increased the thickness of the keyring loop. Printer was not cooperating for two or three prints, as it stagnated near the loop, producing a material blob and partial nozzle clog. 

![Print#3](https://lh3.googleusercontent.com/pw/AP1GczMCBOCNOf0mHiTtWC6QLHo5AvA6Iv1AEnTUMbgxCXu53AKLzPxxGdWD6NgL7gxPCb6T2EI9L-NN2lg4a5Br4h_HpH8OKcl7yWYXfYmtr7SgqZpXfCpmhsriHK9BG_NjOmdpe2qrLfttndX1xaL1AT7aBPAr9T1gH2ePo-2HCIjwTFTV_1ik4ixxiFj7BXodOZKfA43d3Mo4oq-FGC9uMJ2KAxUm_2-JX6wYkOzfN-xvsgjZuhLeTx7WwT4WEd28N7w0t1raCiBGbg2M1ncttaottPofR6RTF9SMbeXjlymBGr93d9EVmDZA_EiidTW9Y8vqYynTS9JimkeQDz3RD_YeL_dfLQ99e86yBfFCNMgm81oNZt0Cpm6F4AhMpipsC8oPAjnUlOXT8a5rS_WH0el23RynzfmD0iprOQUZ2K3O3GELz1heakfCVIGT_DUOIBMkwTfNxVEwUvClQ1j0u-hSER8izfZ7GkUZDYtbhW_y23EF6ftKUUzTp2uwOUkWR6pRDoOOvkRDsyGJ2CLfLUfJGtfZjnIxRRj-h_V3tAs1oD00tJdWKOjWEnbAWdO5pt7_ERdH9Wcml4vWhFhEtuiK4HFM6aIxWdiAnApEx6pbv3MAgaJ3TKHk9R6GmKK2LJXmjKIDJYF-4FBannx9aaLfLw1shfEnRQrmIT9WhG8-fEPvytRn2xMOSsqrZmqnm6AE3JDuYXy63ID-6yC4pN-RfjT8IKRlLKxAT1GEh5PcTf2fJj4a4a2ouXjkfOfZ6_oZ6xpHowXxnQtzfmIuCSOTgiZUp_e4qsoxq8d2TS6nEa-fOphuGM5sx7M13sGpq-T2ITthR-iTSfxwdAWbcOn3Rd1KOvRCJf7DJ6a4snlyddyp47CnJKYq2LuB4YzPn_ENZgbtxGJD4aVwMu_AJzp0jKrWSFDBtV4WO_Lf4piRRtrCjrDDm-QYoA=w2763-h942-s-no?authuser=0)

*Prints on 2/3/2026*

*Fig. 5: Confirm print reliability following troubleshooting. Issue resolved; part cleared for daily use.*

![Print#4](https://lh3.googleusercontent.com/pw/AP1GczPx_wXzr-INMjLRdVj-QW1veXs-5nWV9fExKy5XChI9x-hRhHo15LdzE3ME03hupVzdgcBIL89qyRg0wctUXmnjcZT4E2r4uBqXyxfy9tkfP9VjKXxtuf_npuFEZSvgMYZwTtB9W6LEgWVv8XBjIIhx5yynPar115cMF8vjIgAqha0w99jedax1IWhrXeQOGjNIi9hxblcdzrX_BWnGPprSINxm9jFG4eAR9f10t3fP86RAPnInJkeGO5AbC87sgl4bYBSAK1fj53PiS9K8EhLRmpvEfkPLb3CXOBsTY8A5SuorqhrIVIOJ7Gjk8u_Nt8GeIce0EfE8ORGkMruYJrcbm54oUEGdwt_zCuJzZbX98P7Dwk1L1cJqMTY5DUUGz4L6viXSXJD_qDaoKzTmeY7drVMdhpVh9bogLvVHaSgZwBPg0VQI52lFxtN4h5Ztwn-Zpbsfyz_cI6xz-1865V6Bs-k3lfHKWYhM2e4CWrra3XCrGUiQnDuIU7pS6w1fT0bW4csA8fvTGpOYxvRkq-xqdg7HaEk9_m-SNaamfSPkKhx-qYWNN3MpR5QVhWGiYjQT1mNFPoQwryYDjkApxKHaKkheqq4kS_DFoRbl49i2ZZWmOKCjc55pMHmUof6TECKyakBh_77oCZam_ma2gg-5mfN6IWQgLx4PLvHbTAj2uS3NoVHRmIJfoC-n--ZPcID3NfvIoc-ExE0Lu9XIHL2S-fdOYPeHqFehkGZXNKGMLSNUmRSxv3hhG7Q17fkg4vFQg4KcSloynWI5ZzaVbXihK9W7phqHiar6SUiYcV8AWbv_w1SJR3vFaFOLXAwdhTMSM18VKQzo3IvYZ8YgIsI1hP24No38jLP8E_0TQxvSPK02zojl4oZ0P-VQ6Uh9aBOW4IB_v0zzLjgi08XkjsOC-eEMUgxtqo3k_IdUSoYHKx3oDZGxUi_kZA=w2145-h1037-s-no?authuser=0)

• The keyring in v.2.0 broke at the loop fillet as a result of realsitic use conditions, such as resting them in my pocket and a deformed loop that broke when dropped on the floor. I increased the thickness of the loop by ~2x to reduce bending stress. 

• 2/2: The extruder would arbitrarily pause mid-print. I let the print rest prior to removing it from the bed plate to prevent a deformed loop. 

> Troubleshooting indicated that the issue may be that the filament is too hot to use after staying at 205℃ for too long, so I let the printer rest before I continued printing.

• 2/3: I aimed to perfect the print before I moved on to other projects. I determined that a Z-offset of -1.050 would be ideal position for the nozzle. I also preheated the filament to 140℃ rather than letting it fully rest before beginning to print the keychain.

## **Manufacturing Notes**

• Printed in PLA with Elegoo Neptune 4.

• Optimal Z-offset value: -1.050mm

• Geometry was sound; primary issue was slicer/material tuning rather than CAD error.

## **Lessons Learned**

• Proper Z-offset calibration is critical to first-layer adhesion. The correct nozzle position produces light paper resistance — soft drag, no tearing or catching.

• Unconstrained sketches propagate geometric ambiguity downstream and complicate iteration control. All sketches should be fully constrained prior to extrusion.

• Extended filament dwell at print temperature can degrade flow behavior and cause extruder stalls. Implementing a structured preheat and rest protocol between print attempts mitigates this risk.

## **Next Steps**

• Introduce user-defined parameters to control overall size, loop thickness, and base depth to improve parametric flexibility. 
