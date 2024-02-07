## Relfection
### How did you determine your "days of use" metric ? 
I first calculated the power consumption of component for both sensing and display device in each cycle, integrating active, idle, and sleep states. With this information, I can estimated the total energy used per day. This daily consumption was then divided by the battery's total capacity to get the approximately device's operational days.

### What do you think is the optimum size for the battery in your device ?
There are some criteria that should be considered before deciding the battery size. The first thing is the convenient size for usage. The battery size should not larger than the PCB, which is 6 cm* 8cm, or it is hard to accommodate into the enclosure. The other thing is the battery capacity. It should at least support 6-day usage without being charged, so the size should still large enough to support this duration.

### What hardware/software/cost/effort tradeoffs could you make to improve the user experience ?
To increase the battery life, the device should be under the sleep mode for the most of the time, which will influence the user experience. From the software aspect, I can refine algorithms for efficiency, such as adjustable power-saving modes. For the hardware, selecting energy-efficient components will help to reduce the power consumption and make the life longer.
