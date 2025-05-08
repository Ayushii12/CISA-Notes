# CISA-Notes

## Audit Planning
- A **step-wise approach** to be followed to conduct an audit
- Audit planning is the **initial** stage of the audit process
- Audit planning makes the audit process more **structured**
- Includes both **short-term** and **long-term** planning
- Audit plan should be reviewed and approved by **senior management**
  - Approved audit plan should be **communicated** to the following groups:
    - Senior management
    - Business functions and other stakeholders
    - The internal audit team 
- A well thought out audit plan helps the auditor:
  - Identify required resources
  - Estimate a budget
  - Focus on high-risk areas
- Important terms:
  - **Audit universe**: An inventory of all the **functions/processes/units** under the organization
  - **Qualitative risk assessment**: Risk is assessed using qualitative parameters such as **high, medium, and low**
  - **Quantitative risk assessment**: Risk is assessed using numerical parameters; for example, for a 50% chance of failure, the amount at risk is 1000$
  - **Risk factors**: Factors that have an impact on risk. The presence of such factors increases the risk, whereas their absence decreases the risk
- Steps:
  1. **Understanding the Business**
      - Learn how the company operates
      - Identify important processes
      - Understand how systems and applications are managed and controlled
  2. **Identifying Risks**
      - Determine what could go wrong
      - Spot potential problems in processes, systems, and operations
  3. **Setting Goals and Scope**
      - Define which areas of the business will be audited
      - Establish the timeframe for the audit
  4. **Audit Procedures**
      - Plan specific steps to gather evidence
      - Determine methods to assess systems and processes
  5. **Allocating Resources**
      - Ensure availability of skilled personnel and tools
      - Support efficient and effective audit execution




## Audit Charter
-  A **formal document** defining:
  - Internal audit’s **objective**:
    - Sets the expectations and objectives of the audit function
    - Which processes/departments should be audited?
  - **Authority**:
    - Grants the internal audit function the authority to access:
      - All relevant records, Physical properties and Personnel
    - Empowers auditors to carry out their duties without interference
  - **Responsibility**:
    - Specifies who the audit function reports to (usually the audit committee or senior management)
    - Defines responsibilities such as risk assessments, control evaluations, and compliance reviews
- **Actions** of the **audit department** is primarily influenced by audit charter
- An audit charter must be approved by **senior management**
- Audit charter should not
  - Be changed too often as it defines the objective of the audit function
  - Include things such as planning, resource allocation, and other details such as audit fees and expenses
- An audit charter should be reviewed minimum **annually** to ensure that it is aligned with business objectives




## Business Applications and Controls
- The IS auditor should have sufficient understanding of **overall architecture** and **technical specifications** of the various applications to plan a risk-based audit
- In understanding the **issues** and **current risks** facing the business, the IS auditor should focus on areas that are most **meaningful** to **management**
- The following are some of the widely used applications in business processes. The CISA candidate should be aware of the risks associated with each of them
  - Go over pages 35-42 in the book
 



## Internal control
- An internal control is a **process** used to **safeguard** the **assets** of an **organization**
  - Assets can include systems, data, people, hardware, or the reputation of the organization
- Internal controls help in achieving the objectives of the organization by **mitigating** various risks
- Internal controls are implemented through **policies, procedures, practices, and organizational structures**
- Internal controls provide **assurance** to **management** about the achievement of business objectives
- Through internal controls, risk events are **prevented**, **detected** and **corrected**
- Effective controls in an organization can be categorized into
  - **Preventive**: Prevent occurance of threat and **avoids** the impact of the threat
    - Examples of preventive controls include the following:
      - The use of qualified personnel
      - The segregation of duties
      - The use of SOPs to prevent errors
      - Transaction authorization procedures
      - Edit checks
      - Access control procedures
      - Firewalls
      - Physical barriers 
  - **Detective**: Detect the threat and reduces the potential impact of the threat
    - Examples of detective controls include the following:
      - Internal audits and other reviews
      - Log monitoring
      - Checkpoints in production jobs
      - Echo controls in telecommunications
      - Error messages over tape labels
      - Variance analysis
      - Quality assurance 
  - **Deterrent**: Issue a **warning** signal to **deter** a threat event
  - **Corrective**: **Minimizes** the impact of a threat event once it has occurred
    - Helps in restoring a business to **normal** operations
      - Examples of corrective controls include the following:
        - Business continuity planning
        - Disaster recovery planning
        - Incident response planning
        - Backup procedures
  - **Compensating**: Alternate measures employed to ensure that **weaknesses** in a system are not **exploited**
    - In many cases, a strong control in one area can compensate for a weakness in another area
- **Preventive Vs Deterrent Controls**:
  - When a preventive control is implemented, an intruder is **prevented** from performing an act
    - They **do not have a choice** in whether or not to perform the act
  - When a deterrent control is implemented, the intruder is given a **warning**
    - The intruder **has a choice**: either to act as per the warning or ignore the warning
  - Example: A locked door to a room is a preventive control. Intruders cannot go through the door. On the other hand, just a warning sign that says “No Entry” is a deterrent control. Intruders can ignore the warning and enter the room
- **Control Objective**:
  - The **reason** why a control is implemented
  - Control objectives are linked to **business** objectives
  - Focus on:
    - The **effectiveness** and **efficiency** of operational processes
    - Adherence to **regulatory requirements**
    - The **protection** of **assets**




## Risk-Based Audit Planning
- What is **Risk?**:
  - **Potential events** that may **impact** the entity
  - **Possibility of events** that could have **adverse effects** on an organization's financial, operational, or strategic goals
- **Vulnerabilities Vs Threats**
    |                 | **Vulnerability**                                              | **Threat**                                                    |
    |-----------------|----------------------------------------------------------------|---------------------------------------------------------------|
    | **Definition**  | A vulnerability is a **weakness** in a system                  | A threat is an element that **exploits a weakness**           |
    | **Control**     | A vulnerability **can be controlled** by the organization      | A threat is **not** in the control of the organization        |
    | **Source**      | Vulnerabilities are mostly **internal** elements               | Threats are mostly **external** elements                      |
    | **Examples**    | Weak coding, missing anti-virus, weak access control           | Hackers, malware, criminals, natural disasters                |
- 2 important formulas for Risk
  - **Risk** = Probability * Impact
  - **Risk** = A * V * T
    - A: value of assets
    - V: vulnerability of assets
    - T: threats to assets
- **Inherent Risk Vs Residual risk**
    |                | **Inherent Risk**                                                                  | **Residual Risk**                                             |
    |----------------|------------------------------------------------------------------------------------|---------------------------------------------------------------|
    | **Definition** | The risk that an **activity** poses, excluding any controls or mitigating factors  | The risk that **remains** after taking controls into account  |
    |                | Gross risk – the risk before controls are applied                                  | Net risk – the risk after controls are applied                |
- Some more Definitions:
  - **Inherent** risk: Risk that exists **before** applying a control
  - **Control** risk: Risk that **internal controls** fail to prevent or detect
  - **Detection** risk: Risk that **internal audits** fail to prevent or detect
- What is **Audit-Risk?**:
  - When an auditor is **not** able to detect material errors during the audit process
  - Structured Approach To Minimize Audit-Risk
    - **1.** Acquire **Pre-Audit** Requirements
      - Understand the relevant **industry** and **regulatory requirements**
      - Gain insights into the **specific risks** associated with the business
      - Review outcomes from **previous audits** 
    - **2.** Assess **Internal Controls**
      - Gather information about the **internal control environment procedures**
      - Evaluate **control risk** (risk that controls may not prevent/detect errors)
      - Understand **detection risk** (risk that audit procedures may fail to detect issues)
    - **3.** Perform Compliance Testing
      - Identify **key controls** to be tested
      - Evaluate whether the controls are **functioning effectively**
    - **4.** Conduct Substantive Testing
      - Ensure testing includes:
        - Analytical procedures
        - Detailed testing of account balances
        - Other relevant verification methods
- **Advantages** of Risk based Audit Planning:
  - **Reduces** the risk that arises during an audit
  - Helps to identify issues at an **early** stage
  - Helps an organization identify any major **deviation from contractual and legal requirements**
  - Promotes **preventive controls** over reactive measures
- **Risk Assessment**
  - Risk assessments should be conducted at **regular intervals** to account for **changes** in risk factors
    - The risk assessment process has an **iterative** life cycle
  - Also, it is important to determine the **risk appetite** of the organization as it helps to **prioritize** various risks for mitigation
  - Steps
    - Step 1: Identification of critical assets and processes
    - Step 2: Identification of relevant risk, that is, vulnerabilities and threats
    - Step 3: Conducting an impact analysis (either qualitative or quantitative)
    - Step 4: Prioritizing the risk
    - Step 5: Risk treatment
- **Risk Response**
  - Risk **appetite** of the organization in question determine the **risk response** method
  - 4 main risk response methodologies:
    - Risk **mitigation/reduction**: Take some action to mitigate/reduce the risk
    - Risk **avoidance**: Change the strategy or business process to avoid the risk
    - Risk **acceptance**: Decide to accept the risk
    - Risk **transfer**: Transfer the risk to a third party: insurance is the best example
  - It is not always feasible to mitigate all the risks at an organizational level
    - A risk-free enterprise is an illusion
