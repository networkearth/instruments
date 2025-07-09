# Microcontroller Unit (MCU)

Digital radio communication is fantastically interesting and like many fascinating things it is pretty darn complicated. So isn't it wonderful that ST has chips and software that come with everything you need to manage the communication! All at low power too.

- [STM32WL3 Line](https://www.st.com/content/st_com/en/campaigns/stm32wl3-comprehensive-ecosystem-long-range-iot-connectivity-z13.html?ecmp=tt45044_gl_ps_jun2025&aw_kw=stm32%20wireless%20mcus&aw_m=e&aw_c=22032657977&aw_tg=aud-2173644794635:kwd-1457438729886&aw_gclid=CjwKCAjwprjDBhBTEiwA1m1d0oSMdFI7UCsje4d8FfuBJjFW-EInW3rT8UjZ1rWWHqVwe16UJWC6EBoCuuIQAvD_BwE&gad_source=1&gad_campaignid=22032657977&gbraid=0AAAAADmP1XT8bcmLf6zb8UZTWm7Z2yrFH&gclid=CjwKCAjwprjDBhBTEiwA1m1d0oSMdFI7UCsje4d8FfuBJjFW-EInW3rT8UjZ1rWWHqVwe16UJWC6EBoCuuIQAvD_BwE)
- [Kineis Constellation](https://blog.st.com/kineis/) (works with STM32's)
- [Kineis Stack](https://www.st.com/content/st_com/en/partner/partner-program/partnerpage/Kineis.html)
- [Reference Design](https://kineis.com/en/kineis-stack-for-a-quick-integration-2/)
- [and it's part of the CLS (Argos) ecosystem!](https://telemetry.groupcls.com/argos-solutions/argos-products/modems/)

All in all pretty sweet. What we need is one that's integrated with I2C and SPI for communication with sensors and memory as well. The [STM32WL33K8V6](https://www.digikey.com/en/products/detail/stmicroelectronics/STM32WL33K8V6/22519707) fits the bill pretty well. This uses a **32-VFQFN Exposed Pad** footprint so we can reuse this development board for anything with this footprint. 