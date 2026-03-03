# **Keychain Enclosure v.1**

*Fig 1: Final iteration comparison between the two enclosure models printed using Elegoo Neptune 4 Printer.*

![All](https://lh3.googleusercontent.com/pw/AP1GczP_Wk2cPvBVyWAoyxn9y7N0WPYFQRQKGilRJD6S8ZZHblzLHQCW9wqVz2MsU9g-c-BSColTb7ztvSAhdTwwuATqeA-F9IdkG-JA7JSd9HyeSm_CCJnYSkwXVgdR524VM9Pz8dlR_Xn9XYNOpoNgOsKpg0pSyWXpQ7TFMs9s0iLDWTMs4MixFysXEePB0k81_M5dJ9ndxJ3fJm0egybo3MchvEdNjGVykjnRWNimNNphuDTUUqW5sHJo6lArd6zou50BoOFoVqvGvwGAFVTZDHx8ENjAWi9gmO1HoXrZ2lCAbrOyefsHQQuK2mxlEFy-pcIttjD4DW1dQAN1B4ix1bhroNePL8yy3ntGOlSci3u1xJwv1V3xlbnUFbGYDWAGsquglojfB3anWRoMpWoCWZsFXROUjBnT458vJB3wigROSLFXNtQOSUYWsfRK1639YIHcjaVcMhD7UkyabVTVI64UdVXLzYODssdilYZ4KhEn6dFts8om6he7jTdr0J3o5-_Lbq1jCHc-Gdg8Y9D1UgfYwrWr6XVUXaH9AA24hJ2q9vwOAPO101AtkHnSKZbqJyzXHn94S8z-72d36MUFV4QeJesMgnPczrnIXy0Un7niNnyc-25OwLPHrrXaM5dRT0BrA3ftTcGYzK5rDu5pQTrqKgBLsyB5pjsUg2IH7bfS5J58WdVDU9AyKW5vyZJacEZ6Fh27Uk_XzyzGtcKrg-xJGIVFIV1rwuiw29GSSe2qHXh1Rgr0FkO7CLwxpQM8j2rsPDEUINlB38nkbkLBGfEFekcN2oCOXPAao3crFOQ6xF4OFqi5fZX-ggI_mK8xqzxNnKkiiNtupvZDCtcX7ELPk9ZyZ0ed0x6QyBkx6zE0K7lHDjU3K5uIiYKt2Z8C9issB7JG2mDiEJPqfJP-N2zX7O4sw6yN2RE-BumHjXLSFC0AGGXIe_PUFg=w3323-h1301-s-no?authuser=0)

## **Overview**
The aim of this project was to develop and print a snap fit enclosure that utilizes a cantilevered lip feature on the lid that engages a recessed edge on the body for my keychain model. 

## **Goal**
Design a compact snap-fit enclosure that securely houses the keychain while incorporating a centered docking slot, balancing print reliability, fit tolerance, and material efficiency. 

## **Success Criteria**
→ Keychain fits securely in the internal pocket with a clearance of at least .2mm. 

→ Lid snaps on/off without permanent deformation.

→ Lid and body assemble with the assistance of the snap fit mechanism; clearance of at least .4mm present in between the mechanism. 

→ Print completes without layer fusion or deformation.

## **Process**
To better understand what to take into account while developing the enclosure, I referenced an external tutorial and adapted the technique to this enclosure's geometry. 

- [HOW TO CREATE A SNAP FIT IN FUSION360 - adam james](https://www.youtube.com/watch?v=HcLT5Hz9-mk&t=318s)
  
>> I imported the keychain for which I wanted the enclosure to house. I constrained the dimensions of the enclosure around the keychain, wanting the dock to be at the center of the enclosure, while taking clearance into account. 

## **Engineering Considerations**
→ The snap-fit mechanism between the body and the lid must have a clearance of at least .2mm, based on typical PlA dimensional variance and prior print behavior. 

→ The snap-fit mechanism must maintain its durability, while opening and closing the enclosure, for an extended period of time. 

→ The pocket of the enclosure must also have a clearance of at least .2mm for the keychain to properly fit with no struggle. 

→ PLA was selected for ease of printing, high rigidity, as well as being cost-effective for the purposes of this project. 

## **Iteration Changes**

*Date of Prints: 1/11/2026*

*Fig. 2: Enclosure v.1.0. Doesn't include fillets at the inner corners and insufficient clearance for the keychain.*

![Enclosure #1-Open](https://lh3.googleusercontent.com/pw/AP1GczMsbEapc5YyfpdpNtQlwkshBSd5L00PVaDaxFIsSV6YR9GEP4NVFBL4TTg4QqmKyL1LpNpyayRfgXxTYPv6jUqadPvHhd1jFggwAnlQlx11wK2z7TguTFC9yGApS6XbyHeXE5aS2n9xRgAhDDl3Nk2gUBXNjxc3K2jdhbEgk8iwutUVzsDattvBwutgRistuxTHsO7ZUiOhd6r96fd3iqo5ELMYHW_1zRlWUyCsks_snd44fAkFslPDZK6hEjKcxY8vVRRkOHTeQfD9r0YWA_WmbHjxVnuJ0PYHOT4yR4xmhOzrbihDmrQqklmVzhy_WSvPqjk3jw-RGdbY-WyFhXUrsUk-UPB1ET3Vj7NOSoQXHE_8GW0S9aeVzm8LpH7qrdQGVagWvDuwjAMJtf-zlrSuaYuTVhyuoTLyLMDuoj6_AjkZFlZW1mENFc9zfJ_qHhQfIT--yvcHc12vuOOqag6yLIkEv-QsS2D1-6VqAICVWbxozzIpLtIRBkNLygBgHG4Pny7m6TfGsiPSz2gKRliCKycq3Ml2_-DU8mf0QeOeVldAEQ1xc3BDzNlijbDxXwvGdQGzuZ_F34m-gldROaudStJnvBNouif75VnuSgJmv9jnQhR7JsPjIxmYdTrdF31tGAAu8UkIpM87z5VFiKD2yuwPuFRZEp8MAqxRWiXPx8iRSKyh1iQSleVV99UI4k51cV4ZTm311OOsz_1mYC_OAq3q0uFqACc4R7i9f73V69WiDB8JAN37Y4D1GwbczMzYVQA42NU1pfVH6KUe48Hm7of6ZtkutjZ8AnnvqbOALQxEErxYcJXq9bMQXagIdPpsEQ5QHVgh1qvhhYb9xDrKAqfkb8sOa53tVNal0s44W3CfxQLvpAMEp4nS5sDZOZPwbANkF1jXsAbXe_4zOPdqO6dxXV5IE0ibc_Jf0jjnDFnb1dN81kjdUw=w2974-h2230-s-no?authuser=0)

![Enclosure #1-Closed](https://lh3.googleusercontent.com/pw/AP1GczP3Jmio0f3hfliPtbZClrOgb_5uzVj4UYLsyhMbvGjuXZ6gwk5sui5E4IVksP5alGEZypmZIZqLzUjAZcfyNWj0jx3F5BKYMzLApGXXf_zt2rS7HWGXqWEmFnllMrsjdpq4Av1_gUCd18HnxokkvuRxE9j9OvausNbvCqyREP-jZFFhdYEkN2l4R6I-57KTOLm_wDfiDyFf5sbDmezDZXGvLPrHGlOVyILOwhceL_aH1xa367BO4--L5d4rHirlD9G206xwCdgshRQEakQLX3fFrxaX3KZsOkBgz4xxz1fHEmbS3hJjMdXySXrf_lZM0gxrd9xF30xnWLOGp1rbQ0Q6TqWmurbReZcjcW3_KJ8nhtNVMg4YtvpY_8b-q4VBFf9SHM41g-CYY__j_I1hIovG0f_SQ6T3-SnWpB1HFIB9nW8raq5wlQDbvItzqIBeLMwq4fu9IRWvQnapNyN4UVH2z-wVo6-4xj7Hh7thQkPCAgVGkHQUsW-RJ08jj0V43Y08RZxZxzgywrH_VHfm-SfJHvtQ_aQAQESsnANPkJ3pS_IZy5PflgogtMt4cQVuguPgup__LHNAsTVwp1W_6r2WbDhEu2JytwGanGhaBZQ-PSo7jZbshQsKWMIVfJDfF_0A7KUVvkBgGPCD4_dHyhAxKD8__POzgCet1HAgUedWEmRe2_Un3OIxhJNrtlUQtn4KNA6cvgTS8eRRxawxm2M-TkaTBdA8mCZFWD6xXowe_mtqCtAlb1l7aZ9UR6XkNdAFHPChKp_lxQFMtgvwPVwQ2LOndHWsXPpAE-ZTWdLtBzEMrRYduKE-dDXg40nHuZhdKtOzhZm09UcMbw37OkHm6aPdBkgirFDBli47cZOgxSHkBieERf5oEiVVC6R5QbWUPZdbXPcNIj3pDvVYKFanEbYyL_YT0yTzhsRcIynOxVkoZvaMFrF_rA=w1672-h2230-s-no?authuser=0)

*Fig 2: v.1.1. Utilizes the lid designed in v.1.2, rather than the lid designed for v.1.1 due to uncompatible clearance between the inner lid and inner body.*


![Enclosure #2-Open](https://lh3.googleusercontent.com/pw/AP1GczMoQkhAaBtIt1b86OsypRgyfgN-0rTU7sdCLuiF8D41CnfJIRBF_p_NdcdCdUcLUiwn8ziB5UD3ravAo0gskGA_GkQIeCMpjFBDYtvTUWayImF14OQqKgI4jtGCanLlhtIZb7VON5q2Q6274Bpwx8IMjPah-SsBa3mQklwv4bfKa3H0TLT69zaunPmCkawDkqNUAYy5duZc3UU883FI93lGu6uUUuYABea0JZZD4iyrPwVQ3XsBBnh87xpSCorCyFioesq7gGYS16KlEQL6QJLH0jxxPldoDN5a5GOTKQsOwDfbsnmdUT52Z84Mjbsq3lqitOp1PtV6aO_sZ1i33uEBt8lUWFmD_6OMkYFfapRdtj_d-aH-XHMWOTx3yKy_I1KETnFdRBKcWTrE97fbPZthzyMDXpLFc7d67sD0yr8IkJH8l2_soJvmNJHIWlomMIzb6vax967sAOp0IQsSDr-7g8E4DQFosJ3TOmmVi7iOBdJVtn84MGE2f9CinXMFPOX_HTCirpRseckKOZuQ1QzKdfMj3r-QprCB3Zc2LsuWLWgiyCXypt2aPNQFZPLAWAAc6m-ktcpTPUvDeGiOThtt6VoY7s2KoklEY8o4a4i1xxxfViygf0dDrr4hbl2ckmMhvN8NSKxF0bzKnayXTbmuvoOnNs78de5VgrkNgOLhbaLqb0tqkoJ7_muxzHRxvziutHdXs9XNzJSQLQ_UWix9-7AWsjVdOnzIAipnABurjoB9yE69wLwqKEmBrmwnJG4czQVKPKNbPPlEkKzPhM6tn8nXt8LjRfyzZ1kqSQYrU4fyXVe8g59MqNh0nbks_G1PcYqLUnEIM1DFuZDbAUhEM0mEW1BRF2-tWKzchhfeyu8I-n2BMXcFQt2hCfmPt2beK0B0uMpFyCEYyB__ufeCP1N9Zm1IWgnNP9OYLZX0kK_L0_1KyeCsfQ=w1672-h2230-s-no?authuser=0)

![Enclosure #2-Closed](https://lh3.googleusercontent.com/pw/AP1GczMpLKERjnoPLevQ__oVwdESQxxHbUX0_p7_L-VmiWjc0sZNq9eBSq8hEJM3mECx5ApR6uUQ05zF_PtJ8uXFq-DVp50jmig2oXZRb9-Gs7kuCbmlfKj5jHoYz8WsvhD2MXTrP81YspAabOFOMzO0DCk-AIESHWezsv9mZM4mlgWeXIfhrFQzcTqwnW3-7F-9RdVlZUHVuFAL1Wga5rplGaeoOkZl3CoajR1TAMv88Xp2vdKA-e5M7oLc9iDp5GdzC-GncWU2aEKSQYwGY-PDqj5xab0-SZTp5OHXR1KW3PCfRG25u9AnSCIdNPhvcUIgDvaYXe7gcTVf3VEdn9E9lQNalBujfowD-kzlVXWKFut38sFMnx1Epzl-TPkNxlmOw_PlCxogvAHTN2HHNLHSGuqOUHbFJqWY3OcVNOYXtABPD_YrdRIJ7HyuUkvdEDeFsaTAMHOs9--zFHXnp9ofXgXNLM8t863MzG98cpXzY77wwDvAkBPQmszunWpzMAFgfDcPStY6RKWdOZjF0nMAYI9cQTvngEUKSlbdPer2IKjSPK0njwM5nyIC2F4_ZKC1dSmklHwgULMD9ira3uNoMgR6bYUBvxGodM9O09r0UrZNwhDO52w0AcP-3g7tVILaC2oKysdBv2U92sUDmx3rlm4pefhsOcb0Hn977K0ZBwx5cF8204hf-o4JRd_ohEt2IcX3UAAhMebYr-triaKvhzm_x7jwfCOcItxSc-rA4Vz-n8FVMgE2YyEuC70dlQhXKGXNtSXrZzrQevVTpXTVWg6Vm_9b9W1h6KkXcjT799UBHn88s3K-hW51maFrUfA-b1rjG2rWigiGrA-gtOIpBZyOGe_sMH4TjDBXMZ1g_iJizqSwdSiRdXoHRLqkjRWpUaGwWMsgy4OLvFwB9T01VHe4Z6fssS9eS-WzMrlDf24eeityo588MdQWfA=w2974-h2230-s-no?authuser=0)

## **Testing and Observations**

### *v.1.0* 
→ The internal pocket within the enclosure did not have enough clearance for the keychain to fit. 
>> I did not print the lid of v.1.0 because of the keychain not being able to fit inside the pocket. The design intent behind the enclosure was that the keychain must fit, and the snap fit mechanism must work. 

### *v.1.1*
→ I offsetted the sketch for the internal pocket by .2mm providing enough clearance for the print to fit. 

→ The internal corners of the lid needed to be filleted in order for the lid to fit the body of v.1.1. 
>> Since the corners of the lid were sharper than the inner corners of the body of the enclosure, the lid was unable to fit inside the box. Despite that issue, however, the lid was able to fit the body of v.1.0. 

→ While printing the lid, I noticed that the top surface layers fused with lower layers at an angle - indicating excessive material flow or the extruder at a higher temperature than necessary - rather than a geometric interference. 

### *v.1.2* 
→ For this model, I designed a new lid from scratch, as I found that editing the previous lid to be too reduce timeline dependency complexity and improve parametric clarity. 

→ Boundary sketch of the inner feature of the lid was offsetted by .6mm to provide clearance between the inner part of the lid and the body of the enclosure. Testing showed that there is no significant consequence with respect to the snap-fit engagement by offsetting it .4mm more than recommended, as no visible deformation was observed during short-term testing. 

→ Lid was shelled with a thickness of 1.6mm. 

→ Shared the same issue as the lid of v.1.1 while extruded. While troubleshooting this issue I discovered that the top surface flow rate was too high for the extruder.

## **Manufacturing Notes**
→ Printed in PLA on Neptune 4. 

→ Layer fusion at lid interface traced to excessive top surface flow rate.

→ Geometry was sound; issue was slicer/material tuning rather than CAD error.

## **Next Steps**
→ Reprint lid with corrected top surface flow rate (100% → 95%).

→ Convert lid and body into separate components for assembly validation.

→ Apply snap-fit learnings to a larger functional enclosure.
