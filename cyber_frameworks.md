### PII (Personally Identifiable Information)

- cyber risk management framework 
  - provides a standard approach to review strategic and operational activities and to facilitate a common understanding of the cyber risk management processes.   
  - Objective: - Define the process for the assessment and treatment of risks and define the acceptable level of risk.  
               - Apply risk management practices to enhance strategic, tactical, and operational decision making.  
    * The result from a framework are "controls"  
  - Controls: Apply risk management practices to enhance strategic, tactical, and operational decision making.  
              - They can be physical, administrative, or technical, and they are implemented to mitigate or eliminate risks to information security.  
      - ex. passwords, mFA, firewalls, IDS (intrusion detection system), IPS (intrusion prevention systems), encryption, backup systems, policies & procedures
   
  - In general, companies and organisations have a legal duty to protect the personal information they collect from their customers, employees, and others. If   they fail to adequately protect this information and a breach occurs, they may be held liable for any resulting damages.  
            - usually the governmental regulators will fine companies, rarely do individuals get payouts... usually just credit monitoring at best

  - cybersecurity measures and protocols (in order to mitigate legal liability)  
    - These measures may include regular security audits, employee training programs, and the use of strong passwords and encryption technologies.
   
    - Many organisations implement frameworks to establish a common language among themselves and their clients. For example, frameworks allow you to align   conversations with customers on what they want ‘good’ to look like.
   
  ### Framework Benefits
  - Risk management: Cybersecurity frameworks provide a structured approach to managing cybersecurity risks. By identifying and assessing risks, organisations can   prioritise their cybersecurity efforts and allocate resources more effectively.    
  - Compliance: Many organisations are subject to regulatory requirements and industry standards related to cybersecurity. Cybersecurity frameworks can help   organisations comply with these requirements and avoid legal and financial penalties for non-compliance.  
  - Consistency: Cybersecurity frameworks provide a consistent approach to managing cybersecurity risks across an organisation. This ensures that all departments   and employees are working towards the same goal and following the same procedures.  
  - Proactive: Cybersecurity frameworks promote a proactive approach to cybersecurity. By focusing on preventing cybersecurity incidents before they occur,   organisations can reduce the likelihood and impact of a cybersecurity breach.
  - Continuous improvement: Cybersecurity frameworks encourage organisations to continually review and update their cybersecurity policies and procedures to stay   ahead of emerging threats and technology. This helps organisations adapt to new risks and technologies and maintain their cybersecurity posture over time.
  - Cost-Effective: Cybersecurity frameworks can help organisations allocate resources more effectively by prioritising their cybersecurity efforts based on risk.   This can reduce the overall cost of cybersecurity while still providing adequate protection for sensitive information.  

### NIST (National Institute of Standards and Technology) Framework
  - develops cybersecurity standards, guidelines, best practices, and other resources to meet the needs of U.S. industry, federal agencies and the broader public.
    
###  Identify 
      - Identify critical enterprise processes and assets: most important assets that cannot stop, info remains accessible and accurate   
      - Document information flows: type, where it located, how it's used, contracts with external partners, etc  
      - Maintain hardware and software inventory: could just be a spreadsheet, but should include everything at the enterprise... where a hacker might first look
      - Establish policies for cybersecurity that include roles and responsibilities: These policies and procedures should clearly describe your expectations for               how cybersecurity activities will protect your information and systems, and how they support critical enterprise processes.
      - Identify threats, vulnerabilities, and risk to assets: Ensure risk management processes are established and managed to ensure internal and external threats           are identified, assessed, and documented in risk registers.
      
###  Protect
      - Manage access to assets and information: unique accounts for each employee, with mFA, and tight passwords, and manage/track physical assets  
      - Protect sensitive data: encryption of transferred data, delete old data, Consider utilizing integrity checking to ensure only approved changes to the data              have been made. 
      - Conduct regular backups  
      - Protect your devices: Consider installing hostbased firewalls and other protections such as endpoint security products. Apply uniform configurations to                 devices and control changes to device configurations, Ensure that there is a policy and that devices are disposed of securely.  
      - Manage device vulnerabilities: regularly update operating system and software, and possible tools to scan devices for vulnerabilities  
      - Train users: regularly update users: Regularly train and retrain all users to be sure that they are aware of enterprise cybersecurity policies   

### Detect
      - Test and update detection processes: develop and test processes for detecting unauthorized entities on networks and physical environment
      - Maintain and monitor logs: These logs record events such as changes to systems or accounts as well as the initiation of communication channels. 
      - Know the expected data flows for your enterprise: You are much more likely to notice when the unexpected happens    
      - Understand the impact of cybersecurity events: Communicating information on the event with appropriate stakeholders will help keep you in good stead in               terms of partners, oversight bodies, and others (potentially including investors) and improve policies and processes.  

### Respond
      - Ensure response plans are tested: This includes knowing any legal reporting requirements or required information sharing.
      - Ensure response plans are updated: Testing the plan (and execution during an incident) inevitably will reveal needed improvements.
      - Coordinate with internal and external stakeholders: Eveyrone should know the plan of action if something happens

### Recover
      - Communicate with internal and external stakeholders: Your recovery plans need to carefully account for what, how, and when information will be shared with           various stakeholders so that all interested parties receive the information they need but no inappropriate information is shared.  
      - Ensure recovery plans are updated: testing execution of the plan will improve employee and partner awareness and highlight areas for improvement
      - Manage public relations and company reputation: consider how you will manage public relations so that your information sharing is accurate, complete, and             timely – and not reactionary.  

### COBIT (Control Objectives for Information and Related Technology) Framework   ---- layered above NIST
  - Decision-making, Accountability, Measurement, Alignment with business value  
  - the audience of COBIT is: Executives, Boards, Risk & compliance, Internal audit, GRC teams
  - Who is accountable for access risk?... Is access control aligned with business risk tolerance? How is effectiveness measured? How are exceptions approved and         reviewed?
  - Governance: EDM – Evaluate, Direct, Monitor
                -Set direction
                -Approve risk appetite
                -Monitor performance
  - Management:
      APO – Align, Plan, Organize  
                  (strategy, risk management, policies)  
      BAI – Build, Acquire, Implement  
                  (projects, change management)  
      DSS – Deliver, Service, Support  
                  (operations, incident handling — overlaps strongly with NIST Respond/Recover)  
      MEA – Monitor, Evaluate, Assess  
                  (metrics, audits, continuous improvement)  
    
Knowing NIST = credibility with engineers and SOC  
Knowing COBIT = credibility with auditors, management, boards  

