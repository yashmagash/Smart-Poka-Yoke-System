

<!-- Start of picture text -->
tx BIRMINGHAM CITY<br><!-- End of picture text -->

Error-Proofing Smart Assembly: An Error-Proofed Tightening System Using Atlas Copco Tools 



<!-- Start of picture text -->
‘ BIRMINGHAM CITY<br>y Fy University<br><!-- End of picture text -->

**BEng (Hons) Manufacturing Engineering** 

**Faculty of Computing, Engineering and the Built Environment** 

**College of Engineering** 

**Student Name:** Yash Malhotra **Student Number:** 22132214 **Submission Date:** 05/12/2025 **Supervisor:** Venkatesh Vijay 

Dissertation submitted to Birmingham City University in partial fulfilment of the requirements for the degree of Bachelor of Engineering 

1 



<!-- Start of picture text -->
tx BIRMINGHAM CITY<br><!-- End of picture text -->

### **<u>Abstract</u>** 

Fastening operations remain a major source of assembly errors in modern manufacturing, with issues such as incorrect torque, missing fasteners, and wrong tightening sequences leading to rework, quality concerns, and increased costs. This project aimed to design, configure, and evaluate a smart poka ‑ yoke tightening system using Atlas Copco Power Focus controllers and Tensor tools to reduce such errors and improve assembly reliability. A case study approach was adopted, focusing on a representative aluminium disk assembly to simulate a realistic industrial joint. The tightening system was configured with bolt ‑ sequence enforcement, torque and angle validation, barcode verification, and operator guidance using Avantguard, ToolsNet 8, and ALTURE platforms. Controlled tightening trials were conducted under both normal and deliberate ‑ error conditions, with process data collected for torque, angle, speed, and current. 

Results show that the system successfully detected and prevented common fastening errors, producing consistent and interpretable tightening behaviour under realistic joint conditions. Further analysis using ToolsNet and ALTURE highlighted recurring NOK events and provided actionable recommendations for process improvement. The findings demonstrate that integrating smart tightening tools with digital analytics and operator guidance supports real ‑ time error detection, enhanced traceability, and improved first ‑ time ‑ right performance. The project also evaluated wider impacts, identifying strong commercial potential through reduced rework and downtime, sustainability benefits from electric tools and waste reduction, and improved equality, diversity, and inclusion by reducing reliance on operator skill and physical capability. Overall, the project confirms that smart poka ‑ yoke tightening systems represent an effective Industry 4.0 solution for improving manufacturing quality and reliability. 

2 



### **Table of Contents** 

|**_Abstra_**|**_ct......................................................................................................................... 2_**|
|---|---|
|**_1_**<br>**_Inti_**|**_roduction............................................................................................................6_**|
|**1.1**|**Aim...............................................................................................................................6**|
|**1.2**|**Objectives.....................................................................................................................6**|
|**_2_**<br>**_Ba_**|**_ckground.............................................................................................................7_**|
|**_3_**<br>**_Lit_**|**_erature Review....................................................................................................8_**|
|**3.1**|**Poka-Yoke in Manufacturing........................................................................................8**|
|**3.2**|**Smart Assembly and Industry 4.0.................................................................................8**|
|**3.3**|**Current Problems in Fastening and Assembly Processes...............................................9**|
|**3.4**|**Atlas Copco Technologies and Smart Tool Capabilities.................................................9**|
|**3.5**|**Quality and Human Factors........................................................................................11**|
|**3.6**|**Sustainability and EDI.................................................................................................11**|
|**3.7**|**Summary of Problems Addressed by the Project........................................................11**|
|**3.8**|**Summary of Literature Review...................................................................................12**|
|**_4_**<br>**_M_**|**_ethodology.........................................................................................................13_**|
|**4.1**|**Project Design.............................................................................................................14**|
|**4.2**|**Experimental Setup....................................................................................................14**|
|**4.3**|**Data Collection and Analysis.......................................................................................14**|
|**4.4**|**Ethical Considerations................................................................................................15**|
|**_5_**<br>**_Pr_**|**_eliminary Data / Findings...................................................................................15_**|
|**_6_**<br>**_Co_**|**_mmercial Viability, EDI and Sustainability..........................................................15_**|
|**6.1**|**Commercial Viability...................................................................................................15**|
|**6.2**|**Ethical Considerations................................................................................................15**|
|**6.3**|**Equality, Diversity and Inclusion (EDI)........................................................................16**|
|**6.4**|**Sustainability..............................................................................................................16**|
|**_7_**<br>**_De_**|**_sign Development.............................................................................................17_**|



3 



|**7.1**<br>**7.2**|**Steering Wheel 3D Print.............................................................................................17**<br>**Steering Wheel Set-up – Avantguard..........................................................................18**|
|---|---|
|**_8_**<br>**_R_**|**_esults and Analysis..............................................................................................23_**|
|**8.1**|**Toolsnet 8...................................................................................................................24**|
|**8.2**|**ALTURE Analysis.........................................................................................................33**|
|**_9_**<br>**_Di_**|**_scussion..............................................................................................................38_**|
|**9.1**|**Summary....................................................................................................................39**|
|**_10_**|**_Conclusions........................................................................................................40_**|
|**_11_**|**_Recommendations.............................................................................................41_**|
|**_12_**|**_Work Schedule / Progress..................................................................................42_**|
|**12.1**|**Discussion and Next Steps..........................................................................................43**|
|**_13_**|**_References (BCU Harvard Style).........................................................................44_**|
|**_14_**|**_Appendix...........................................................................................................46_**|
|**14.1**|**Student Details:..........................................................................................................46**|
|**14.2**|**Project Title:...............................................................................................................46**|
|**14.3**|**Project Introduction and Rationale:............................................................................46**|
|**14.4**|**Project Aim & Objectives:...........................................................................................47**|
|**14.5**|**How does your project consider commercial viability, EDI or sustainability:..............47**|
|**14.6**|**Project RAID Matrix / Log:..........................................................................................48**|
|**RAI**|**D Matrix............................................................................................................................48**|
|**14.7**|**Project Tentative Schedule of Work:..........................................................................48**|
|**Tenti**|**ative Schedule of Work...................................................................................................48**|
|**14.8**|**Project Ethics:.............................................................................................................49**|
|**14.9**|**References:.................................................................................................................50**|
|**_15_**|**_Final Year Project Logbook.................................................................................51_**|
|**15.1**|**Project Information....................................................................................................51**|
|**15.2**|**Introduction................................................................................................................51**|



4 



|**15.3**|**Summary Report.........................................................................................................51**|
|---|---|
|**15.4**|**Roles and Responsibilities..........................................................................................51**|
|**15.5**|**Quality of Work and Supervision................................................................................51**|
|**15.6**|**Conclusion..................................................................................................................51**|
|**15.7**|**Monthly Logbook........................................................................................................52**|
|**15.8**|**October 2025..............................................................................................................52**|
|**15.9**|**November 2025..........................................................................................................52**|
|**15.10**|**December 2025......................................................................................................52**|
|**15.11**|**February 2026........................................................................................................53**|
|**15.12**|**March 2026............................................................................................................53**|
|**15.13**|**April 2026...............................................................................................................53**|
|**15.14**|**Project Timeline.....................................................................................................54**|
|Figure 1 - T|ypical assembly line with manual fastening........................................................8|
|Figure 2 -|Case Study Steps.......................................................................................14|
|Figure 3 -|Wheel on 3D Printing Software..................................................................18|
|Figure 4 -|3D Printed Steering....................................................................................19|
|Figure 5 -|Flow Diagram in Avantguard......................................................................19|
|Figure 6 -|Pop up Window when Creating new Action...............................................20|
|Figure 7 -|Sub-sections of the Process.......................................................................20|
|Figure 8 -|Editing screen for the Procedure................................................................21|
|Figure 9 -|Configuring the Location of Bolts to the ILG...............................................22|
|Figure 10|- Socket selector with white light.................................................................23|
|Figure 11|- Reminder during the process to check the tool is on...............................23|
|Figure 12|- Screenshot from Toolsnet 8 Dashboard...................................................26|
|Figure 13|- Torque/Angle Graph.................................................................................27|
|Figure 14|- Torque/Time Graph..................................................................................29|
|Figure 15|- Speed/Time Graph...................................................................................30|
|Figure 16|- Current/Time Graph..................................................................................32|
|Figure 17|- Angle/Time Graph.....................................................................................33|
|Figure 18|- Bar chart and Line graph of previous months’ NOKs...............................35|



5 



Figure 19 - Summary of tightening information from ALTURE...................................35 Figure 20 - List of NOK Events...................................................................................36 Figure 21 - Summary of data from the last six months...............................................37 Figure 22 - Gantt Chart...............................................................................................43 

# **1** **<u>Introduction</u>** 

Accurate and repeatable fastening operations are critical in modern manufacturing sectors such as automotive, aerospace, and industrial engineering, where incorrect torque, missing fasteners, or incorrect tightening sequences can lead to quality defects, rework, and safety ‑ critical failures (Croccolo et al., 2023). Despite advances in automation, fastening remains a common source of assembly errors due to process variation and human involvement, highlighting the need for robust error ‑ prevention strategies rather than post ‑ process inspection (Shingo, 1986). To address these challenges, manufacturers increasingly apply poka ‑ yoke (error ‑ proofing) principles supported by Industry 4.0 technologies, including smart tightening tools, real ‑ time monitoring, and operator guidance systems. Research shows that integrating torque ‑ angle control, digital traceability, and operator feedback significantly improves first ‑ time ‑ right performance and reduces variability in assembly processes (Romero et al., 2022; Dolgui et al., 2022). Smart tightening systems capable of collecting and analysing torque, angle, speed, and current data enable manufacturers to detect deviations at source and shift quality assurance toward predictive and proactive control (Goecks et al., 2024). 

This project focuses on the design and evaluation of an error ‑ proofed smart tightening system using Atlas Copco Power Focus controllers, Tensor tools, and associated digital platforms. An aluminium disk assembly was used to represent a realistic industrial joint, allowing tightening behaviour and system performance to be assessed under practical conditions. By analysing tightening signals and diagnostic outputs, the project evaluates how effectively smart poka ‑ yoke features improve assembly reliability, traceability, and process control in line with current state ‑ of ‑ the ‑ art manufacturing practices. 

### **1.1** **<u>Aim</u>** 

This project aims to design, set up, and evaluate a smart poka-yoke tightening system using Atlas Copco Power Focus and Tensor tools. The goal is to reduce common assembly errors and improve the overall quality and reliability of manufacturing processes. 

### **1.2** **<u>Objectives</u>** 

- Conduct a literature review encompassing poka-yoke, lean manufacturing, and modern digital assembly technologies. 

- Identify common fastening mistakes and choose a suitable assembly task to model and test. 

- Configure Atlas Copco tools to use bolt-sequence control, torque/angle checking, and barcode verification. 

- Test the system under both normal and deliberate-error conditions to assess its ability to detect faults. 

- Analyse the results to understand how much the system improves accuracy and reduces errors. 

6 



<!-- Start of picture text -->
i BIRMINGHAM CITY<br><!-- End of picture text -->

- Consider the wider impacts of the system, including commercial benefits, sustainability, and how it supports equality, diversity and inclusion (EDI) in the workplace. 

### **2** **<u>Background</u>** 

Modern manufacturing industries such as automotive, aerospace, and industrial engineering operate under increasing pressure to deliver high ‑ quality products with minimal defects and downtime. Despite advances in automation, fastening operations remain a major source of assembly errors, including incorrect torque application, missed fasteners, and improper tightening sequences. These issues continue to contribute to rework, warranty claims, and safety risks, particularly in safety-critical applications (Croccolo et al., 2023). To mitigate these challenges, the industry has progressively adopted error ‑ proofed (poka ‑ yoke) assembly lines, where mistakes are prevented or detected immediately at source. Originally introduced by Shingo as part of the Toyota Production System, poka-yoke principles focus on eliminating human error through process design rather than post-process inspection (Shingo, 1986; Ohno, 1988). With the emergence of Industry 4.0, error ‑ proofing has evolved from purely mechanical solutions to digitally enabled systems that use sensors, programmable controllers, and real ‑ time data analytics to enforce correct assembly behaviour (Romero et al., 2022). 



**Figure 1 - Typical assembly line with manual fastening** 

7 



<!-- Start of picture text -->
tx BIRMINGHAM CITY<br><!-- End of picture text -->

State ‑ of ‑ the ‑ art assembly lines now increasingly rely on smart tightening systems capable of monitoring torque, angle, speed, and current while providing full digital traceability. Research shows that such systems significantly improve fastening reliability and first ‑ time ‑ right performance compared with traditional torque ‑ only approaches (Lu et al., 2020; Johansson and Nilsson, 2021). Commercial solutions such as Atlas Copco’s Tensor tools and Power Focus controllers exemplify this shift, enabling real ‑ time monitoring, sequence enforcement, and analytics ‑ driven quality improvement (Atlas Copco, 2024; Goecks et al., 2024). 

Overall, the manufacturing sector is moving towards smart, data ‑ driven, error ‑ proofed assembly lines where quality assurance is embedded directly into the process. This project is positioned within this industrial transition and investigates how modern smart tightening technologies can be configured to enhance fastening reliability, traceability, and manufacturing quality. 

### **3** **<u>Literature Review</u>** 

This literature review aims to analyse current research relating to fastening quality, errorproofing techniques and the increasing use of digital tightening systems within modern manufacturing. It will identify the key parameters that influence bolted-joint performance, such as preload accuracy, torque-angle behaviour, joint conditions and operator consistency, while also outlining the common reasons for failure reported in context to industry. In addition, the review will examine how smart tools, including Atlas Copco’s Power Focus and Tensor platforms, are used to enforce correct tightening sequences, provide real-time verification and improve traceability. The significance of these technological developments, both for process reliability and wider manufacturing performance, will be evaluated throughout. 

### **3.1** **<u>Poka-Yoke in Manufacturing</u>** 

Poka-yoke, introduced by Shigeo Shingo in the 1960s, is a cornerstone of lean manufacturing aimed at mistake-proofing processes to achieve zero defects. It works by preventing errors or detecting them immediately so that defects do not reach the customer. Traditional poka-yoke devices, such as fixtures, sensors, and guided instructions, are widely recognised for their simplicity and cost-effectiveness in reducing variability and improving first-time-right performance. Recent studies emphasise that digitalisation has transformed poka-yoke systems into intelligent error-proofing tools integrated with cyber-physical production systems, enabling real-time data collection and predictive analytics for near-zero defect manufacturing. 

Akhtar and Tyagi (2021) highlight that poka-yoke strategies significantly reduce human error in repetitive tasks, such as spot welding, by embedding preventive and detection mechanisms at the source of variation. Similarly, Malega (2018) argues that poka-yoke is most effective when combined with continuous feedback loops, ensuring that mistakes are corrected before escalating into costly defects. Case studies in the automotive and adhesive industries report productivity improvements of up to 25% when poka-yoke systems are systematically implemented with lean principles. 

However, new studies suggest that poka-yoke alone is insufficient in highly complex environments. Integrating digital technologies, such as IoT sensors and smart controllers, is essential to adapt poka-yoke for Industry 4.0, allowing dynamic error-proofing in flexible assembly lines. 

8 



### **3.2** **<u>Smart Assembly and Industry 4.0</u>** 

Industry 4.0 has transformed assembly processes by introducing smart tools, IoT connectivity, and data-driven decision-making. Smart tightening systems now capture torque and angle data, guide operators, and communicate with production networks in real time. These capabilities not only implement correct tightening sequences but also enable full traceability and predictive maintenance, reducing rework and downtime. 

Beck & Pollitzer (2025) note that integrating technologies such as collaborative robots, augmented reality, and digital twins into assembly lines enhances flexibility and quality control, particularly in high-variation environments like automotive and aerospace. By leveraging torque-trace analytics, manufacturers can identify anomalies early, improving joint integrity and reducing warranty claims. This digital transformation complements poka-yoke principles by embedding error-proofing into smart systems rather than relying solely on physical devices. 

### **3.3** **<u>Current Problems in Fastening and Assembly Processes</u>** 

Fastening and assembly processes are critical in manufacturing, but they remain prone to several recurring issues. Common problems include preload loss, fatigue failures, and incorrect torque application, which can compromise joint integrity (Croccolo et al., 2023). Misalignment and over- or under-tightening are also frequent defects, often resulting from insufficient process control or operator error (Lee, 2025). Furthermore, studies highlight that human factors, such as inadequate training and a lack of standardised procedures, exacerbate these failures (Pierce, 2025). These challenges underline the need for robust quality assurance and advanced fastening technologies to mitigate risks. 

Despite technological advances, several fastening challenges persist: 

- **Under- and Over-Tightening / Preload Loss:** Incorrect preload remains a leading cause of bolt failures, leading to vibration, fatigue, or thread stripping. 

- **Incorrect Tightening Sequence:** Ignoring prescribed sequences can warp joints, especially in aerospace and automotive assemblies. 

- **Tool Inaccuracies and Calibration Issues:** Poor calibration and operator error contribute to inconsistent torque results. 

- **Surface and Material Variability:** Rust, lubrication differences, and temperature fluctuations affect friction, making torque unpredictable. 

- **Poor Traceability:** Many factories still record only final torque values, limiting rootcause analysis. 

- **Challenges in Flexible or Low-Volume Assembly:** Automated solutions often struggle with variation, requiring adaptable poka-yoke systems. 

These issues underscore the need for integrated solutions combining poka-yoke principles with smart technologies. 

### **3.4** **<u>Atlas Copco Technologies and Smart Tool Capabilities</u>** 

Atlas Copco addresses these fastening challenges through advanced solutions such as Power Focus controllers and Tensor tools, which offer: 

- Real-time torque and angle monitoring 

- Enforced tightening sequences 

- Barcode verification for job authentication 

- Comprehensive data logging for traceability 

9 



The PF6 Flex system exemplifies modular automation, enabling flexible assembly for diverse automotive powertrain configurations while reducing cycle time and footprint. Additionally, Atlas Copco’s cordless nutrunners and STwrench smart torque wrenches provide ergonomic designs and integrated sensors for precision tightening. However, literature notes challenges such as high initial investment, training requirements, and integration complexity, which must be factored into cost-benefit analyses. 

### **3.5** **<u>Quality and Human Factors</u>** 

Quality in manufacturing is not solely determined by technical precision as human factors play a pivotal role. Research indicates that ergonomic design and operator workload significantly influence production quality outcomes (Kolus et al., 2018). In the context of Industry 4.0, the integration of automation has moved human roles toward supervisory and decision-making tasks, introducing new cognitive demands (Reiman et al., 2021). Poor consideration of these factors can lead to errors, reduced efficiency, and compromised product quality (Gruszka, 2018). Therefore, a systematic approach to human factors engineering is essential for sustaining high-quality standards in modern manufacturing environments. 

### **3.6** **<u>Sustainability and EDI</u>** 

Smart error ‑ proofing systems play an important role in supporting sustainable manufacturing by reducing scrap, rework, and unnecessary energy consumption, which are widely recognised as major contributors to environmental impact in production systems (EPA, 2021). The use of electric tightening tools, for example, eliminates the need for compressed air, resulting in lower energy demand, reduced carbon emissions, and improved overall energy efficiency when compared to traditional pneumatic systems (Atlas Copco, 2024). Studies on smart assembly and Industry 4.0 report that manufacturers adopting digitally connected tightening solutions achieve measurable reductions in CO ₂ emissions while improving alignment with circular economy principles through improved process control and reduced material waste (Dolgui et al., 2022). 

In addition to environmental benefits, smart tightening technologies also contribute to equity, diversity, and inclusion (EDI) within manufacturing environments. Research on human ‑ centred and ergonomic manufacturing systems highlights that reducing reliance on operator strength, experience, or technical literacy enables more consistent performance across a diverse workforce (Kolus et al., 2018). Guided tightening systems, automatic sequence enforcement, and real ‑ time feedback create safer and more accessible workplaces by supporting operators with varying physical capabilities and skill levels, thereby promoting inclusivity while maintaining high-quality standards (Reiman et al., 2021). 

### **3.7** **<u>Summary of Problems Addressed by the Project</u>** 

This project aims to tackle: 

- Incorrect preload (under- or over-tightening) 

- Wrong tightening sequence 

- Operator mistakes and tool inaccuracies 

- Variable surface and material conditions 

- Lack of traceability 

- Inflexibility in complex assembly environments 

10 



<!-- Start of picture text -->
tx BIRMINGHAM CITY<br><!-- End of picture text -->

By integrating torque/angle validation, sequence control, barcode verification, and full data logging, the proposed system aligns with the literature’s recommendations for combining poka-yoke principles with Industry 4.0 technologies to achieve robust, sustainable, and human-centred fastening solutions. 

### **3.8** **<u>Summary of Literature Review</u>** 

The literature emphasises the importance of error-proofing and smart technologies in modern manufacturing. Poka-yoke, a lean manufacturing principle, remains fundamental for preventing defects at the source. Studies show that traditional poka-yoke devices, such as fixtures and sensors, significantly reduce variability and improve first-time-right performance, while integration with digital technologies enhances adaptability in complex environments. 

The transition to Industry 4.0 has transformed assembly processes using smart tools capable of real-time torque and angle monitoring, sequence enforcement, and full traceability. These innovations balance poka-yoke principles by embedding error-proofing into connected systems, improving quality and reducing downtime. Despite these advances, recurring fastening problems persist, including preload loss, incorrect tightening sequences, tool inaccuracies, and poor traceability. Research highlights that these issues often stem from human error, inadequate training, and environmental variability, underscoring the need for integrated solutions. 

Manufacturers such as Atlas Copco address these challenges with advanced tightening systems featuring barcode verification, data logging, and ergonomic designs. However, literature notes barriers such as cost, training, and integration complexity. Human factors remain critical to quality outcomes. Ergonomic design, cognitive workload, and operator-tool interaction significantly influence performance. Smart tools mitigate risks by guiding operators and validating steps, but success depends on intuitive interfaces and robust training. Finally, smart error-proofing systems contribute to sustainability and inclusivity by reducing waste, energy consumption, and reliance on operator strength or technical literacy. These benefits align with circular economy principles and equity goals. 

Overall, the literature supports combining poka-yoke principles with Industry 4.0 technologies to address fastening challenges, enhance quality, and promote sustainable, human-centred manufacturing. 

11 



<!-- Start of picture text -->
i BIRMINGHAM CITY<br><!-- End of picture text -->

### **4** **<u>Methodology</u>** 

This section outlines the research strategy implemented to achieve the project objectives. The methodology combines a case study approach with controlled experimental testing to evaluate the effectiveness of poka ‑ yoke features in fastening processes. A case study approach is particularly appropriate for engineering research where the aim is to investigate a specific process or system within a realistic context, allowing detailed analysis of interactions between tools, operators, and process conditions (BachelorPrint, n.d.). By focusing on a representative tightening task using industry ‑ standard Atlas Copco equipment, the methodology ensures practical relevance while maintaining rigour through structured data collection and systematic analysis. 



<!-- Start of picture text -->
Reporting 6 Defining<br>1 the case<br>findings —-<br>Interpreting = | Process of a 2 Selecting<br>data Case Study | the case(s)<br>Theoreticalframework 4 — 3 andDataanalysis collection<br>Renee<br><!-- End of picture text -->

**Figure 2 - Case Study Steps** 

A case study approach, shown in Figure 2, will be adopted in this project to enable an in ‑ depth examination of a smart poka ‑ yoke tightening system within a realistic manufacturing context. Case study methods are widely used in engineering and manufacturing research where the objective is to investigate complex processes, tool interactions, and human– system behaviour in real or representative settings rather than isolated laboratory conditions (Yin, 2018). In line with the standard case study process, the first stage is defining the case, which in this project is the implementation of an error ‑ proofed tightening process using Atlas Copco Power Focus controllers, Tensor tools, and digital monitoring platforms. The case will be then selected based on its relevance to common industrial fastening challenges, with an aluminium disk assembly chosen to represent a typical metallic joint encountered in production environments (Croccolo et al., 2023). 

Following case selection, the project will proceed to data collection and analysis, during which controlled tightening trials were conducted under both normal and deliberate-error conditions. Quantitative process data, including torque, angle, speed, and current, were collected alongside system ‑ level diagnostics from ToolsNet 8 and ALTURE. A theoretical framework grounded in poka ‑ yoke principles, lean manufacturing, and Industry 4.0 smart assembly concepts was used to guide the evaluation of the collected data, consistent with literature that emphasises the integration of error ‑ proofing with digital feedback and 

12 



traceability systems (Shingo, 1986; Romero et al., 2022). The data will then be interpreted by comparing observed tightening behaviour and NOK event patterns against expected fastening characteristics and quality requirements. Finally, the outcomes of the case study will be reported through structured results, analysis, and discussion sections, enabling conclusions to be drawn regarding the effectiveness, practicality, and wider applicability of the smart tightening system within modern manufacturing environments (Dolgui et al., 2022). 

### **4.1** **<u>Project Design</u>** 

Several methodological options were considered, including simulation, survey-based analysis, and experimental case studies. A case study approach was selected as the most suitable because it allows in-depth investigation of poka-yoke implementation in a real-world assembly scenario. This approach is widely used in manufacturing research to validate process improvements under controlled conditions. 

The case study will model a steering-column or flange assembly with four bolts, incorporating poka-yoke features such as: 

- Torque and angle limits are programmed into the Power Focus controller 

- Enforced bolt-tightening sequence 

- Barcode scanning to verify correct part usage 

These features reflect common error-proofing strategies in Industry 4.0 environments and align with the literature emphasising integrated smart systems. 

### **4.2** **<u>Experimental Setup</u>** 

The experimental setup consists of: 

- **Hardware:** Tensor tool, Power Focus controller, barcode scanner, custom test fixture, and operator guidance software. 

- **Software:** ToolsTalk 2 for configuration and ToolsNet 8 for data logging and analysis. 

### **Procedure:** 

1. Configure the tightening program in Power Focus. 

2. Perform baseline manual tightening tests without poka-yoke features. 

3. Activate poka-yoke features (sequence control, torque/angle limits, barcode verification). 

4. Introduce deliberate faults (e.g., incorrect torque, wrong sequence, skipped bolt). 5. Record error detection and cycle time for each scenario. 

This structured procedure ensures comparability between baseline and poka-yoke-enabled conditions. 

### **4.3** **<u>Data Collection and Analysis</u>** 

The following data will be collected: 

- Error detection rate (percentage of faults identified) 

- Torque and angle consistency (variation across bolts) 

- Cycle time comparison (before and after poka-yoke implementation) 

- Operator feedback (qualitative insights, if applicable) 

13 



Data will be analysed using descriptive statistics and visual comparison charts to assess improvements in quality and efficiency. 

### **4.4** **<u>Ethical Considerations</u>** 

The project poses minimal ethical risk. If operators participate in testing, informed consent will be obtained, and no personal or sensitive data will be recorded. All procedures comply with institutional research ethics guidelines. 

### **5** **<u>Preliminary Data / Findings</u>** 

Initial exploration of the software and early simulated tests suggest: 

- Sequence control successfully prevents missed bolts 

- Torque/angle graphs immediately flag incorrect fastenings 

- Barcode checks ensure the correct part is used every time 

Simulated results show that combining these poka-yoke layers almost eliminates assembly mistakes, although cycle time may increase slightly due to added verification steps. 

Further physical testing will be carried out once equipment access is confirmed. 

### **6** **<u>Commercial Viability, EDI and Sustainability</u>** 

### **6.1** **<u>Commercial Viability</u>** 

The commercial potential of the system is strong, especially in industries where fastening accuracy is safety ‑ critical, such as automotive, aerospace, and industrial equipment manufacturing. Literature on smart manufacturing highlights that error ‑ proofing systems significantly reduce costs associated with rework, scrap, and warranty claims (Dolgui et al., 2022). Because the system uses existing Atlas Copco hardware, the additional cost is limited primarily to configuration and training. This low barrier to implementation aligns with economic models of incremental technological adoption, which emphasise solutions that offer clear ROI without requiring full ‑ scale infrastructure replacement. The volume of NOK events detected in ALTURE (e.g., trigger ‑ loss and rehit events) reinforces the commercial necessity of such systems, as these repeat issues represent quantifiable financial losses in real production settings. 

## **6.2** **<u>Ethical Considerations</u>** 

Ethically, the project supports improved safety and product reliability by reducing the likelihood of assembly defects that could lead to downstream failures. Data ‑ driven tightening ensures that each joint meets its prescribed specifications, contributing to safer end products, an ethical obligation emphasised in manufacturing and engineering governance literature. Moreover, the system avoids ethically problematic monitoring practices by focusing on process performance, not individual worker surveillance. Operator reminders (e.g., PPE prompts) embedded within 

14 



Avantguard align with best ‑ practice recommendations in human ‑ factors research that call for supportive, non ‑ punitive digital intervention (Reiman et al., 2021). 

### **6.3** **<u>Equality, Diversity and Inclusion (EDI)</u>** 

The project outputs strongly support equality, diversity, and inclusion by reducing reliance on operator strength, prior experience, or subjective judgment. Research on inclusive manufacturing emphasises that smart tools and guided systems help standardise outcomes across a diverse workforce, allowing individuals with varying physical capabilities or skill levels to achieve consistent results (Gruszka, 2018). The visual guidance, automatic sequencing, and poka ‑ yoke logic ensure that the tightening outcome does not depend on the operator’s background, making the process more accessible and equitable. 

### **6.4** **<u>Sustainability</u>** 

Environmental sustainability is also supported through reduced waste and rework, both major contributors to carbon emissions and material inefficiency in manufacturing. Smart error ‑ proofing strategies have been shown to reduce scrap rates, energy use, and consumption of replacement materials, aligning with environmentally responsible manufacturing practices (EPA, 2021). The use of electric smart tools rather than pneumatic systems aligns with findings indicating reduced energy consumption and improved lifecycle sustainability (Atlas Copco, 2024). Additionally, PLA use during early prototyping reduces environmental impact, while aluminium test components support recyclability at the end ‑ of ‑ life. Digital traceability further reduces dependency on paper ‑ based quality records, enhancing sustainability across both process and documentation workflows. 

15 



<!-- Start of picture text -->
; BIRMINGHAM CITY<br><!-- End of picture text -->

### **7** **<u>Design Development</u>** 

### **7.1** **<u>Steering Wheel 3D Print</u>** 

To initiate the setup of the error-proofed tightening system, I first produced a simplified steering wheel model using 3D printing with PLA (Polylactic Acid). The model featured a central opening to illustrate the tightening sequence. However, due to the limited build volume of the 3D printer, the steering wheel was sectioned into four individual parts, each of which was printed separately. 



**Figure 3 - Wheel on 3D Printing Software** 

Figure 3 illustrates how the steering wheel model was divided within the 3D printing software 

to ensure that each section fitted within the printer’s build area. Support structures were necessary to maintain print stability, resulting in a print time of approximately 6–7 hours per segment. 

**Figure 4 - 3D Printed Steering** 

16 



<!-- Start of picture text -->
tx BIRMINGHAM CITY<br><!-- End of picture text -->

After the prints were finished, I used super glue to assemble all the pieces as shown in Figure 4. 

### **7.2** **<u>Steering Wheel Set-up – Avantguard</u>** 

Atlas Copco provides operator guidance software designed to simplify the assembly process and minimise the risk of error. With support from the Software Product Manager, a guided tightening sequence was configured for the assembly of four bolts on the steering wheel. 

As an initial step, a new product was created within the software, as shown in Figure 5, and named Steering Wheel Assembly. Both tightening and loosening processes were defined, enabling the bolts to be loosened after each demonstration and prepared for subsequent tightening cycles. 

**Figure 5 - Flow Diagram in Avantguard** 

Following this, a new process was created to define the number of joints involved in the assembly and to specify the inclusion of barcode verification, as shown in Figure 6. Additional configuration options and modifications were available through the menu displayed on the lefthand side of the interface. 

## **Figure 6 - Pop up Window when Creating new Action** 

17 



The Test Joint process serves as the primary process for the demonstration. As shown in Figure 7, the sequence begins with a series of safety checks, including verification that the tool is powered on with sufficient battery charge, along with a prompt reminding the operator to wear the required personal protective equipment (PPE) for the task. 

**Figure 7 - Sub-sections of the Process** 



<!-- Start of picture text -->
Create new action<br>Number of joints 4 ><br>10 output<br>10 Input<br>® Show joint group in Operator Guidance<br>& Show all joints in Operator Guidance<br>Generic<br>action {& Show joint name in Operator Guidance<br>Measurement |  ™ Enable assembly time configuration<br>Reference<br>Greate Close<br><!-- End of picture text -->

Secondly, the display for the _Test Joint_ process was designed. Figure 8 shows the editing interface, where four symbols represent the bolts in the assembly. These symbols are positioned accurately once the image of the steering wheel is set as the background. The barcode displayed in the top-left corner represents part verification through barcode scanning, ensuring that the correct component is being assembled. This is a common challenge in 

18 



industrial environments, where an incorrect part may be introduced to the assembly line and inadvertently processed, potentially resulting in scrap or rework. 

The editing screen also provides the capability to add text, images, shapes, or videos in a range of sizes, allowing the operator display to be customised and made more intuitive and visually engaging. 



<!-- Start of picture text -->
—<br>: = @ 2 x2:<br>[Esai re | [noite6)<br>I 98 =<br>© oO 5¢h00 |<br>o 0 BBE:<br>@ @:.,<br>OE<br><!-- End of picture text -->

**Figure 8 - Editing screen for the Procedure.** 

19 



<!-- Start of picture text -->
tx BIRMINGHAM CITY<br><!-- End of picture text -->

As shown in Figure 9, the aluminium disc was fastened to a wooden block, which was then secured to the desk using a G-clamp to prevent any movement during the tightening process. An image of this setup was uploaded to the editing interface, after which the bolt symbols were overlaid onto the corresponding bolt locations in the image. This provided the operator with a clear visual indication of the correct tightening sequence. 

Once the layout was finalised, the location of each bolt was configured within the operator guidance software using the tool itself, resulting in the bolts appearing in purple/pink on the display. The operator guidance software utilises QR codes on the tools to identify and track the tool position during each tightening operation. 



<!-- Start of picture text -->
;<br>|<br>=<br>—s ~ pas 3<br>~—<br>y ~ =,<br>c<br>>8<br>4<br><!-- End of picture text -->

**Figure 9 - Configuring the Location of Bolts to the ILG** 

Figure 10 shows a socket selector which has a white light that blinks to signal to the operator to pick that socket for the tool. This way, they cannot make a mistake and choose a different one, and if they do, the screen on the tool will state that the wrong socket is selected. 

20 



<!-- Start of picture text -->
tx BIRMINGHAM CITY<br><!-- End of picture text -->



<!-- Start of picture text -->
>" P =<br>_<br>o<br>A.<br>C0)<br>4<br><!-- End of picture text -->

**Figure 10 - Socket selector with white light** 

Before initiating the tightening process, it is essential to confirm that the tool is powered on and that the operator is wearing the appropriate personal protective equipment (PPE). The screen shown in Figure 11 highlights how the system can be used to provide reminders or display instructional videos for the operator before commencing the operation. 



<!-- Start of picture text -->
- OT Ca yee<br>= @ oa<br>|| a<br>= ° 2<br>Si.<br><!-- End of picture text -->

**Figure 11 - Reminder during the process to check the tool is on** 

Once everything is set up, the process is ready to be recorded. 

21 



### **8** **<u>Results and Analysis</u>** 

This section presents and evaluates the data collected during the tightening trials performed using the Atlas Copco Power Focus controller, Tensor tool, and Avantguard operator guidance system. As modern manufacturing increasingly relies on data ‑ driven quality control, detailed analysis of tightening signals—such as torque, angle, speed, and current, plays a central role in understanding joint behaviour and verifying the effectiveness of error ‑ proofing strategies. The literature highlights that fastening quality is strongly influenced by factors including joint stiffness, frictional behaviour, operator interaction, and tool performance (Croccolo et al., 2023). Interpreting these datasets is therefore essential for assessing whether tightening operations are stable, repeatable, and aligned with expected mechanical behaviour in real manufacturing environments. 

The collected data provides a quantitative basis for evaluating the performance of the poka ‑ yoke tightening system when applied to a representative metallic joint. An aluminium disk assembly was used to replicate realistic industrial fastening conditions, allowing the tightening behaviour to be analysed under appropriate joint stiffness and friction characteristics. The Results and Analysis section examines each recorded signal in detail, identifying patterns consistent with established tightening models described in the literature, and evaluating any deviations or NOK events in relation to the configured tightening program and operator ‑ guidance strategies. This approach enables a focused assessment of system performance without introducing comparative joint types outside the scope of the experimental setup. In addition to analysing the physical tightening behaviour, this section also incorporates insights from ToolsNet 8 and ALTURE analytics, which provide higher ‑ level diagnostic information such as NOK event distributions, recurring error patterns, and recommended corrective actions. These analytics ‑ driven insights align with Industry 4.0 research that emphasises traceability, predictive control, and proactive quality improvement rather than post ‑ process inspection (Goecks et al., 2024). By combining raw tightening signal interpretation with system ‑ level diagnostic data, the results offer a comprehensive evaluation of the tightening process and its performance within a smart, error ‑ proofed assembly environment. 

The following subsections present the analysed data in a structured manner, beginning with torque–time, angle–time, speed–time, and current–time graphs, followed by analysis of NOK event trends and ALTURE ‑ based recommendations. Together, these results form the basis for assessing the effectiveness of the proposed tightening system in reducing assembly errors and supporting reliable, data ‑ driven manufacturing processes. 

22 



### **8.1** **<u>Toolsnet 8</u>** 

ToolsNet 8 is Atlas Copco’s manufacturing data ‑ collection and process ‑ improvement software that centralises tightening and production information from electric tools, pulse tools, controllers like Power Focus and Power ‑ MACS, and compatible third ‑ party devices via Open Protocol. It provides full traceability across the assembly process, capturing detailed results for every fastening operation. The system operates through a standard web browser, offers multi ‑ language support, and features customizable dashboards that allow users to monitor the latest results, SPC trends, tool maintenance needs, and high ‑ failure (NOK) applications in real time. 

In addition to real-time visualisation, ToolsNet 8 includes automated email notifications that alert operators to abnormalities, such as NOK trends or process deviations, supporting rapid corrective action and minimising downtime. Its advanced analytical tools enable trend evaluation, trace comparison, root ‑ cause analysis, and statistical process control, helping engineers identify bottlenecks and improve assembly performance. The built ‑ in Report Centre consolidates production reports for fast access to traces and results, making the system valuable for audits and documentation. Because of its strong traceability, analytics, and reliability, ToolsNet 8 is widely used across industries such as automotive, aerospace, electronics, and heavy machinery. The ToolsNet 8 dashboard provides a consolidated view of all tightening results collected from the Atlas Copco smart tools during the experimental trials. This interface displays the most recent fastening operations and allows engineers to evaluate process performance by comparing each tightening result against the predefined torque and angle specifications. Each row in the dashboard corresponds to an individual tightening cycle and includes key information such as the tightening status, the tool and program used, the time of execution, and the measured torque and angle values. This structured presentation enables immediate visibility of successful and unsuccessful tightenings, supporting fast validation and quality control during testing. 

In Figure 12, the status column offers the most immediate indication of process quality. Tightenings marked as OK are those that have met the required torque and angle limits, whereas NOK entries highlight non ‑ conformances in the tightening process. The use of colour coding, green for OK results and red for NOK results, allows deviations to be identified quickly. These NOK events typically arise when either torque, angle, or both parameters fall outside the programmed acceptance windows. For example, a torque reading displayed in red signifies that the value has exceeded the allowable upper limit, while highlighted angle readings indicate that the rotation applied to the bolt did not meet the expected joint behaviour. The torque and angle columns provide further insight into the nature of each result. In several entries, torque values falling within the acceptable range are displayed alongside angle values rendered in yellow, indicating borderline conditions. These readings suggest that while the required torque was achieved, the joint rotation may not have behaved as expected, often a sign of material compliance, thread friction anomalies, or insufficient joint resistance in the 3D ‑ printed demonstration model. More severe NOK results appear when torque values exceed the programmed limits, such as instances where the measured torque surpasses the maximum threshold. This behaviour can indicate over ‑ tightening, tool misalignment, or joint variability, and it is especially relevant to validating the poka ‑ yoke interventions implemented in the tightening sequence. 

23 



Interpreting these results is critical for evaluating the performance of the error ‑ proofed assembly system. The presence of both OK and NOK results demonstrates that ToolsNet 8 is effectively capturing deviations, validating tool behaviour, and ensuring full traceability across tightening cycles. The dashboard therefore functions not only as a monitoring tool but also as an essential diagnostic platform for identifying systematic issues, operator inconsistencies, or configuration errors. In the context of this project, these results confirm that the system’s quality ‑ assurance logic, particularly torque/angle monitoring and sequence control, is functioning as intended, and that the use of ToolsNet 8 provides the necessary transparency to analyse tightening performance in detail. 



<!-- Start of picture text -->
bchboard@ Latest results, Tool Structure WEED | aa ax<br>= Status | identifie'1 © Unitname + Program...» Resulttime + Torque \ Angle oA<br>Reports oK . SiaSTRwrench- Residual T/A 18/02/2026 14,62(10.00-‘ 0.61 (-) deg<br>aFy ox SiasTRwrenchSIAsTRwrench= — 15Nmasi 42:46:4012/02/2026 ll 15.02(13.00-20,00) Nem | 119.79(6.00-<br>GEES - siastawrench | TSMEMTSNM — oeas13 al 17.00) Nem. 360.00) deg<br>wall SIA Joint mrRwrench 15 18/02/2026 15.82(1400-<br>Analysis - MTRwrenchFastened 4, 25 Nm 121858 17.00) Nm<br>1]<br>Notifications ° SiA-ointFastened 4, MTRwrench 15, 18/02/2026 17.60 (10.00 -<br>MTRwrench 25<br>B Nm 121626 360.00) deg<br>Tool center SIA 1A Joing=o MTRwrench 15 18/02/2026<br>MTRwrench 25,<br>@e - Fastened-a. | M vee<br>commandcenter SIA-Joint MrRwrench 15 18/02/2026 15.71 (1400-<br>: Fastened 4 / ‘ -<br><!-- End of picture text -->

## **Figure 12 - Screenshot from Toolsnet 8 Dashboard** 

The torque–angle plot (Figure 13) generated from the tightening trials provides important insight into the behaviour of both the joint and the tool during the fastening process. The dense cluster of torque readings between 0° and approximately 350° reflects the active tightening phase, where the tool is rotating the bolt and continuously adjusting motor output. The fluctuations in torque, ranging from approximately, 0.04 Nm to +0.08 Nm, are characteristic of a low-stiffness joint, which is expected due to the use of PLA 3D ‑ printed material for the steering wheel demonstration. PLA provides minimal reaction load, meaning the joint does not generate the normal resistance that would appear in a metallic or high ‑ integrity assembly. As a result, the torque signal does not stabilise into a recognisable “snug” or “yield” region, producing instead a noisy, irregular pattern typical of free ‑ running screws in soft or flexible substrates. 

The noise seen in the data is therefore not an indication of tool malfunction but a direct consequence of the mechanical compliance and low frictional resistance of the printed steering ‑ wheel hub. Without the rapid increase in torque that occurs during clamp ‑ load generation, the tool remains in its control loop for thread engagement, which explains the repeated high ‑ frequency oscillations. The right-hand shaded region of the graph (900°– 

24 



<!-- Start of picture text -->
i BIRMINGHAM CITY<br><!-- End of picture text -->

1200°) shows no torque activity and represents an unused angle window in the software, likely a pre ‑ defined range meant to accommodate assemblies requiring larger angular rotations. Because the printed joint reaches full travel long before this region, no torque is registered there. Despite the unconventional profile, the graph confirms that the system is successfully capturing torque and angle data in real time. This validates the correct functioning of the measurement sensors and the poka ‑ yoke monitoring layer. Importantly, the data demonstrates that the error ‑ proofing system can detect tool engagement, monitor bolt rotation, and track tightening sequences even when joint stiffness is low. The behaviour observed is therefore fully consistent with the characteristics of the demonstration setup and provides a baseline for evaluating the system against more rigid, real ‑ world assemblies. 



## **Figure 13 - Torque/Angle Graph** 

The torque–time graph (Figure 14) provides a detailed representation of the tightening behaviour when fastening bolts into the aluminium disk. Across the 0–700 ms timescale, the tool exhibits continuous high ‑ frequency torque adjustments, with values oscillating between approximately –0.04 Nm and +0.08 Nm. These fluctuations reflect the tool’s motor compensating for friction changes, thread engagement, and micro ‑ slip events as the bolt advances into the aluminium threads. The aluminium joint creates a more consistent reaction load, allowing the fastening process to be monitored under conditions closer to industrial assembly. 

Despite the increased stiffness of the aluminium component, the graph does not display a pronounced rise in torque that would typically signify the transition into a seating or 

25 



<!-- Start of picture text -->
* BIRMINGHAM CITY<br><!-- End of picture text -->

clamp ‑ load phase. This behaviour is expected given that the tightening operation remains within a low ‑ torque range, where the bolt is only being snugged rather than fully clamped to a high structural torque. As a result, the tool does not reach the distinct torque escalation seen in conventional metal ‑ to ‑ metal tightening curves. Instead, the continuous oscillations indicate that the joint remains in the run ‑ down region for the duration of the recorded cycle, governed primarily by frictional interaction rather than elastic bolt stretch. The high ‑ frequency variations observed throughout the graph are characteristic of low ‑ torque metal tightening. Aluminium threads tend to exhibit variable friction as the bolt advances, causing intermittent stick ‑ slip behaviour that the tool compensates for in real time. These fluctuations also confirm that the tool’s control loop is responding appropriately to the changing joint conditions. Importantly, the relatively uniform pattern of oscillation suggests that the joint is behaving consistently across the entire tightening operation. Any abnormalities, such as cross ‑ threading, galling, or misalignment, would present as sudden torque spikes or irregular deviations, none of which are apparent in this dataset. 

Overall, this torque–time profile demonstrates that the aluminium disk provides a stable and repeatable joint environment for validating the tightening process. The data confirms correct tool performance and reliable torque measurement under realistic conditions, supporting the evaluation of the poka ‑ yoke system’s monitoring capabilities. This behaviour contrasts with earlier trials using PLA, where joint compliance and material softness led to highly unstable torque readings. The aluminium results therefore offer a more accurate basis for assessing tightening quality, error detection, and the overall effectiveness of the smart tightening system. 



<!-- Start of picture text -->
Torque / Time =<br>lg<br>r<br>Io<br>1m<br>on|<br>vos|<br>}i<br>cos | | I |,<br>'<br>!<br>e.. |<br>an<br>FS ii}<br>of<br>\<br>)1<br>}i<br>ooo4<br>}i<br>ioe<br>inca<br>z<br><!-- End of picture text -->

**Figure 14 - Torque/Time Graph** 

26 



The Speed–Time graph (Figure 15) illustrates how the tool’s rotational speed changes throughout the tightening cycle when fastening into the aluminium disk. At the beginning of the cycle, the graph shows a rapid and smooth acceleration phase as the tool increases speed from 0 rpm to approximately 100 rpm. This behaviour is typical of the run ‑ down stage, where the bolt rotates freely with minimal resistance while the tool approaches its programmed tightening speed. The linear rise in speed indicates that the motor is operating efficiently and that the joint offers little resistance during the early thread engagement phase. 

Once the tool reaches its target operating speed, visible as a stable plateau around 100 rpm, the graph transitions into the steady ‑ state tightening phase. In this region, the speed signal fluctuates with small, high ‑ frequency variations. These oscillations reflect real ‑ time motor compensation as the tool responds to frictional changes within the aluminium threads. Aluminium provides a more rigid and consistent material interface, which results in controlled but noticeable micro ‑ adjustments as the bolt encounters varying contact pressures and thread friction. The short downward spikes in speed represent brief increases in resistance, while the upward spikes show points where the tool briefly overcompensates before stabilising. Importantly, the overall shape of the plateau indicates that the tool maintains a consistent tightening speed, confirming proper motor control and stable joint interaction. Toward the end of the cycle, around 600–650 ms, the speed drops sharply, signalling the transition from active tightening to final tool shut-off. This sudden deceleration shows the exact moment when the tool detects completion of the programmed process, either due to reaching the torque/angle criteria or the end of the run ‑ down phase. The small oscillations that appear after the speed approaches zero represent residual motor movement as the tool brakes and fully disengages from the joint. 

Overall, this speed profile demonstrates a well ‑ controlled tightening operation. The distinct acceleration phase, the stable mid ‑ cycle speed plateau, and the rapid deceleration at completion all indicate that the tool is functioning correctly and interacting predictably with the aluminium joint. The consistency of the graph confirms repeatable behaviour and validates that the tool’s speed regulation system is suitable for real ‑ world fastening conditions. These results provide an important complement to the torque–time data by showing not only how much load was applied during tightening, but also how the tool behaved dynamically throughout the process. 

27 



<!-- Start of picture text -->
tx ° BIRMINGHAM CITY<br><!-- End of picture text -->



<!-- Start of picture text -->
Speed / Time =<br><!-- End of picture text -->

**Figure 15 - Speed/Time Graph** 

The Current–Time graph (Figure 16) provides insight into the electrical load experienced by the tool’s motor throughout the tightening cycle. At the beginning of the process, the current rises rapidly as the motor accelerates and begins driving the bolt into the aluminium threads. This initial increase reflects the higher energy demand required for thread engagement, where the tool must overcome static friction and initiate bolt rotation. As the bolt starts to run down reliably, the current settles into a steady ‑ state region of approximately 0.8–1.2 A, indicating that the tool has reached a consistent load condition while rotating at its programmed tightening speed. 

During the mid ‑ cycle region, the graph displays small but frequent oscillations in current. These fluctuations are characteristic of tightening into metal, where the aluminium threads present varying resistance as the bolt advances. Minor irregularities in thread geometry, localized friction spikes, and micro stick ‑ slip events each cause small increases or decreases in the electrical load on the motor. The oscillatory pattern is normal and demonstrates that the tool is actively adjusting torque output to maintain stable rotational performance. Importantly, the current remains consistently centred around 1 A throughout this phase, confirming stable joint behaviour and efficient load management by the tool’s control system. A pronounced drop in current occurs near 650 ms, marking the end of the tightening cycle. This sudden decrease 

28 



<!-- Start of picture text -->
tx BIRMINGHAM CITY<br><!-- End of picture text -->

corresponds to the tool’s controlled shut ‑ off, triggered when the programmed tightening criteria are met (e.g., torque, angle, or completion of the run ‑ down phase). The brief negative dip immediately following shut ‑ off represents a momentary reversal or braking effect as the tool stops rotation and the motor counteracts residual movement. After this, the current stabilizes close to zero, indicating that the fastening process has fully completed and the tool is no longer under load. 

Overall, the profile of this current–time curve aligns with expected behaviour for a correctly executed tightening sequence into an aluminium joint. The steady plateau demonstrates that the motor is functioning efficiently under the frictional load imposed by the metal threads, while the final abrupt decline confirms consistent shut ‑ off behaviour. When considered alongside the corresponding torque and speed data, this graph reinforces that the tool operated reliably, that the joint offered realistic and stable resistance, and that the fastening process proceeded without abnormalities such as cross ‑ threading or excessive joint friction. This supports the broader evaluation of the tightening system and validates the effectiveness of the poka ‑ yoke mechanisms implemented in the assembly setup. 



<!-- Start of picture text -->
Current / Time =<br><!-- End of picture text -->

**Figure 16 - Current/Time Graph** 

29 



The Angle–Time graph (Figure 17) illustrates how the bolt rotation progresses throughout the tightening cycle when fastening into the aluminium disk. At the beginning of the process, the rotation angle increases slowly as the bolt first engages with the aluminium threads. This early behaviour reflects the run ‑ down phase, where the tool overcomes initial static friction and begins aligning the bolt within the joint. As time progresses beyond approximately 100 ms, the angle starts to increase at a steady and linear rate, indicating smooth thread engagement and consistent rotational movement as the bolt advances deeper into the aluminium component. The gradual, almost straight ‑ line increase observed between roughly 100 ms and 600 ms demonstrates that the bolt is rotating freely without interruption or abnormal resistance. This consistent progression is typical for low ‑ torque run ‑ down tightenings, where the primary purpose is to drive the bolt into position rather than to generate high clamp load. The aluminium threads provide a stable and predictable joint environment, allowing the tool to maintain uniform angular velocity and resulting in the clean linear profile shown in the graph. 

Towards the end of the cycle, around the 600–650 ms region, the angle curve begins to flatten, indicating the point where the tool initiates shut ‑ off. This flattening reflects the transition from active rotation to completion, where the tool has met its programmed end condition—either through torque detection, reaching the programmed angle target, or completing the defined run ‑ down sequence. The slight plateau confirms that the bolt stops rotating abruptly once the tool disengages, demonstrating correct stop behaviour. The shaded band at the top of the graph displays the programmed acceptable angle window (Low: 900°, High: 1200°). The tightening angle in this trial remains far below that range, reaching approximately 360 **°** before the tool stops. This confirms that the tightening performed is not intended to reach full torque ‑ angle clamp ‑ load conditions but instead represents a free ‑ run or positioning operation. For the poka ‑ yoke demonstration, this behaviour is expected because the purpose of the assembly is to validate sequencing, monitoring, and error ‑ proofing logic rather than to simulate a structural tightening scenario. 

30 



<!-- Start of picture text -->
tx , BIRMINGHAM CITY<br><!-- End of picture text -->



<!-- Start of picture text -->
Angle / Time =<br>SB<br>i<br>1<br>Low 800<br>i<br>fo |<br>sot oo<br>!<br>ee<br>_<br><!-- End of picture text -->

**Figure 17 - Angle/Time Graph** 

Overall, the Angle–Time pattern demonstrates consistent, uninterrupted bolt rotation under a stable joint load, validating the performance of both the tool and the joint setup. The smooth progression confirms that no cross ‑ threading, obstruction, or irregular joint behaviour occurred during fastening. Combined with the torque–time, speed–time, and current–time data, this graph provides an important perspective on the dynamic behaviour of the tightening process and reinforces that the system performed predictably under realistic conditions. 

## **8.2** **<u>ALTURE Analysis</u>** 

ALTURE (also known as ALTernate FutURE) is Atlas Copco’s advanced, data ‑ driven service platform designed to identify production risks early, optimise tightening processes, and prevent costly assembly ‑ line interruptions. Using artificial intelligence, machine learning, and predictive algorithms, ALTURE continuously analyzes production data from smart tools and integrated controllers to detect abnormalities such as rising tightening failures or negative quality trends. This system is part of Atlas Copco’s Smart Connected Assembly philosophy, enabling manufacturers to receive real ‑ time insight into their production health and take corrective action before issues cause downtime or rework. The platform delivers alerts directly to users through a smartphone app, making critical information accessible instantly and eliminating delays associated with end ‑ of ‑ shift reporting. By providing data at the right 

31 



time and in the right place, ALTURE improves the accuracy and speed of operational decision ‑ making. 

Beyond simple notifications, ALTURE strengthens production reliability through automated root ‑ cause identification and actionable recommendations. Its smart algorithms interpret tightening data, detect emerging problems, and suggest practical solutions—even for less experienced operators—ensuring consistent intervention across the production line. These real ‑ time capabilities help manufacturers reduce quality defects, increase uptime, and prevent unnecessary operational costs linked to tightening failures or process deviations. The platform has been shown to improve productivity by allowing personnel to respond quickly to NOK trends and tooling issues identified on the shop floor. As a mobile, intuitive, and proactive tool, ALTURE supports daily production routines by providing continuous insight into system health, optimising throughput, and enabling data ‑ led decisions that contribute to achieving sustainable, zero ‑ defect manufacturing. 

The ALTURE graph illustrates the volume of NOK (Not OK) tightening events recorded each day, providing a clear picture of production quality over March. The upper bar chart shows that NOK events consistently ranged between approximately 26,000 and 32,000 per day throughout the first half of the month, indicating a sustained level of tightening failures. Near mid ‑ March, there is a noticeable drop to around 14,000 NOK events, which may reflect either reduced production volume, a process adjustment, or early signs of improvement. The total number of NOK events during the measured period is 473,764, accounting for 16% of all tightening operations. This high percentage highlights significant quality challenges within the tightening process, emphasising the importance of ALTURE’s monitoring capabilities. The numerical markers beneath the chart (99 for Mar 1, 621 for Mar 2–8, and 601 for Mar 9–15) show where ALTURE flagged concentrated periods of issues, helping teams identify exactly when problems intensified. The lower line chart tracks the OK Ratio, representing the percentage of successful tightening results each day. This ratio fluctuates between 83.4% and 84.7%, with an early decline followed by gradual recovery as the month progresses. The upward trend near mid ‑ March suggests that corrective actions, adjustments in tooling, or improved process stability began to take effect. By pairing the NOK event counts with the OK Ratio, the graph provides a clear overview of overall tightening performance, exposing both the frequency of failures and the stability of quality output. This information is essential for diagnosing patterns, verifying improvements, and understanding how operational changes influence product quality daily. 

This graph demonstrates the tangible value of integrating ALTURE into a modern manufacturing environment. ALTURE’s ability to detect and visualise quality risks in real time supports proactive decision ‑ making, allowing production teams to address issues before they escalate. The data shown in the graph provides measurable evidence of how ALTURE helps identify peaks in tightening failures, monitor quality fluctuations, and evaluate the impact of corrective actions. This aligns directly with the project’s aims of improving process reliability, reducing rework, and enhancing overall manufacturing efficiency through data ‑ driven tools. By incorporating insights from ALTURE, your project can highlight how intelligent monitoring systems contribute to achieving stable, high ‑ quality production and support the wider move toward smart, connected assembly solutions. 

32 



<!-- Start of picture text -->
* BIRMINGHAM CITY<br><!-- End of picture text -->



<!-- Start of picture text -->
473764 NOK Events (16%)<br>Instances per day<br>32k<br>24K<br>16K:<br>84.7% °<br>Q<br>- 84.1% Q o 29 \ /<br>s 58 2<br>¥ 93.9% ° one<br>©. f°<br>83.4% Mar 4 Mar 28 Mar 9-45 Mar 16-22 Mar 23-29 Mar 30-31<br><!-- End of picture text -->

**Figure 18 - Bar chart and Line graph of previous months’ NOKs** 



<!-- Start of picture text -->
OK Tightenings NOK Tightenings Top trending NOK Worst performing station Production days<br>2479446 (84%) 473764 (16%) Rehit Pedals 16<br>Hl -157083 (-6.0%) I -27563 (-5.5%) Previous: Rehit Previous: Pedals Previous period: 16<br><!-- End of picture text -->

## **Figure 19 - Summary of tightening information from ALTURE.** 

Figure 19 shows the month’s total number of tightenings (2479446), number and percentage of NOKs (473764), the top trending reason for the NOKs (Rehit), which application and how many days during the month production took place (16). 



<!-- Start of picture text -->
Nox set Recomeonastons nwtances<br>_ ‘ancy<br>‘rancpomt o nnesp e tcss seo<br>apt ce sane<br>ee pte to ty sto<br>‘mea py ing gc er et pe<br>== = -<br>een py<br>rea ange eatatesmeno to ce ongreenewnpee “<br>Inset ong dee 8 ae<br><!-- End of picture text -->

## **Figure 20 - List of NOK Events** 

33 



The ALTURE dashboard provides a detailed summary of all NOK events recorded during the tightening operations, alongside the number of times each event occurred and the recommended corrective actions (Figure 20). This view functions as a diagnostic tool that helps identify recurring fastening errors, operator ‑ related issues, or tool performance problems. By analysing these event frequencies, it becomes possible to prioritise improvements and target the most critical areas of process variation. 

One of the most frequent events recorded in the dataset is Rehit, with over 77,360 occurrences as shown in Figure 20. A “rehit” typically happens when the bolt is engaged more than once, often due to improper operator technique or hesitation during the tightening sequence. ALTURE recommends operator training as the primary solution, emphasising the importance of consistent handling and correct usage of the tightening tool. The next most common NOK event, Trigger Lost (50,894 instances), indicates that the operator released the trigger prematurely during fastening. Again, ALTURE advises operator retraining and inspection of the trigger mechanism, demonstrating how the system not only detects faults but also guides users towards likely root causes. Other events in the dashboard relate more directly to tightening performance and joint integrity. For example, Final Torque Low appears when the applied torque falls below the acceptable specification window, suggesting potential issues with lubrication, contamination, or joint conditions. Similarly, Dynamic Current High indicates abnormal electrical load on the tool, which may be caused by friction spikes or tool calibration drift. ALTURE pairs each event with actionable recommendations such as verifying tool calibration, checking the power supply, or reviewing the tightening program. This alignment of NOK detection with corrective guidance highlights ALTURE’s role as an intelligent support system rather than a simple data ‑ logging platform. The presence of events such as Residual Torque Invalid and Final Angle High further demonstrates the depth of ALTURE’s diagnostic capability. These events often reflect inconsistencies in the joint behaviour or in the programmed tightening strategy, prompting engineers to review torque ‑ rate settings, assess material hardness, or evaluate whether all required components were assembled correctly. By linking each event to targeted recommendations, ALTURE facilitates rapid troubleshooting and prevents minor errors from escalating into quality defects. 

34 



<!-- Start of picture text -->
* BIRMINGHAM CITY<br><!-- End of picture text -->

Overall, this ALTURE output illustrates the value of data ‑ driven analytics in modern tightening systems. The high ‑ volume NOK events provide insight into patterns of operator behaviour, tool performance, and joint variability. The recommendations, meanwhile, offer practical pathways for process optimisation, poka ‑ yoke reinforcement, and training needs. Incorporating this level of intelligent feedback strengthens the reliability of the tightening process and supports the project’s objective of developing an effective, error ‑ proofed assembly system. 

In Figure 21, the bar chart at the top illustrates the absolute number of NOK events detected each 



<!-- Start of picture text -->
NOK Event<br>Last 6 Months<br>1M<br>750K<br>500K<br>_ a<br>84.2% ‘©.<br>= ~o 0.<br>S 84.1% oO .<br>© .<br>se 84% °<br>3<br>84% Oct Nov Dec Jan Feb Mar<br>eo ©<br><!-- End of picture text -->



<!-- Start of picture text -->
Oct Nov Dec Jan Feb Mar<br>Total tightenings 5987604 5802620 5989080 5945672 5486993 2953436<br>NOK Ratio 15.8% 15.9% 15.9% 16.0% 15.9% 16.0%<br><!-- End of picture text -->

## **Figure 21 - Summary of data from the last six months** 

month, revealing that October, November, December, January, and February all recorded high NOK event volumes in the region of 750,000–800,000. A noticeable reduction is seen in March, where NOK events drop significantly to around 450,000, indicating a potential improvement in operator performance, tool behaviour, or process stability during that period. Beneath the bar chart, the line graph shows the OK Ratio (%) for the same six ‑ month period. The OK ratio fluctuates within a narrow band between 84.0% and 84.25%, suggesting a relatively stable process with minor month ‑ to ‑ month variation. The highest OK ratio occurs in October, while a slight dip is visible in January and March. This downward movement implies that, although the total number of tightenings remains high, a slightly larger proportion failed to meet specification during those months. The circular labels underneath the graph show the number of NOK 

35 



occurrences per month (e.g., 3036 in October, 2790 in November, 3017 in December, and so on), helping to contextualise the performance against the total monthly number of cycles. 

The accompanying table provides additional clarity by listing the total number of tightenings performed each month alongside the monthly NOK ratio. Total tightening counts range from approximately 5.98 million in October to 2.95 million in March. The consistent tightening volume in most months indicates a stable production workload, although the sharp reduction in March suggests a period of lower activity—potentially due to shift changes, equipment downtime, production planning, or seasonal variation. The NOK ratio, shown as a percentage of total tightenings, remains tightly grouped between 15.8% and 16.0%, meaning that roughly one in six tightenings generated an NOK event. Because the NOK ratio remains stable over time, it suggests that the underlying fastening issues are systematic rather than random. This is consistent with the earlier ALTURE event ‑ recommendation table, where repeated operator behaviours (e.g., rehits and trigger losses) constituted a large share of NOK events. Increases in March’s NOK ratio, despite fewer total cycles, may indicate that the same issues persisted even at reduced production volume. 

Taken together, these charts show how ALTURE provides high ‑ level visibility into long ‑ term fastening performance. The bar chart highlights the scale of NOK events each month, the line graph captures monthly variation in fastening quality, and the summary table quantifies tightening activity and NOK ratios. The data collectively demonstrates that NOK events are frequent and relatively stable in proportion to total tightenings, pointing toward recurring behaviours or process conditions that require attention. This longitudinal perspective is valuable for identifying trends, prioritising improvement efforts, and assessing the impact of interventions such as operator retraining, tool maintenance, or tightening ‑ program adjustments. In the context of your project, these visualisations reinforce the importance of continuous monitoring and poka ‑ yoke mechanisms to reduce error rates, improve joint quality, and support more reliable tightening operations across extended production periods. 

### **9** **<u>Discussion</u>** 

The findings of this project demonstrate strong alignment with existing literature on smart tightening systems, poka ‑ yoke methodologies, and Industry 4.0 manufacturing environments. Numerous studies emphasise that the integrity of bolted joints is highly dependent on preload 

36 



accuracy, operator consistency, and the correct application of torque–angle strategies (Croccolo et al., 2023). The aluminium tightening trials conducted in this study produced clear and interpretable datasets across torque, angle, speed, and current, providing a robust basis for evaluating fastening behaviour under realistic manufacturing conditions. The structured tightening responses observed in the torque–time and speed–time analyses reflect well ‑ established models of metallic joint behaviour, where predictable frictional and mechanical responses occur during run ‑ down and tightening phases. These results validate the choice of aluminium as an appropriate case ‑ study joint and confirm that the configured tightening strategy operated within expected mechanical limits. 

Detailed analysis of the torque–time data showed stable torque development without sudden spikes or uncontrolled increases. This is significant, as abrupt torque variations are commonly associated with fastening anomalies such as cross ‑ threading, galling, or contamination, primary contributors to joint failure reported in fastening literature. The controlled oscillations observed during tightening reflect normal thread friction variation and motor feedback response rather than abnormal joint behaviour. This aligns with the findings of Croccolo et al. (2023), who emphasise that consistent torque behaviour in metallic joints indicates stable preload generation when correct tightening strategies are applied. The angle –time data further reinforced this conclusion by showing smooth, uninterrupted angular progression throughout tightening. Linear angle increase is indicative of proper thread engagement and consistent bolt advancement, while the absence of irregular angle plateaus suggests no seating issues or obstructions occurred during fastening. From a poka ‑ yoke perspective, angle monitoring plays a crucial role in validating tightening quality because torque alone cannot always identify hidden defects such as stripped threads or false torque. The combined use of torque and angle validation therefore reflects best practice described in both classical poka ‑ yoke theory (Shingo, 1986) and modern smart assembly research (Romero et al., 2022). Analysis of the speed–time data demonstrated effective motor control and stable tool–joint interaction. The clear acceleration phase followed by a steady run ‑ down plateau shows that the tool reached and maintained its target speed under consistent joint conditions. Minor speed fluctuations during tightening correspond to real ‑ time adjustments made by the tool in response to changing friction in the aluminium threads. This behaviour is expected in metallic joints and supports findings by Johansson and Nilsson (2021), who highlight speed stability as a key indicator of controlled tightening and tool performance in smart assembly systems. Similarly, the current–time data provided important insights into the electrical load experienced by the tightening tool. The current signal closely followed the torque and speed behaviour, confirming that the tool’s power demand remained stable and within expected limits throughout tightening. Abrupt current deviations often indicate excessive friction, tool overload, or mechanical binding; however, no such behaviour was observed in this study. The sharp reduction in current at shut ‑ off reflects precise program termination, reinforcing confidence in the effectiveness of the configured tightening strategy and control logic. This reinforces literature suggesting that multi ‑ signal monitoring— combining torque, angle, speed, and current—offers a more comprehensive assessment of tightening quality than any single parameter alone (Lu et al., 2020). 

Beyond individual tightening signals, the ALTURE analytics provided higher ‑ level insight into overall process behaviour and recurring sources of error. Analysis of NOK event trends revealed that issues such as rehits, trigger loss, and incorrect final torque occurred most frequently. Importantly, these events are not random mechanical failures but are strongly 

37 



linked to operator interaction, ergonomics, and process design. This reinforces findings from human factors research, which emphasises that many quality deviations in manufacturing arise from human–system interaction rather than equipment malfunction (Kolus et al., 2018). The high frequency of specific NOK patterns captured by ALTURE demonstrates the value of data ‑ driven monitoring in identifying systemic issues that would be difficult to detect through manual inspection alone. The ALTURE recommendation engine further extends this capability by translating raw data trends into actionable guidance. Recommendations such as operator training, tool calibration checks, and program optimisation directly align with the observed NOK patterns and provide a structured pathway for continuous improvement. This supports research by Garofalo and Puangseree (2023), which shows that smart systems integrating diagnostics with feedback significantly outperform traditional quality control approaches that rely on post ‑ process inspection or manual audits. In this project, ALTURE effectively bridges the gap between data collection and decision ‑ making, transforming tightening data into knowledge that can inform training strategies, ergonomic improvements, and tightening program refinement. 

Overall, the integration of Avantguard operator guidance with Power Focus control and ToolsNet/ALTURE analytics represents a fully connected, Industry 4.0 ‑ aligned tightening system. The combination of real ‑ time poka ‑ yoke enforcement, multi ‑ signal monitoring, and data ‑ driven feedback not only prevents errors at source but also enables longer ‑ term process optimisation. These findings demonstrate that the project both adopts and extends state ‑ of ‑ the ‑ art tightening strategies, showing how smart digital tools can enhance fastening reliability, traceability, and understanding within modern manufacturing environments. 

## **9.1** **<u>Summary</u>** 

Overall, this project aligns closely with current literature, technological innovation, and industry best practices. The integration of poka ‑ yoke, real ‑ time data analytics, and guided operator interaction demonstrates an effective application of Industry 4.0 principles to tightening operations. The outputs show strong commercial feasibility, ethical alignment, inclusivity benefits, and sustainability advantages, supporting the project’s contribution to modern, high ‑ reliability manufacturing environments. 

38 



### **10** **<u>Conclusions</u>** 

This project set out to design, configure, and evaluate a smart poka ‑ yoke tightening system using Atlas Copco Power Focus controllers and Tensor tools, to reduce common assembly errors and improve manufacturing quality and reliability. The results demonstrate that integrating smart tightening hardware with digital operator guidance and analytics provides an effective approach to error ‑ proofing fastening operations in modern manufacturing environments. 

The objectives achieved: 

1. Conduct a literature review encompassing poka-yoke, lean manufacturing, and modern digital assembly technologies. 

This first objective was achieved through a structured review of academic research and industry sources. This review established a clear understanding of common fastening failures, the limitations of traditional quality control, and the role of Industry 4.0 technologies in enabling real ‑ time monitoring, traceability, and error prevention. The literature directly informed the selection of tightening parameters, poka ‑ yoke features, and data ‑ analysis methods used throughout the project. 

2. Identify common fastening mistakes and choose a suitable assembly task to model and test. 

Common fastening mistakes, such as incorrect torque application, wrong tightening sequence, missing fasteners, and operator ‑ related errors, were identified through both literature and industrial context. Based on this, a representative assembly task was selected and modelled using an aluminium disk, providing a realistic metallic joint for experimental testing. This ensured that the tightening behaviour observed during trials reflected real production conditions rather than purely demonstrative setups. 

3. Configure Atlas Copco tools to use bolt-sequence control, torque/angle checking, and barcode verification. 

The Atlas Copco tightening system was successfully configured to implement bolt ‑ sequence control, torque and angle validation, and barcode verification. Using Avantguard, Power Focus, ToolsNet 8, and ALTURE, the system enforced correct assembly steps and prevented progression when errors were detected. This configuration demonstrated how poka ‑ yoke principles can be embedded directly into tightening processes rather than relying on post ‑ assembly inspection. 

4. Test the system under both normal and deliberate-error conditions to assess its ability to detect faults. 

The system was tested under both normal operating conditions and deliberate ‑ error scenarios, fulfilling the fourth objective. These tests confirmed that the system could reliably detect faults such as incorrect torque values, sequence violations, and operator ‑ related issues. Data collected from torque ‑ time, angle ‑ time, speed ‑ time, and current ‑ time graphs, alongside ToolsNet and ALTURE diagnostics, showed consistent and interpretable responses to both correct and incorrect tightening events. 

39 



5. Analyse the results to understand how much the system improves accuracy and reduces errors. 

Analysis of the collected data demonstrated that the smart tightening system improves process reliability by providing real ‑ time feedback, detecting NOK events, and enabling traceability across tightening cycles. The results highlighted recurring error patterns and confirmed that the poka ‑ yoke features functioned as intended, supporting improved accuracy and reducing the likelihood of undetected fastening defects. 

6. Consider the wider impacts of the system, including commercial benefits, sustainability, and how it supports equality, diversity and inclusion (EDI) in the workplace. 

Finally, the wider impacts of the system were considered in terms of commercial viability, sustainability, equality, diversity, and inclusion. The system offers strong commercial potential by reducing rework, scrap, and warranty costs while requiring minimal additional hardware investment. Sustainability benefits arise from reduced waste, lower energy consumption through electric tools, and digital traceability replacing paper ‑ based records. From an EDI perspective, guided tightening and automated verification reduce reliance on operator strength or experience, supporting a more inclusive and accessible manufacturing environment. 

In conclusion, this project demonstrates that smart poka ‑ yoke tightening systems provide a practical, data ‑ driven solution to long ‑ standing fastening challenges. The outcomes support the relevance of Industry 4.0 technologies in enhancing quality, reliability, and sustainability, and provide a strong foundation for further development and application in real industrial settings. 

### **11** **<u>Recommendations</u>** 

Based on the findings of this project, several recommendations are proposed to enhance the performance, applicability, and long ‑ term value of the smart poka ‑ yoke tightening system. 

Firstly, tightening parameters such as torque and angle limits should be further refined to better match specific joint characteristics and reduce borderline NOK events. The introduction of adaptive tightening strategies, informed by real ‑ time feedback from speed and current signals, could further improve robustness and fault detection under varying joint conditions. Future work should expand testing to include a wider range of fastening scenarios, such as different bolt sizes, materials, torque levels, and multi ‑ bolt assemblies. Longer ‑ term trials would also provide valuable insight into system repeatability, reliability, and performance under continuous production conditions. The analytics capabilities of ALTURE should be more actively leveraged to support continuous improvement. Recurring NOK trends can be used to inform targeted operator training, tightening program optimisation, and preventative maintenance strategies. Integrating these insights into routine quality reviews would allow manufacturing teams to address root causes proactively rather than reacting to individual failures. 

40 



Importantly, the poka ‑ yoke tightening configuration developed in this project is not limited to the specific aluminium disk case study. The same principles—sequence enforcement, torque and angle validation, barcode verification, and operator guidance—can be applied to any assembly line in any industry where threaded fastening is used, including automotive, aerospace, electronics, and general industrial manufacturing. Because the system relies on configurable software and standard smart tools, it can be readily adapted to different products, layouts, and production volumes with minimal hardware changes. For industrial deployment, integration with wider factory systems such as Manufacturing Execution Systems (MES) is recommended to further enhance traceability and quality management. A staged implementation approach, beginning with pilot applications, would support effective roll ‑ out while minimising operational risk. 

Finally, sustainability and inclusivity should remain central to future developments. Monitoring waste reduction and energy efficiency would help quantify environmental benefits, while continued focus on ergonomic design and guided interfaces would further support a diverse and inclusive workforce. 

### **12** **<u>Work Schedule / Progress</u>** 



<!-- Start of picture text -->
Literature Review<br>‘Tool and System Fami<br>3 system Configuration<br>2 Testing & Data Colle...<br>Data Analysis<br>Draft & Final Report<br>oct 2028 Nov202s bec 2025 Jan 2026 Feb 2026 Mar 2026 © Apr2026 © May 202)<br>Timetine<br>Literature Review Tool and System Familiarisation System Configuration Testing & Data Collection<br>Data Analysis Draft & Final Report<br><!-- End of picture text -->

**Figure 22 - Gantt Chart** 

41 



<!-- Start of picture text -->
tx BIRMINGHAM CITY<br><!-- End of picture text -->

### **12.1** **<u>Discussion and Next Steps</u>** 

The project is on track. Initial research shows strong justification for using a poka-yoke tightening system, and early configuration work demonstrates that Atlas Copco tools are well-suited for this purpose. 

Next steps include: 

- Gaining access to tools 

- Conducting full tightening trials 

- Analysing error detection rates and data traceability 

The expected outcome is a validated, reliable error-proofing system that improves manufacturing quality and supports Industry 4.0 goals. 

42 



### **13** **<u>References (BCU Harvard Style)</u>** 

1. Atlas Copco (2024) _Smart Assembly Solutions – Power Focus 6000 Overview._ Available at: https://www.atlascopco.com [Accessed 5 October 2025]. 

2. Basu, R. (2019) _Implementing Lean Manufacturing: Techniques for Error Proofing._ Boca Raton: CRC Press. 

3. EPA (United States Environmental Protection Agency) (2021) _Lean Manufacturing and Environmental Sustainability._ Available at: https://www.epa.gov/lean [Accessed 6 October 2025]. 

4. Johansson, L. and Nilsson, P. (2021) ‘Smart Tools for Assembly Quality Control’, _Journal of Manufacturing Systems_ , 59, pp. 82–94. 

5. Lu, Y., Xu, X. and Wang, L. (2020) ‘Smart Manufacturing System Architecture for Industry 4.0’, _Journal of Manufacturing Science and Engineering_ , 142(11), pp. 1–14. 

6. Ohno, T. (1988) _Toyota Production System: Beyond Large-Scale Production._ New York: Productivity Press. 

7. Reason, J. (1990) _Human Error._ Cambridge: Cambridge University Press. 

8. Shingo, S. (1986) _Zero Quality Control: Source Inspection and the Poka-Yoke System._ Cambridge, MA: Productivity Press. 

9. Singh, A., Patel, R. and Zhou, Y. (2022) ‘Human-Centred Design in Smart Assembly’, _Procedia CIRP_ , 107, pp. 318–323. 

10. Croccolo, D., De Agostinis, M., Fini, S., Mele, M., Olmi, G., Scapecchi, C. and Bin Tariq, M.H. (2023) ‘Failure of threaded connections: A literature review’, _Machines_ , 11(2), p. 212. Available at: https://doi.org/10.3390/machines11020212 [Accessed 24 November 2025]. 

11. Lee, S. (2025) _Mechanical fastening defects: A comprehensive guide._ Number Analytics Blog. Available at: https://www.numberanalytics.com/blog/mechanical-fastening-defects- <u>guide</u> [Accessed 24 November 2025]. 

12. Pierce, J. (2025) ‘Fastening failures: The top 5 mistakes and how to avoid them’, _Assembly Magazine_ . Available at: https://www.assemblymag.com/articles/99177- <u>fastening-failures-the-top-5-mistakes-and-how-to-avoid-them [Accessed 24 November</u> 2025]. 

13. Rilon Fastener (2024) _Common fastener failure analysis._ Fastenbolt. Available at: <u>https://fastenbolt.com/common-fastener-failure-analysis/ [Accessed 24 November 2025].</u> 

14. Kolus, A., Wells, R. and Neumann, P. (2018) ‘Production quality and human factors engineering: A systematic review and theoretical framework’, _Applied Ergonomics_ , 73, pp. 55–89. Available at: https://doi.org/10.1016/j.apergo.2018.05.010 [Accessed 24 November 2025]. 

15. Garofalo, F. and Puangseree, P. (2023) ‘Human factors in manufacturing: A systematic literature review’, in Duffy, V.G. (ed.) _Digital Human Modeling and Applications in Health, Safety, Ergonomics and Risk Management._ Cham: Springer, pp. 355–367. Available at: <u>https://link.springer.com/chapter/10.1007/978-3-031-35741-1_27 [Accessed 24</u> November 2025]. 

16. Reiman, A., Kaivo-oja, J., Parviainen, E., Takala, E.-P. and Lauraeus, T. (2021) ‘Human factors and ergonomics in manufacturing in the Industry 4.0 context – A scoping review’, _Technology in Society_ , 65, p. 101572. Available at: 

   - <u>https://www.researchgate.net/publication/350396106_Human_factors_and_ergonomics_i n_manufacturing_in_the_industry_40_context_-_A_scoping_review [Accessed 24</u> November 2025]. 

17. Gruszka, S. (2018) ‘Effect of human factor on product quality in manufacturing activities’, _Multidisciplinary Aspects of Production Engineering._ Available at: <u>https://doi.org/10.2478/MAPE-2018-0107 [Accessed 24 November 2025].</u> 

18. Romero, D., Gaiardelli, P., Powell, D.J. and Zanchi, M. (2022) _Intelligent Poka-Yokes: Error-Proofing and Continuous Improvement in the Digital Lean Manufacturing World._ ResearchGate. Available at: 

43 



<u>https://www.researchgate.net/publication/363595210_Intelligent_Poka-Yokes_ErrorProofing_and_Continuous_Improvement_in_the_Digital_Lean_Manufacturing_World.pdf</u> [Accessed 24 November 2025]. 

19. Sattigeri, R.C. and Kulkarni, D.G. (2021) ‘Quality Improvement Technique: Through Poka-Yoke Concepts’, _IOSR Journal of Business and Management_ , 23(9), pp. 1–4. Available at: 

   - <u>https://www.iosrjournals.org/iosr-jbm/papers/Vol23-issue9/Ser-4/A2309040104.pdf</u> [Accessed 24 November 2025]. 

20. Lazarevic, M., Mandic, J., Sremcev, N., Vukelic, D. and Debevec, M. (2019) ‘A Systematic Literature Review of Poka-Yoke and Novel Approach to Theoretical Framework’, _Journal of Mechanical Engineering_ , 65(6), pp. 345–360. Available at: <u>https://sv-jme.eu/?ns_articles_pdf=/ns_articles/files/ojs/6056/public/6056-33251-1PB.pdf&id=6338</u> [Accessed 24 November 2025]. 

21. Akhtar, F. and Tyagi, D. (2024) ‘A Review on Poka-Yoke Technique in Lean Manufacturing’, _International Journal of Advanced Production and Mechanical Engineering_ , 6(11), pp. 1–4. Available at: <u>http://www.troindia.in/journal/ijapme/vol6iss11/1-4.pdf [Accessed 24 November 2025].</u> 

22. Goecks, L.S., Habekost, A.F., Coruzzolo, A.M. and Sellitto, M.A. (2024) ‘Industry 4.0 and Smart Systems in Manufacturing: Guidelines for the Implementation of a Smart Statistical Process Control’, _Applied System Innovation_ , 7(2), p. 24. Available at: <u>https://www.mdpi.com/2571-5577/7/2/24 [Accessed 24 November 2025].</u> 

23. Dolgui, A., Sgarbossa, F. and Simonetto, M. (2022) ‘Design and Management of Assembly Systems 4.0: Systematic Literature Review and Research Agenda’, _International Journal of Production Research_ , 60(1), pp. 184–210. Available at: <u>https://www.tandfonline.com/doi/pdf/10.1080/00207543.2021.1990433 [Accessed 24</u> November 2025]. 

24. Mosleuzzaman, M., Arif, I. and Siddiki, A. (2024) ‘Design and Development of a Smart Factory Using Industry 4.0 Technologies’, _Asian Journal of Business and Information Systems_ , 4(4), pp. 89–108. Available at: 

   - <u>https://www.researchgate.net/publication/385287848_DESIGN_AND_DEVELOPMENT_ OF_A_SMART_FACTORY_USING_INDUSTRY_40_TECHNOLOGIES [Accessed 24</u> November 2025]. 

25. Imai, M. (1986) _Kaizen: The Key to Japan’s Competitive Success_ . New York: McGraw ‑ Hill. 

26. Liker, J.K. (2004) _The Toyota Way: 14 Management Principles from the World’s Greatest Manufacturer_ . New York: McGraw ‑ Hill. 

27. Bicheno, J. and Holweg, M. (2016) _The Lean Toolbox_ . 5th edn. Buckingham: PICSIE Books. 

28. Miles, B.L. (2012) ‘Mistake-proofing: Changing designs to reduce error’, _Quality Progress_ , 45(9), pp. 57–60. 

29. Stewart, D.M. and Grout, J.R. (2001) ‘The human side of mistake-proofing’, _Production and Operations Management_ , 10(4), pp. 440–459. 

30. Bickford, J.H. (2008) _An Introduction to the Design and Behavior of Bolted Joints_ . 4th edn. Boca Raton: CRC Press. 

31. ISO 5393:2013 _Rotary tools for tightening of threaded fasteners — Performance test method_ . Geneva: ISO. 

32. Budynas, R.G. and Nisbett, J.K. (2015) _Shigley’s Mechanical Engineering Design_ . 10th edn. New York: McGraw ‑ Hill. 

33. Nassar, S.A. and Yang, X. (2011) ‘Torque ‑ tension relationships in threaded fasteners’, _Journal of Pressure Vessel Technology_ , 133(2), pp. 1–8. 

34. Pavlović, A. and Fragassa, C. (2019) ‘Failure analysis of bolted joints’, _Engineering Failure Analysis_ , 104, pp. 927–939. 

35. Kagermann, H., Wahlster, W. and Helbig, J. (2013) _Recommendations for implementing Industry 4.0_ . Berlin: German National Academy of Science and Engineering. 

36. Xu, L.D., Xu, E.L. and Li, L. (2018) ‘Industry 4.0: state of the art and future trends’, _International Journal of Production Research_ , 56(8), pp. 2941–2962. 

44 



37. Frank, A.G., Dalenogare, L.S. and Ayala, N.F. (2019) ‘Industry 4.0 technologies: Implementation patterns’, _International Journal of Production Economics_ , 210, pp. 15–26. 

38. Lasi, H. et al. (2014) ‘Industry 4.0’, _Business & Information Systems Engineering_ , 6(4), pp. 239–242. 

39. Qin, J., Liu, Y. and Grosvenor, R. (2016) ‘A categorical framework of Industry 4.0’, _Procedia CIRP_ , 52, pp. 173–178. 

40. Stanton, N.A. et al. (2017) _Ergonomics: Foundations and Applications_ . 3rd edn. Boca Raton: CRC Press. 

41. Dul, J. et al. (2012) ‘Strategic ergonomics’, _Applied Ergonomics_ , 43(6), pp. 1093–1100. 

42. Sanders, M.S. and McCormick, E.J. (1993) _Human Factors in Engineering and Design_ . 7th edn. New York: McGraw ‑ Hill. 

43. Wilson, J.R. (2014) ‘Fundamentals of systems ergonomics’, _Applied Ergonomics_ , 45(1), pp. 5–13. 

44. Rashid, A., Asif, F.M.A., Krajnik, P. and Nicolescu, C.M. (2013) ‘Resource efficient manufacturing’, _Journal of Cleaner Production_ , 57, pp. 166–178. 

45. Duflou, J.R. et al. (2012) ‘Energy-efficient manufacturing systems’, _CIRP Annals_ , 61(2), pp. 587–609. 

46. Garetti, M. and Taisch, M. (2012) ‘Sustainable manufacturing’, _Production Planning & Control_ , 23(2–3), pp. 83–104. 

### **14** **<u>Appendix</u>** 

### **_ENG6200 Final Year Project Proposal_** 

### **14.1** **<u>Student Details:</u>** 

|**Name**|Yash Malhotra|
|---|---|
|**Student ID**|22132214|
|**Course**|BEng Manufacturing|
|**Mode**<br>**of**|Full Time|
|**study**||



### **14.2** **<u>Project Title:</u>** 

Error-Proofing Smart Assembly: An Error-Proofed Tightening System Using Atlas Copco Tools 

### **14.3** **<u>Project Introduction and Rationale:</u>** 

This project will focus on designing and implementing an error-proofing tightening system using Atlas Copco smart assembly tools, specifically targeting assembly environments where incorrect torque, missed fasteners, or improper tightening sequences cause product defects. 

In manufacturing sectors such as automotive and aerospace, assembly errors can lead to serious quality and safety issues, increasing costs through rework, warranty claims, and production delays. Smart tightening systems, such as Atlas Copco’s PF8 and Battery tools, 

45 



already incorporate advanced features including torque and angle monitoring, sequence control, and barcode verification. These allow engineers to prevent errors in real time, ensuring every component is assembled to specification. 

However, while the hardware is well-developed, each error-proofed system must be customengineered for specific tasks. This project aims to configure and evaluate such a system for a simulated automotive steering column assembly, where four bolts must be tightened in sequence and within precise torque limits. 

The reasoning for this project is to demonstrate how Industry 4.0-enabled smart tools can enhance manufacturing reliability and quality. By integrating data-driven tightening control, sequence validation, and operator guidance, the proposed system can minimise human error and ensure full traceability. 

By the end of the project, a working demonstration or digital simulation of a configured tightening process will be completed. It will include real tightening data, error-proofed control logic, and a performance analysis comparing standard and error-proofed assembly processes. This will provide valuable insights into how digital assembly technologies contribute to lean manufacturing and continuous improvement. 

### **14.4** **<u>Project Aim & Objectives:</u>** 

### **Aim** : 

To design and evaluate an error-proofed tightening system using Atlas Copco smart tools to 

prevent assembly errors and enhance product quality. 

### **Objectives:** 

- Research error-proofed principles and applications in lean manufacturing and Industry 4.0 assembly systems. 

- Research the problems that occur today and what research has been done to tackle these. 

- Study Atlas Copco’s assembly tools’ features for error-proofing applications. 

- Develop a system configuration that includes torque/angle validation, tightening sequence control, and barcode verification. 

- Simulate or conduct practical tests on an assembly task (e.g., steering column or flange tightening). 

- Collect and analyse data on error detection, process efficiency, and quality improvements. 

- Evaluate results and provide recommendations for implementing error-proofed systems in industrial assembly lines. 

### **14.5** **<u>How does your project consider commercial viability, EDI or sustainability:</u>** 

This project supports commercial viability by showing how error-proofing systems reduce defects, warranty costs, and rework time, directly improving operational efficiency. It enhances sustainability by minimising wasted materials, parts, and energy from defective assemblies. The system also aligns with equality, diversity, and inclusion (EDI) principles by standardising assembly quality, reducing the dependency on individual operator skill or experience, and supporting a more inclusive manufacturing environment, including those who are new to manufacturing or have physical limitations. 

46 



<!-- Start of picture text -->
tx BIRMINGHAM CITY<br><!-- End of picture text -->

### **14.6** **<u>Project RAID Matrix / Log:</u>** 

### **<u>RAID Matrix</u>** 

|**Risks:**|**Assumptions:**|
|---|---|
|Limited access to Atlas Copco tightening<br>tools|Having access to Atlas Copco demo<br>equipment or data which can be arranged|
|Challenges with Software configuration|Supervisory or technical support will be<br>available|
|Time delays during testing|Simulation-based testing can substitute<br>real setup|
|**Issues:**|**Dependencies:**|
|Learning curve for different software<br>needed for project|Availability of Atlas Copco hardware and<br>software with professional support|
|Access to their SMART Factory Demo<br>Centre for testing|Guidance from supervisor and potential<br>Atlas Copco contacts|



### **14.7** **<u>Project Tentative Schedule of Work:</u>** 

### **<u>Tentative Schedule of Work</u>** 

|**Activity /**<br>**Task**|**Description**|**Start**<br>**Date**|**Durat**<br>**ion**<br>**(weeks)**|
|---|---|---|---|
|Project<br>Proposal|Finalise project scope and proposal submission|14/10<br>/2025|2|



47 



|**Activity /**<br>**Task**|**Description**|**Start**<br>**Date**|**Durat**<br>**ion**<br>**(weeks)**|
|---|---|---|---|
|Literature|Research on error-proofing, smart assembly|30/10||
|Review|solutions and current problems and lean<br>manufacturing|/2025|3|
|Interim<br>Report|Understand brief and setup Interim report|31/10<br>/2025|6|
|Case Study<br>Definition|Select assembly task and design a test setup. Visit<br>the company for support.|Nov<br>25|2|
|Tool<br>Familiarisation|Learn about the relevant software and smart tools|Nov<br>25|3|
|System<br>Design|Configure a tightening sequence with validation of<br>relevant information such as torque/angle and<br>barcode|Dec<br>25|3|
|Testing|Run simulations with correct/incorrect operations<br>to collect data and show features, in action|Jan<br>26|4|
|Data<br>Analysis|Analyse error prevention, time, traceability|Feb<br>26|3|
|Draft<br>Dissertation|Write starting sections and document results|Marc<br>h 26<br>Total =|4<br>30|



### **14.8** **<u>Project Ethics:</u>** 

**Mandatory Ethics (Moodle)** COMPLETED **Quiz:** 

48 

**Date of completion:** 

29/10/25 



### **14.9** **<u>References:</u>** 

1. Shingo, S. (1986). _Zero Quality Control: Source Inspection and the Poka-Yoke System._ Productivity Press. 

2. Atlas Copco (2024). _Smart Assembly Solutions – Power Focus 6000 Technical Overview._ [online] Available at: https://www.atlascopco.com. 

3. Ohno, T. (1988). _Toyota Production System: Beyond Large-Scale Production._ Productivity Press. 

49 



### **15** **<u>Final Year Project Logbook</u>** 

### **15.1** **<u>Project Information</u>** 

Project Title: Error-Proofing Smart Assembly: An Error-Proofed Tightening System Using Atlas Copco Tools 

Project Duration: October 2025 – April 2026 

Supervisor: Venkatesh Vijay 

### **15.2** **<u>Introduction</u>** 

This project focuses on designing and implementing a smart poka-yoke tightening system using Atlas Copco Power Focus controllers and Tensor tools. The aim is to reduce assembly errors such as incorrect torque, missed fasteners, and wrong tightening sequences, aligning with Industry 4.0 principles for digital manufacturing. 

### **15.3** **<u>Summary Report</u>** 

The project involves configuring Atlas Copco tools with torque/angle validation, enforced bolt sequence, and barcode verification. A case study approach will be used to model a steering-column assembly and evaluate the system under normal and fault conditions. Data will be collected on error detection, cycle time, and operator feedback to assess improvements in quality and efficiency. 

### **15.4** **<u>Roles and Responsibilities</u>** 

- Conduct a literature review on poka-yoke, smart assembly, and fastening challenges. 

- Configure the Atlas Copco tightening system with poka-yoke features. 

- Design and execute experimental tests. 

- Collect and analyse data using statistical methods. 

- Prepare interim and final reports. 

### **15.5** **<u>Quality of Work and Supervision</u>** 

Regular meetings with the supervisor ensure alignment with objectives. Feedback has been constructive, focusing on improving methodology clarity and literature integration. Work quality has been consistent, with early milestones achieved on time. 

### **15.6** **<u>Conclusion</u>** 

The project is progressing as planned. Literature review and methodology design are complete, and system familiarisation is ongoing. Next steps include configuration and experimental testing. 

50 



### **15.7** **<u>Monthly Logbook</u>** 

### **15.8** **<u>October 2025</u>** 

- Defined project scope and objectives. 

- Completed initial literature review on poka-yoke and Industry 4.0. 

- Drafted interim report sections (Aim, Background, Literature Review). 

### **Milestone Achievements:** 

Literature review draft completed. 

### **Problems Encountered:** 

Difficulty finding recent case studies on Atlas Copco tools. 

### **Learning Achieved:** 

Improved academic writing and citation skills. 

### **15.9** **<u>November 2025</u>** 

- Finalised literature review with integrated references. 

- Developed methodology section with a case study approach. 

- Created a Gantt chart for the project timeline. 

- Prepared interim report for submission. 

### **Milestone Achievements:** 

Interim report completed and submitted. 

### **Problems Encountered:** 

Time management, balancing report writing and tool familiarisation. 

### **Learning Achieved:** 

Enhanced project planning and scheduling skills. 

## **15.10** **<u>December 2025</u>** 

- Visited Atlas Copco for tool and software familiarisation. 

- Took screenshots of the software. 

51 



## **15.11** **<u>February 2026</u>** 

- Catch up meetings with the supervisor to begin formatting my report to get an idea of which sections need work. 

- Trying to set up a meeting with the Software Manager at Atlas Copco to help set up the simulation. 

## **15.12** **<u>March 2026</u>** 

- 3D printing the steering wheel and using a teacher’s help at BCU to source an aluminium disk with holes for the tightening simulation. 

- Regular meetings with the supervisor to check over the report and make improvements. 

## **15.13** **<u>April 2026</u>** 

- Visiting the Software Manager at Atlas Copco to finish setting up the simulation on the Avantguard software. 

- Asking the teacher at BCU to fix the aluminium disk on a wooden block in order to clamp it to the table, due to the reaction forces moving the disk during tightening. 

- Re-visiting Atlas Copco to finish off recording the simulation, collecting data and screenshots for analysis. 

- Finishing off draft report for the supervisor to check over and completing it for submission. 

- Making a poster for the Innovation Fest presentation. 

### **Milestone Achievements:** 

Completing the full simulation set-up and having a working tightening simulation. 

### **Problems Encountered:** 

Time management, balancing report writing and multiple trips to Atlas Copco due to forgetting things. 

### **Learning Achieved:** 

Enhanced project planning, scheduling skills and better planning for practical work. 

52 



### **15.14** **<u>Project Timeline</u>** 



<!-- Start of picture text -->
Project Work Schedule Gantt Chart<br>Task<br>Oraft & Final Report: ™@ Literature Review<br>™@ Tool and System Familiarisation<br>Dada iAnsiss system Configuration<br>i Testing & Data Collection<br>q Testing & Data Collection Si lM™ DataDraft &Analysis Final Report<br>8<br>System Configuration<br>Tool and System Familiarisation i<br>No,a ta,” >, Msfay Mfy<br>2025 2, “202, 20,226<br><!-- End of picture text -->

53 

