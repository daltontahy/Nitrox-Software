# Operating System Information

Nirox utilizes multiple operating systems over many different machines to effectively manage various tasks concurrently, all working together to create a unique ecosystem. Below is a detailed description of how each operating system is utilized.

## Linux Based Systems

The workers utilize two Linux-based operating systems: **HiveOS** and **NHOS**. It is crucial for the workers to have maximum efficiency, making a lightweight OS ideal.

### HiveOS

Dedicated workers with 6-8x of the same card usually use HiveOS because its deployment of a single algorithm and hefty overclocks is the most ideal and efficient in my experience. Mining directly to a pool with no middle man is the gold standard, and no one does it better than Hive. Additionally, the minimum hardware requirements are near 0, and I can optimize budgeting by using very old CPUs and RAM on these machines. In the end, HiveOS is best when you have many similar GPUs on lower spec base components.

ASICs also utilize HiveOS for their onboard ASIC-OS, as it is very lightweight, and the web interface is very easy to access/one of the most secure ASIC operating systems available. Security is a significant concern with ASIC machines as hijacking becomes more prevalent and power draw more expensive.

### NHOS

The other OS my workers use is NHOS. While not as lightweight, cost-effective, or efficient as HiveOS, they do have a few gold bargaining chips: profit switching and mixed machines. This means that I can mix virtually any GPU and run different algorithms on each one. It's not efficient to get into a habit of using this OS due to their third-party platform, high fees, and less-than-standard overclocks, but for the odd mixed rig, it does the job pretty well. When ETH went POS, the profit switching on this OS saved a lot of downtime.


