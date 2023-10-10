Why this topic matters as it relates to what you are studying in this module:

This is important to be aware of hardware hacking as well as software hacking. Leaking sensitive information can impose a serious threat to the privacy of personal information, military, and businesses. Therefore, companies and governments take this matter very seriously and there is a high demand for cyber security.

How is a hardware hack different than a software hack?

Hardware Hack: In a hardware hack, a malicious actor manipulates or introduces compromised hardware components into a device or system during the manufacturing process. In the article's context, it was alleged that tiny, malicious microchips were surreptitiously added to server motherboards during their production in China.

Software Hack: A software hack, on the other hand, involves exploiting vulnerabilities in the software layer of a system. This can include exploiting software bugs, vulnerabilities, or weaknesses in operating systems, applications, or network services. Software hacks typically do not require physical access to the hardware itself.

Source (according to the article): https://chat.openai.com/c/86b290ae-8067-4db6-b9a8-04099b148084 Links to an external site.

What are the two ways for spies to alter a computer’s hardware?

Hardware Implants: Spies or hackers may physically insert small hardware devices, often referred to as "implants" or "bugs," into a computer's motherboard or other components. These implants can be used to intercept data, manipulate the system's functions, or create backdoors for remote access. These hardware modifications are typically difficult to detect and can provide unauthorized access or control over the compromised system.

Supply Chain Attacks: Another method is to compromise the hardware during the manufacturing or supply chain process. In this scenario, attackers may infiltrate the production process of computer components, such as microchips or motherboards, and insert malicious components or modify existing ones. This can allow them to compromise multiple systems at once since the compromised components are distributed widely.

Source (according to the article): https://chat.openai.com/c/0aba56e5-b102-4fbc-a52b-3760aa731a8c Links to an external site.

Explain how the hack worked.

The chips on Elemental servers were designed to be as inconspicuous as possible, according to one person who saw a detailed report prepared for Amazon by its third-party security contractor, as well as a second person who saw digital photos and X-ray images of the chips incorporated into a later report prepared by Amazon’s security team. Gray or off-white in color, they looked more like signal conditioning couplers, another common motherboard component, than microchips, and so they were unlikely to be detectable without specialized equipment. Depending on the board model, the chips varied slightly in size, suggesting that the attackers had supplied different factories with different batches.

Officials familiar with the investigation say the primary role of implants such as these is to open doors that other attackers can go through. “Hardware attacks are about access,” as one former senior official puts it. In simplified terms, the implants on Supermicro hardware manipulated the core operating instructions that tell the server what to do as data move across a motherboard, two people familiar with the chips’ operation say. This happened at a crucial moment, as small bits of the operating system were being stored in the board’s temporary memory en route to the server’s central processor, the CPU. The implant was placed on the board in a way that allowed it to effectively edit this information queue, injecting its own code or altering the order of the instructions the CPU was meant to follow. Deviously small changes could create disastrous effects.

Since the implants were small, the amount of code they contained was small as well. But they were capable of doing two very important things: telling the device to communicate with one of several anonymous computers elsewhere on the internet that were loaded with more complex code; and preparing the device’s operating system to accept this new code. The illicit chips could do all this because they were connected to the baseboard management controller, a kind of superchip that administrators use to remotely log in to problematic servers, giving them access to the most sensitive code even on machines that have crashed or are turned off.

This system could let the attackers alter how the device functioned, line by line, however they wanted, leaving no one the wiser. To understand the power that would give them, take this hypothetical example: Somewhere in the Linux operating system, which runs in many servers, is code that authorizes a user by verifying a typed password against a stored encrypted one. An implanted chip can alter part of that code so the server won’t check for a password—and presto! A secure machine is open to any and all users. A chip can also steal encryption keys for secure communications, block security updates that would neutralize the attack, and open up new pathways to the internet. Should some anomaly be noticed, it would likely be cast as an unexplained oddity. “The hardware opens whatever door it wants,” says Joe FitzPatrick, founder of Hardware Security Resources LLC, a company that trains cybersecurity professionals in hardware hacking techniques.

Source: https://web.archive.org/web/20190330085155/https://www.bloomberg.com/news/features/2018-10-04/the-big-hack-how-china-used-a-tiny-chip-to-infiltrate-america-s-top-companies Links to an external site.

How were investigators able to trace the chips back to the source?

Forensic Analysis: Investigators conducted a thorough examination of the compromised hardware. They physically examined the affected servers and motherboards to find the tiny chips that were allegedly inserted into them.
Cooperation from Affected Companies: Some of the companies that discovered the malicious hardware cooperated with investigators. They shared information about the compromised servers and provided access to the hardware for examination.
Supply Chain Investigations: The investigation also involved looking into the supply chain of the affected hardware. This included tracing the manufacturing and distribution of the compromised motherboards and chips.
Intelligence Gathering: Intelligence agencies may have been involved in the investigation, providing additional resources and expertise. They might have used their own sources and methods to gather information about the origin of the malicious chips.
Technical Expertise: Investigators likely had access to technical experts who could analyze the chips and their behavior. This would have involved reverse engineering the chips to understand their purpose and functionality.
Cooperation with Other Agencies: International cooperation might have played a role. U.S. agencies could have worked with foreign intelligence and law enforcement agencies to gather additional information and intelligence.
Source (according to the article):  https://chat.openai.com/c/0aba56e5-b102-4fbc-a52b-3760aa731a8c Links to an external site.

 

## Things I want to know more about:

Hardware hacking

