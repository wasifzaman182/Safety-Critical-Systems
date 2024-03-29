FUP# Safety-Critical-Systems
This Repo will have all topics of safety-critical systems which is being taught in the HIS program at Frankfurt University

# Complexity in software development 
    --> Complexity in software development refers to the complex nature of designing, implementing, and maintaining software that plays a crucial role in ensuring a system's safety and       
        reliability.

--> Here are the some aspects

### Stringent Requirements 
    --> SCSs often have stringent and precise requirements that must be met.
    --> These requirements come from regulatory bodies, industry standards, or specific safety standards applicable to the domain.

### Integration and Compliance
    --> SCS is subject to rigorous certification processes to ensure it complies with safety standards.
    --> The documentation and evidence required for certification can significantly increase the complexity of the development process.

### Fault Tolerance and Redundancy
    --> Building bag/error-free systems with redundancy is common in SC Applications.
    --> Implementation and testing redundancy mechanisms, such as backup systems or failover strategies, add complexity to the software architecture. 

### Real-time constraints 
    --> SCS meeting deadlines and response time requirements add complexity to software design

### Verification and Validation
    --> V&V for SC software are extensive.
    --> Rigorous testing, simulation, and formal verification methods are often used to ensure that software behaves correctly under all conditions.
    
    --> Integrating the legacy systems into new systems adds complexity
    --> Human Factors, trying to design user-friendly systems add complexity to the systems
    

# Complexity Metrics in SCS
    --> Complexity metrics in SCS are measures used to quantify the intricacy(detail Small part of a system) and intricacies of the software or system design.
    --> These metrics help assess the potential challenges and risks of managing and maintaining safety-critical software.

Below are some of them.

## Halstead Complexity Metrics
    Developed by Maurice Halstead, these metrics include measures such as program length, vocabulary, volume, difficulty, and effort. They provide insights into the complexity of software 
    based on the number of operators and operands.

## McCabe's Complexity (or Cyclomatic Complexity) Metrics
    Derived from Thomas J. McCabe's work, these metrics quantify the complexity of a program by counting the number of decision points and loops. A higher value indicates a more complex code 
    structure.

## Depth of Inheritance Tree (DIT)
    DIT measures the number of levels in the inheritance hierarchy for a class. In safety-critical systems, excessive inheritance depth can lead to increased complexity and potential 
    difficulties in understanding and maintaining the software.

## Fan-In and Fan-Out
    Fan-In measures the number of functions or methods that call a particular function or method. Fan-Out measures the number of functions or methods called by a specific function or method.

## Coling and Cohesion Metrics
    Metrics related to the coling and cohesion of software components provide insights into how interconnected and independent different system parts are. Low coling and high 
    cohesion is generally desirable in safety-critical systems.

## Component Interactions
    Analyzing the number and nature of interactions between components or modules can provide insights into the potential complexity of the system's behaviour.

## Cyclomatic Complexity (CC):
    Definition: Cyclomatic Complexity is a metric developed by Thomas J. McCabe that quantifies the complexity of a program by measuring the number of independent paths through the source code. It provides insights into the software's structural complexity based on the control flow of the program.
    
    Calculation: The cyclomatic complexity is calculated using the formula:
    CC=E−N+2P
    where:
    E is the number of edges in the program's control flow graph.
    N is the number of nodes in the graph.
    P is the number of connected components (typically 1 for a well-structured program)
    
    Considerations:
    --> CC is used to identify potential areas that may benefit from additional testing.
    
    --> Reducing cyclomatic complexity can enhance code maintainability.
    --> It is just one of many metrics used in software analysis, and it is often used in conjunction with other metrics for a more comprehensive evaluation of software quality and safety.
  

# Modern risk in safety-critical software
--> A range of risks due to the evolving tech landscape and increased complexity in their design and deployment.
  Some of the key risks include

### Cybersecurity Threats
    Unauthorized access, data breaches, and cyber-attacks can compromise the integrity and safety of software systems.

### Software Complexity
    The complexity of modern safety-critical software continues to grow with advanced functionalities, integration of artificial intelligence, and intricate control systems. Increased       
    complexity can lead to challenges in understanding, testing, and ensuring the reliability of the software.

### Autonomous Systems Risks
    Developing and deploying autonomous systems, such as autonomous vehicles and drones, introduce new risks. Issues related to perception, decision-making algorithms, and the 
    ability to handle unforeseen scenarios poses challenges in ensuring the safety of these systems

### Machine Learning and AI Risks:
    Safety-critical systems incorporating machine learning and artificial intelligence algorithms face challenges in ensuring the predictability and reliability of AI-driven decisions. 
    Understanding the behaviour of complex learning systems and validating their safety becomes crucial.

### Data Integrity and Quality
    Safety-critical systems often rely on data for decision-making. Ensuring the integrity and quality of data, especially in dynamic and uncertain environments, is a challenge. Incorrect or 
    compromised data can lead to incorrect system responses.

### Regulatory Compliance Challenges
    Evolving regulations and standards for safety-critical systems can pose challenges in maintaining compliance. Adapting to changing regulatory requirements and ensuring that systems meet 
    the latest safety standards are ongoing concerns.

### Environmental Factors
    Safety-critical systems operating in challenging environments, such as extreme weather conditions or hostile territories, face additional risks. Adapting to diverse environmental factors     and ensuring the robustness of systems in such conditions is a concern.

# IEEE Code of Ethics 
    --> In recognition of the importance of our technologies in affecting the 
    quality of life throughout the world, and in accepting a personal obligation to our profession, its 
    members and the communities we serve, do hereby commit ourselves to the highest ethical and 
    professional conduct and agree: 

### To hold the highest standards of integrity, responsible behaviour, and ethical conduct in professional activities.
    1. Prioritize the safety, health, and welfare of the public in professional activities.
    2. Strive to comply with ethical design principles and promote sustainable development practices.
    3. Protect the privacy of individuals and disclose factors that might pose risks to the public or the environment
    4. Improve public and individual understanding of the capabilities and societal implications of both conventional and emerging technologies, including intelligent systems.
    5. Avoid real or perceived conflicts of interest, and disclose them when they exist.
    6. Avoid engaging in unlawful conduct in professional activities and reject bribery in all its forms
    7. Seek, accept, and offer honest criticism of technical work. Acknowledge and correct errors. Be honest and realistic in making claims or estimates based on available data. Credit properly the contributions of others.
    8. Maintain and improve technical competence. Undertake technological tasks for others only if qualified by training or experience, or after full disclosure of pertinent limitations.
    9. Make the rules simple to understand. This emphasizes clarity and accessibility in ethical guidelines.

### To treat all persons fairly and with respect, to avoid harassment or discrimination, and to avoid injuring others. 
    1. Treat everyone fairly and with respect. Do not discriminate based on race, religion, gender, disability, age, national origin, sexual orientation, gender identity, or gender     
       expression.
    2. Do not engage in any form of harassment, including sexual harassment or bullying behaviour.
    3. Avoid causing harm to others, their property, reputation, or employment. Refrain from false or malicious actions, rumours, or any other verbal or physical abuse.

### To strive to ensure this code is held by colleagues and co-workers.
    1. to sport colleagues and co-workers in following this code of ethics, to strive to ensure the code is held, and to not retaliate against individuals reporting a violation.  

# Process for safety and reliability
    --> Ensuring safety and reliability in critical systems involves a systematic and rigorous process throughout the entire lifecycle of the system.
        Below is an overview 

### Requirements Analysis:
    --> Safety and Reliability Requirements: Clearly define safety and reliability requirements at the beginning of the project. These requirements should be specific, measurable, and 
        achievable.

### System Design:
    Failure Modes and Effects Analysis (FMEA): Identify potential failure modes of components and systems. Assess the impact of these failures on the overall system and prioritize them for 
    mitigation.

### Fault Tree Analysis (FTA): 
     Analyze how individual faults or failures contribute to system-level failures. This helps in understanding the relationships between different failure events.

### Redundancy and Diversity: 
    Incorporate redundancy and diversity in critical components to enhance reliability. Redundancy involves having backup systems, while diversity involves using different methods or 
    components to achieve the same function.

### Development and Implementation:
    1. Standards Compliance: Adhere to industry standards and regulations specific to safety and reliability. Compliance with standards ensures that the system meets established criteria for 
       safety and reliability.
    2. Testing and Validation: Conduct thorough testing, including functional testing, performance testing, and stress testing. Validation involves ensuring that the system meets the 
       specified requirements and operates reliably under normal and extreme conditions.

### Operational Phase:
    1. Monitoring and Maintenance: Implement continuous monitoring of system performance during its operational phase. Regular maintenance and inspections help identify and address potential 
       issues before they lead to failures.
    2. Incident Reporting and Analysis: Establish a system for reporting and analyzing incidents or failures. Learn from incidents to improve the safety and reliability of the system.
    3. Software and Firmware Updates: Keep software and firmware up-to-date with the latest security patches and improvements. Regular updates can address vulnerabilities and enhance system 
       reliability.

### Documentation and Training:
    1. Comprehensive Documentation: Maintain detailed documentation, including design documents, manuals, and incident reports. Comprehensive documentation aids in understanding the system's 
       architecture and behaviour.
    2. Training Programs: Provide training programs for operators and maintenance personnel. Well-trained personnel are better equipped to operate and maintain the system safely.

### Continuous Improvement:
    Lessons Learned: Collect and analyze data from incidents and failures to identify lessons learned. Use this information to implement improvements in processes, design, and operations.
    Feedback Loop: Establish a feedback loop that allows ongoing input from operators, maintainers, and other stakeholders. This feedback can help identify issues and improvement 
    opportunities.

# Process for high-integrity software and systems
    --> Developing high-integrity software and systems involves a systematic and disciplined process to ensure reliability, safety, and adherence to stringent quality standards. Below is a 
        generalized overview
 ### Requirements Analysis
     Clearly define and document high-level requirements, considering both functional and non-functional aspects such as safety, security, and reliability.
### Risk Analysis and Management
    --> Conduct a comprehensive risk analysis to identify potential threats and vulnerabilities. Develop strategies to mitigate or manage these risks, particularly those related to safety 
       and reliability.
### System Architecture Design
    --> Create a robust system architecture that meets the specified requirements. Consider redundancy, fault tolerance, and isolation mechanisms to enhance system integrity.
### Formal Specifications
    --> Use formal methods to specify the behaviour and properties of the software and system. Formal specifications provide a precise and unambiguous representation of system requirements.
### Coding Standards and Guidelines
    --> Enforce coding standards and guidelines to promote consistency, readability, and maintainability. Follow best practices for high-integrity software development, such as MISRA-C for 
        embedded systems.
### Verification and Validation
    --> Implement rigorous verification and validation processes, including static code analysis, dynamic testing, and model checking. Verify that the software meets its specifications and 
         validate its functionality in a real-world environment.
### Safety and Security Assessments
    --> Perform safety and security assessments to identify potential vulnerabilities and ensure compliance with relevant safety standards (e.g., ISO 26262 for automotive, DO-178C for 
        aviation).
### Configuration Management:
     --> Establish robust configuration management practices to control changes to software artifacts, track versions, and ensure traceability between requirements, design, and 
         implementation.
### Documentation
    --> Maintain comprehensive documentation, including design documents, requirements traceability matrices, test plans, and safety cases. Documentation is essential for understanding, 
        maintaining, and auditing high-integrity systems.
### Change Management:
    --> Implement a rigorous change management process to assess the impact of proposed changes on system integrity. Changes should be carefully evaluated and validated before implementation.
### Certification and Compliance:
    --> Seek certification from relevant regulatory bodies or standards organizations. Ensure compliance with industry-specific standards and regulations governing high-integrity systems.
### Continuous Improvement
    --> Establish a culture of continuous improvement. Collect feedback from operational experiences, incidents, and audits to drive improvements in processes, tools, and the overall system.

# Unified process and ICE61508

  **Note**
      1. The Rational Unified Process (RUP) described is a software engineering process
      2. It provides a disciplined approach to assigning and managing tasks and responsibilities within a development organization.
      3. Its goal is to ensure the production of high-quality software that meets the needs of its end users within a predictable schedule and budget.
      4. IEC61508 is accepted as a generic basis for standards in all industrial sectors and is the basis for newer reference literature like [25] [18] [24] within the development of safety- 
         critical systems.

## ICE61508
    1. IEC61508 is a standard for developing safety-critical software and a framework for developing domain-specific safety standards.
    2. The standard has an integrated approach to achieve and assess the functional safety of a system and all of its components.

The standard of ICE61508 is in 7 different parts but we will focus on 1 to 3

## Purpose and Scope
  ### primary purpose
      1. The primary purpose is to provide a ”unified approach” for all safety lifecycle activities that is rational and consistent.
      2. As such, the standard covers all lifecycle phases for all system components.
      3. A fundamental premise is the risk-based determination of safety integrity levels (SILs).

### Secondary purpose 
    1. The secondary purpose of IEC61508 is to facilitate the development of industry-specific standards, which have been successfully achieved. EN50128:1997, the MISRA
         Guidelines and the SEMSPLC Guidelines are examples of application-specific standards derived from IEC16508.

### Third purpose
     1. IEC61508 applies to any safety-related software which, as defined by Parts 1 and 2, includes: (a) software that is part of a safety-related system; (b) software that is used to   
        develop a safety-related system; and (c) the operating system, system software, communication software, human-computer interface (HCI) functions, utilities, and software engineering 
        tools used with (a) or (b) above.

## Definitions and concepts in ICE61508
    1.** ”safety”** is defined as freedom from unacceptable risk.
    2. **”risk”** is defined as the combination of the probability of occurrence of harm and the severity of that harm.
    3.** ”harm”** is defined as a physical injury or damage to people's health either directly or indirectly due to damage to property or the environment.
    4. **”A hazard”** is defined as the potential source of harm.
     This implies that to say something about safety, you have to identify hazards and their effects and show how these hazards are handled within the system- or not.

## Safety integrity and functional safety
    1. Safety integrity is like measuring how well a safety system does its job. It's about figuring out the chance that the system will do what it's supposed to do when needed.
    **Example:** If you have a safety system in a car that's meant to deploy the airbags during a crash, safety integrity would measure how likely it is that the airbags will indeed deploy 
     when a crash happens.

    2. Functional safety is all about making sure that a safety system can do the things it's supposed to do to keep things safe. It's about the system's ability to take the right actions to 
       prevent accidents or keep things under control.
    **Example:** Going back to the car example, if there's a safety system that helps the car stay on the road and avoid collisions, functional safety ensures that this system works as 
      intended to maintain a safe driving state.

### Safety lifecycle
     1. IEC61508 addresses the safety requirements in all lifecycle stages, from concept to decommissioning. The safety lifecycle in Figure 2.1 is a model for identifying the activities
     appropriate to the assessment of safety-related systems.

### A risk-based approach
    1. A risk-based approach is about being super careful, thinking ahead about what could go wrong, making smart choices to make things safer, proving that it works, and being responsible 
       for those decisions.
![2 1](https://github.com/wasifzaman182/Safety-Critical-Systems/assets/75499379/7ea24923-5054-436a-8012-a2d61a9f79a5)

## ALARP
 ### Tolerable Risk:
    1. Tolerable risk means finding a level of risk that we can live with or accept. It's about deciding how much risk is okay, considering the possible consequences of accidents.
    **Example:** Imagine you're building a playground. You want it to be fun but safe. Tolerable risk is like deciding on a level of excitement (risk) that kids can enjoy without getting 
      seriously hurt.

### ALARP (As Low As Reasonably Practicable):
    1. ALARP is about making risks as low as possible without going to extreme measures. It recognizes that, in some situations, it's not realistic to aim for zero risk, but we should do 
      everything reasonable to make things safe. [^]
    **Example**: Think of driving a car. You want to reduce the risk of accidents as much as possible (ALARP), but you also understand that you can't eliminate all risks. So, you wear a 
      seatbelt and follow traffic rules to make it as safe as reasonably possible.

### Determining Acceptable Risk:
    1. In Simple Words: Deciding what level of risk is acceptable is like weighing the benefits and efforts. If the benefits are huge, we might accept a bit more risk. If reducing risk 
       requires a lot of effort and the benefits are small, we might accept a bit more risk too.
    **Example:** When deciding safety measures for a new technology, like a smartphone, you consider how much people will benefit from it and how hard it would be to make it completely risky-- 
      free.
![2 2](https://github.com/wasifzaman182/Safety-Critical-Systems/assets/75499379/da4315c6-c25e-4a9a-8d21-f6692b410940)

## Safety Integrity Levels (SILs) 
  ### SIL Represents:
     SIL is like a safety target that helps make systems more reliable. It doesn't measure risk directly

  ### Safety Management:
     SIL guides how seriously we take safety in the development process. The higher the SIL, the more rigorous the safety measures we use

  ### Absolute Safety:
    Just because we reach a certain SIL doesn't mean the system is entirely safe. It gives us confidence but not a guarantee

  ### Risk Management:
    Steps like analyzing software risks, determining SIL, setting safety requirements, and controlling risks are all part of the process. Assessing remaining risks helps fine-tune safety 
    measures.

  ### Controlling Factors for Safety:
    IEC 61508 focuses on controlling factors like engineering techniques, software design, and quality assurance methods. These factors are matched to the required SIL level.

## Confidence of safety
  ### Plan Safety in Advance:
    Instead of assuming something is safe if it functions correctly, IEC 61508 advises planning for safety and confidence from the start.

 ### Independent Safety Requirements:
    Safety requirements should be separate from functional ones, stating clearly when and how they'll be met.

 ### Independent Validation:
    Safety requirements must be independently validated to ensure they work as intended.

 ### Avoiding Assumptions:
    Don't assume correct functionality guarantees safety. Validate safety independently and use external assessments for added confidence.

## Compliance
 ### "Shall" Indicates Strict Compliance:
    When a requirement uses "shall," it means it must be strictly followed to claim conformity with the standard.

 ### "Should" or "Recommended" Allows Flexibility:
    "Should" or "recommended" suggests a preferred course of action but doesn't exclude other possibilities. It's a suggestion, not a strict requirement. 

### Normative Elements Define Requirements:
    Normative elements outline provisions necessary for claiming compliance. They often contain both "shall" and "should.

### IEC 61508 Normative Elements:
    Parts 1, 2, 3, and 4 contain normative elements, setting out requirements for compliance. Parts 5, 6, and 7 don't have normative requirements.

### Informative Elements Provide Additional Info:
    Informative elements offer extra insights but aren't mandatory for claiming compliance. Text in informative elements doesn't include "shall."
# To be continued.............. page-no 21, topic 2.6 use of standard 


# Quantifying project and process management
    --> involves measuring, analyzing, and assessing various aspects to ensure efficiency, effectiveness, and successful outcomes. Below are some of them.

  ## Timeline and Milestones:
   ### Metrics:
     Project duration (start to finish).
     Milestone completion dates.
    
  ### Quantification:
    Calculate project duration against the planned timeline.
    Measure the variance between planned and actual milestone completion dates.

## Resource Utilization:
  ### Metrics:
    Work hours allocated.
    Actual work hours spent.

 ### Quantification:
     Compare planned vs. actual work hours.
     Calculate resource utilization rate.

## Cost Management:
 ### Metrics:
    Budget allocation.
    Actual project costs.

### Quantification:
    Measure cost performance against the budget.
    Analyze cost variances.

## Task and Activity Completion:
 ### Metrics:
    Planned vs. completed tasks.
    Task completion times.

 ### Quantification:
    Calculate task completion rates.
    Evaluate the time taken for task completion.

## Quality Metrics:
 ### Metrics:
    Defect rates.
    Customer satisfaction scores.

 ### Quantification:
    Quantify the number of defects per unit.
    Analyze customer feedback and satisfaction scores.

## Risk Management:
 ### Metrics:
    The number of identified risks.
    Risk mitigation effectiveness.
 ### Quantification:
    Quantify the impact and likelihood of identified risks.
    Measure the success of risk mitigation strategies.

## Communication Effectiveness:
 ### Metrics:
    Response time to emails and messages.
    Team collaboration metrics.

### Quantification:
    Quantify response times.
    Evaluate team collaboration through measurable indicators.

## Process Efficiency:
  ### Metrics:
    Process cycle time.
    Process improvement metrics.

### Quantification:
    Measure the time taken to complete a process cycle.
    Quantify improvements achieved through process changes.

## Customer and Stakeholder Engagement:
  ### Metrics:
    Customer/stakeholder feedback.
    Engagement metrics.

### Quantification:
    Quantify positive and negative feedback.
    Evaluate stakeholder engagement through measurable criteria.

## Project Performance Indices:
  ### Metrics:
    Earned Value (EV).
    Schedule Performance Index (SPI) and Cost Performance Index (CPI).

### Quantification:
    Calculate EV and compare it with the planned value.
    Assess SPI and CPI to measure schedule and cost performance.


# Quantification of the development process
     --> Quantifying the development process is crucial for assessing efficiency, identifying improvement areas, and ensuring successful outcomes. Here are key aspects

  ## Code Metrics:
   ### Metrics:
    Lines of code (LOC).
    Cyclomatic complexity.
    Code duplication.

  ### Quantification:
    Measure the size and complexity of the codebase.
    Identify and quantify duplicated code.

## Velocity and Burndown Charts:
  ### Metrics:
    Story points are completed per iteration.
    Remaining work over time.

### Quantification:
    Calculate the velocity based on completed story points.
    Monitor progress and remaining work through burndown charts.

## Defect Density:
 ### Metrics:
    Number of defects.
    Code churn (code changes).

  ### Quantification:
    Calculate defects per line of code.
    Assess the impact of code changes on defect density.

## Code Review Metrics:
  ### Metrics:
    Time spent on code reviews.
    Number of comments per review.

 ### Quantification:
    Measure the efficiency of code review processes.
    Quantify the feedback and discussion generated during reviews.

### Testing Metrics:
  ### Metrics:
    Test coverage.
    Number of test cases executed.

 ### Quantification:
    Quantify the percentage of code covered by tests.
    Measure the number of test cases executed.

## Deployment Frequency:
  ### Metrics:
    Number of deployments.
    Deployment frequency over time.

### Quantification:
    Quantify how often deployments occur.
    Monitor changes in deployment frequency.

## Lead Time and Cycle Time:
 ### Metrics:
    Lead time (time from idea to deployment).
    Cycle time (time from code commit to deployment).

 ### Quantification:
    Measure the duration of key development phases.
    Evaluate efficiency in moving from idea to deployment.

## Customer Satisfaction Surveys:
  ### Metrics:
    Net Promoter Score (NPS).
    Customer feedback ratings.

  ### Quantification:
    Quantify customer satisfaction through NPS and ratings.
    Analyze feedback to identify improvement areas.

## Agile Metrics:
  ### Metrics:
    Sprint burndown charts.
    Release burnup charts.

### Quantification:
    Monitor progress within sprints using burndown charts.
    Track overall project progress with burnup charts.

## Continuous Integration Metrics:
 ### Metrics:
    Build success rate.
    Build duration.

### Quantification:
    Quantify the percentage of successful builds.
    Measure the time taken for each build.

# Stages in process control
  ### Data Safety:
     1. Software-generated data is used for safety-critical decisions.
     2. Emphasis on the importance of data integrity in safety-critical systems.
     3. Software is used in design analysis, and safety-critical data is stored in databases.

  ### Abstraction from Physical Design:
     1. Software engineers are involved in system design.
     2. Common errors in operational software are often related to requirements.
     3. Completeness in requirements is highlighted as a particular challenge.
     4. Software failure modes differ from hardware, and software usually does what it is instructed to do.

  ### Safety vs. Reliability:
     1. Safety and reliability require different development approaches.
     2. Reliability, historically emphasized in hardware design, may not be sufficient for safety.
     3. Examples from FAA reports highlight the need for ultra-high reliability in safety-critical systems.

  ### Software Safety Basics:
     1. The challenge is determining how safe is "safe enough" without over- or under-designing a system.
     2. Thresholds must be established based on risk-based assessments and hazard analyses.
     3. Differentiates between demand mode (periodic or on-demand use) and continuous mode (continuous operation for an intended task).
        
   #### Demand Mode
        **Usage Pattern**: In demand mode, the system is used periodically or on demand.
        **Operational Characteristics**: The system operates intermittently based on specific needs or requests.
        **Examples**: A system might be activated or used when a certain condition occurs or when a user requests it. For example, an emergency response
                      system that is activated when an emergency button is pressed.
  #### Continuous Mode:
        **Usage Pattern:** In continuous mode, the system operates continuously for an intended task.
        **Operational Characteristics**: The system is designed to operate continuously without significant interruptions.
         **Examples:** Systems that are required to provide continuous monitoring or control, such as a safety-critical process control system in a
                       manufacturing plant or a continuous monitoring system for environmental conditions.
      
  ### Software Reliability Basics:
     1. Defines software reliability as a measure of confidence that software produces accurate, consistent, and repeatable results.
     2. Considerations under various operational loads and in the intended environment.

  ### The Problem to be Solved:
     1. Identifies the lack of appropriate constraints on design as the primary safety problem in computer-based systems.
     2. The role of the system safety engineer is to identify and enforce design constraints necessary for safety.

  ### Most Common Software Errors:
     1. Highlights that most safety-related software errors can be traced back to requirements rather than coding errors.
     2. Understanding the software process is crucial for the development of safety-critical software-intensive systems.

# ACM/IEEE Code of Ethics (The Role of the Software and Systems Engineer)
  ### Public: 
    1. Software engineers shall act consistently in the public interest.
     
 ### Client And Employer: 
    1. Software engineers shall act in a manner that is in the best interests of their client and employer consistent with the public interest.
 
 ### Product: 
    1. Software engineers shall ensure that their products and related modifications meet the highest professional standards possible.
 
 ### Judgment: 
    1. Software engineers shall maintain integrity and independence in their professional judgment.

 ### Management: 
    1. Software engineering managers and leaders shall subscribe to and promote an ethical approach to the management of software development and maintenance.
 
 ### Profession: 
    1. Software engineers shall advance the integrity and reputation of the profession consistent with the public interest.

 ### Colleagues: 
    1. Software engineers shall be fair to and supportive of their colleagues.
 
 ### Self: 
    1. Software engineers shall participate in lifelong learning regarding the practice of their profession and shall promote an ethical approach to the practice of 
     the profession.


# Capability Maturity Model Integration (CMMI)

  ### Objective: 
   To provide a structured view of process improvement across an organization.

  ### Types of Representations:
   #### Staged View: 
    1.  Follows a predefined and proven path with case study and ROI data. Emphasizes organizational improvement, and overall results are summarized in maturity levels.
  #### Continuous View: 
    1.  Offers maximum flexibility for the order of process improvement. It focuses on improvement within process areas, and improvement can occur at different rates.

### +SAFE Extension:
  #### Purpose: 
    An extension to the continuous representation of CMMI for Development with a focus on safety-critical systems (SCS).
   
  #### Added Process Areas:
   #### Safety Management: 
    Includes goals for developing safety plans, monitoring safety incidents, and managing safety-related suppliers.
   #### Safety Engineering: 
    Involves goals related to identifying hazards, analyzing hazards and performing risk assessments, defining and maintaining safety requirements, designing for safety, and supporting 
    safety acceptance.

## Key Points:
  #### Maturity Levels:
    Both representations (Continuous and Staged) share common discriminators regarding maturity levels.
 #### Integration: 
    CMMI can help integrate traditionally separate organizations, set process improvement goals, guide quality processes, and serve as a yardstick for appraising current practices.

### Benefits of +SAFE Extension:
    1. Identifies safety strengths and weaknesses early in the acquisition process.
    2. Explicitly addresses safety capabilities for product and service suppliers.

### Comparison:
    1. Continuous vs. Staged: While the continuous representation offers flexibility in the order of improvement and focuses on process areas, the staged representation follows a predefined path, emphasizing organizational improvement with results summarized in maturity levels.


# Software Engineering Body of Knowledge (SWEBOK)
    SWEBOK describes the generally accepted contents about software engineering. Its 15 knowledge areas (KAs) are,
 
 ## 1 Software Requirements
    1. Understanding what the software should do and the constraints under which it must operate.
    2. Specifying, and validating requirements, and managing them throughout the lifecycle of the project.
  
   #### Software Design: 
    1. Defining the architecture, components, interfaces, and other characteristics of a system or component. 
    2. Creating a plan that describes the structure and behaviour of the software, ensuring it meets the specified requirements. 
    3. Key aspects include architectural styles, design patterns, and user interface design.
    
   #### Software Construction: 
    1. Programming phase, where developers translate design into source code. 
    2. This phase requires a deep understanding of programming languages and development tools.
  
   #### Software Testing: 
    1. It includes test planning, design, execution, and evaluation. 
    2. The aim is to ensure that the software meets its requirements and is free of defects.
       
   #### Software Maintenance: 
    1. Correcting defects, improving performance or other attributes, and adapting to a changed environment.
    2. Maintenance is an ongoing activity and often requires more resources than the initial development.
       
   #### Software Configuration Management: 
    1. Involves identifying and organizing the configuration of software (source code, documentation, etc).
    2. Controlling changes and maintaining integrity and traceability throughout the software life cycle.
  
   #### Software Engineering Management: 
    1. Planning, coordinating, measuring, monitoring, controlling, and reporting software projects.
    2. Understanding project management principles, including risk management, planning, scheduling, resource allocation, and leadership.
  
   #### Software Engineering Process:
    1. Involves understanding software life cycle models, methodologies, process assessment and improvement, and project management.
       
   #### Software Engineering Models and Methods: 
     1. Encompasses various models and methods used in software engineering.
     2. Includes traditional and agile methodologies, modelling languages, and the design and analysis of algorithms.
  
   #### Software Quality: 
    1. Ensuring that software meets the required level of quality.
    2. Software quality is closely linked to software testing but has a broader focus, including the process and the product.
  
  #### Software Engineering Professional Practice
    1. Ethical, legal, and professional responsibilities of software engineers.
    2. Understanding codes of ethics, professional conduct, team dynamics, and effective communication within a software development team.
  
  #### Software Engineering Economics
    1. Understanding the financial and economic aspects of software engineering, such as cost estimation, cost-benefit analysis, and budgeting.
    2. Crucial for decision-making and assessing the viability of projects.
  
  #### Computing Foundations
    1. This chapter provides a foundation in computer science that supports software engineering. 
    2. Topics include algorithms, data structures, programming languages, and the theory of computation.
       
  #### Mathematical Foundations
    1. This includes the mathematical concepts necessary for software engineering, such as logic, sets, functions, algebra, and probability. 
    2. These concepts are fundamental in algorithm design and systems modelling.
  
  #### Engineering Foundations
    1. This covers the basic principles of engineering that are relevant to software engineering. 
    2. It includes topics like system engineering, control theory, and the application of scientific methods to software development.
    
## 2 Requirement Analysis
    1. Software Requirement Analysis is a crucial phase in software engineering, focusing on understanding and documenting user needs and system constraints.
    2. The primary goal is to translate high-level requirements into detailed specifications that serve as a foundation for the software development process.

 ### Requirement Classification
  #### Functional vs Nonfunctional
       1. Functional requirements specify what the system should do.
       2. Nonfunctional requirements describe how the system should operate.
  #### Priority and Scope
      1. Priority determines the essentiality of a requirement. 
      2. Scope refers to the extent to which a requirement affects the software and its components.
  #### Product or Process 
    1. Product requirements affect the software itself.
    2. Process requirements constrain the choice of contractor, software engineering process, or standards.
  #### Volatility/Stability Requirements
    Some requirements are likely to change during the software's life cycle.
  #### Derived or Imposed Requirements
    1. Derived requirements come from higher-level requirements.
    2. Imposed requirements are imposed by stakeholders or other sources

## 3. Conceptual Modeling 
   #### Purpose of Conceptual Models
       Conceptual models aid in understanding the problem and depicting a solution. They comprise models of entities from the problem domain, reflecting their real-world relationships and dependencies. 
  #### Factors Influencing Modeling Notation
     The choice of modeling notation is influenced by the nature of the problem, the software engineer's expertise, and the process requirements of the customer. It is essential to start by building a model of the software context to understand its operational environment and interfaces.

## 4. Architectural Design and Requirements Allocation
    Architectural design involves defining the overall structure of a system.
    **High-level decisions** Regarding data flow and storage, control flow and execution logic.
    **Quality Attributes** In terms of scalability, Maintainability, Reliability, security, and performance  
    **Mapping Requirements** Involves mapping each system requirement to the specific component responsible for fulfilling that requirement.
    **Traceability** Helps in validating that each requirement is addressed and tested by architectural components. 
    **Verification and Validation** Involves confirming that the system, as built meets the user’s needs.
    **Evolution and Changes** It helps In managing changes efficiently by understanding which components need modification or extension

## 5. Requirements Negotiation
    1. It concerns resolving conflicts between requirements, stakeholders, and resources. 
    2. It is important to prioritize requirements and plan for staged deliveries, taking into account detailed domain knowledge and good estimation skills

## 6. Formal Analysis
  ### Benefits of Formal Analysis
    1. Precision Mathematical models and notations help eliminate ambiguity and ensure a clear understanding of system behaviour.
    2. Verification of correctness early error detection
  ### Tool Support and Challenges
    1. Relies on theorem provers or model checkers.
    2. Limited automation; competence in formal reasoning needed
  ### Focus and Timing
    1. Counterproductive until business goals and requirements are clear.
    2. Formalize critical requirements for static validation.
 
 ## Conclusion
     In conclusion, software requirements analysis is a crucial process in the development of software systems. Understanding the dimensions of requirements, modelling notations, 
     architectural design, requirements negotiation, and formal analysis is essential for successful project outcomes. The careful classification, modelling, and negotiation of requirements  
     are key to delivering effective software solutions that meet the needs of stakeholders and users.

# V-Model – Software Engineering
    1. It executes sequentially in a V-shape. 
    2. It is also known as the Verification and Validation model. 
    3. The development of each step is directly associated with the testing phase. 
    4. The next phase starts only after completion of the previous phase i.e., for each development activity, there is a testing activity corresponding to it.
    
  ## V-Model Design:
   #### Requirements Gathering and Analysis: 
     The first phase of the V-Model is the requirements gathering and analysis phase, where the customer’s requirements for the software are gathered and analyzed to determine the scope of 
     the project.
  #### Design: 
    In the design phase, the software architecture and design are developed, including the high-level design and detailed design.
  #### Implementation:
     In the implementation phase, the software is built based on the design.
  #### Testing: 
     In the testing phase, the software is tested to ensure that it meets the customer’s requirements and is of high quality.
 #### Deployment:
    In the deployment phase, the software is deployed and put into use.
 #### Maintenance:
    In the maintenance phase, the software is maintained to ensure that it continues to meet the customer’s needs and expectations.
  **Note**
            The V-Model is often used in safety: critical systems, such as aerospace and defence systems, because of its emphasis on thorough testing and its ability to clearly define the 
             steps involved in the software development process.
 ![Vmodel](https://github.com/wasifzaman182/Safety-Critical-Systems/assets/75499379/3a0c6e3e-10f9-4428-9fcb-d43ff4812e1f)

 ## Different phases in a V-Model 
   ### Verification Phases:
       It involves a static analysis technique (review) done without executing code. It is the process of evaluation of the product development phase to find whether specified requirements            are met.
 There are several Verification phases in the V-Model:

   #### Business Requirement Analysis
        1. Initiates the development cycle by aligning product requirements with customer perspectives.
        2. Crucial for understanding and communicating with customers to clarify their needs.
        3. Acceptance test design planning is done during this phase for future acceptance testing.
   #### System Design:
       1. Begins after a clear understanding of product requirements.
       2. Enables comprehensive system design, beneficial for future test case execution.
   #### Architectural Design (High-Level Design - HLD):
       1. Specifies and comprehends architectural specifications.
       2. Technical approaches are evaluated for both technical and financial viability.
       3. Defines system architecture, modules, and communication between them.
       4. Integration tests can be developed during this phase.
  #### Module Design (Low-Level Design - LLD):
       1. Specifies detailed internal design for each system module.
       2. Ensures compatibility with other modules and external systems in the architecture.
       3. Unit tests are created based on internal module designs.
  #### Coding Phase:
       1. Involves writing code for system modules based on design specifications.
       2. Follows coding standards and principles.
       3. Code undergoes reviews and optimizations before final build integration.
       
### Validation Phases:
   #### Unit Testing:
        1. Unit Test Plans are developed during module design.
        2. Executed to eliminate bugs at the code or unit level.
  #### Integration Testing:
        1. Conducted after unit testing.
        2. Modules are integrated, and system communication is tested.
        3. Validate module interactions based on the architectural design.
  #### System Testing:
        1. Test the complete application for functionality, interdependency, and communication.
        2. Validates both functional and non-functional requirements.
  #### User Acceptance Testing (UAT):
        1. Performed in a user environment resembling the production environment.
        2. Ensures the delivered system meets user requirements and is ready for real-world use.

### Principles of V-Model
  #### Large to Small:
        1. Testing is performed in a hierarchical perspective, progressing from project requirements to High-Level Design and Detailed Design phases.
        2. Requirements become more refined and detailed as each phase is completed.
 #### Data/Process Integrity:
        1. Successful design requires the incorporation and cohesion of both data and processes.
        2. Process elements must be identified at each requirement.
 #### Scalability:
        1. V-Model is flexible and can accommodate IT projects of varying sizes, complexities, and durations.
 #### Cross Referencing:
        1. A direct correlation between requirements and corresponding testing activities is established.
### When to use? 
        1. Where requirements are clearly defined and fixed.
        2. The V-Model is used when ample technical resources are available with technical expertise.
        3. Small to medium-sized projects with set and specified needs are recommended to use the V-shaped model.
        4. Since it is challenging to keep stable needs in large projects, the project should be small.

### Advantages: 
        1. This is a highly disciplined model and Phases are completed one at a time.
        2. V-Model is used for small projects where project requirements are clear.
        3. Simple and easy to understand and use.
        4. This model focuses on verification and validation activities early in the life cycle thereby enhancing the probability of building an error-free and good quality product.
        5. It enables project management to track progress accurately.
        6. Clear and Structured Process: The V-Model provides a clear and structured process for software development, making it easier to understand and follow.
        7. Emphasis on Testing: The V-Model places a strong emphasis on testing, which helps to ensure the quality and reliability of the software.
        8. Improved Traceability: The V-Model provides a clear link between the requirements and the final product, making it easier to trace and manage changes to the software.
        9. Better Communication: The clear structure of the V-Model helps to improve communication between the customer and the development team.
### Disadvantages: 
        1. High risk and uncertainty.
        2. It is not good for complex and object-oriented projects.
        3. It is not suitable for projects where requirements are not clear and contain a high risk of changing.
        4. This model does not support iteration of phases.
        5. It does not easily handle concurrent events.
        6. Inflexibility: The V-Model is a linear and sequential model, which can make it difficult to adapt to changing requirements or unexpected events.
        7. Time-Consuming: The V-Model can be time-consuming, as it requires a lot of documentation and testing.
        8. Overreliance on Documentation: The V-Model places a strong emphasis on documentation, which can lead to an overreliance on documentation at the expense of actual development work.


# ICE 61508
        1. This standard consists of planning, designing, implementing and maintaining safety-related systems. This standard applies to either electrical/electronics/Programmable electronic safety-related systems.
        2. The fundamental concept is that any safety-related system must work correctly or fail in a predictable(safe) way.
 
 The standard has two fundamental principles
            1. An engineering process called the safety life cycle (FTA etc) is defined based on best practices to discover and eliminate design errors and omissions.
            2. A probabilistic failure approach to account for the safety impact of device failures. The risk is a function of the frequency (or likelihood) of the hazardous event and the event consequence severity. Many requirements                   apply to all technologies but there is a strong emphasis on programmable electronics, especially.

IEC 61508 has the following views on risks:
          1. Zero risk can never be reached, only probabilities can be reduced
          2. Non-tolerable risks must be reduced (ALARP) (The principle is that the residual risk shall be reduced as far as reasonably practicable).
          3. Optimal, cost-effective safety is achieved when addressed in the entire safety lifecycle

 #### Hazard and risk analysis
         1. The standard requires that hazard and risk assessment be carried out for bespoke systems: 'The EUC (equipment under control) risk shall be evaluated, or estimated, for each determined hazardous event'.
         2. The standard advises that 'Either qualitative or quantitative hazard and risk analysis techniques may be used' and offers guidance on many approaches. for details please check https://en.wikipedia.org/wiki/IEC_61508.


# Iterative Development and the Unified Process (UP)
![UP](https://github.com/wasifzaman182/Safety-Critical-Systems/assets/75499379/00860f9a-7de7-4dc7-a607-ef83d21216be)

      1. The unified software development process or unified process is an iterative and incremental software development process framework. The best-known and extensively documented refinement of the unified process is the rational unified process (RUP).
      2. The unified process is not simply a process, but rather an extensible framework which should be customized for specific organizations or projects. 
      3. The Unified Process (UP) is an iterative, partly agile process model, originally developed for projects using OOA/OOD.
      4. The elaboration, construction and transition phases are divided into a series of timeboxed iterations.
      5. Each iteration results in an increment, which is a release of the system that contains added or improved functionality compared with the previous release.   
      
### Architecture-centric
    1. The unified process insists that architecture sits at the heart of the project team's efforts to shape the system.
    2. One of the most important deliverables of the process is the executable architecture baseline which is created during the elaboration phase. This partial implementation of the system serves to validate the architecture and act as a foundation for the remaining 
       development.
### Risk-focused
    1. The unified process requires the project team to focus on addressing the most critical risks early in the project life cycle. The deliverables of each iteration, especially in the elaboration phase, must be selected to ensure that the greatest risks 
        are addressed first.
        
### Project lifecycle (phases of Unified process)
    1. Inception
    2. Elaboration (milestone)
    3. Construction (release)
    4. Transition (final production release)

  #### Inception phase
      1. It should be quite short
      2. If the inception phase is long then it may be an indication of excessive up-front specification, which is contrary to the spirit of the unified process.
      3. Develop an approximate vision of the system, make the business case, define the scope, and produce a rough cost estimate and project schedule.
 #### Elaboration phase
     1. The elaboration phase focuses on defining the system architecture and addressing known risks. It produces an executable architecture baseline and a detailed plan for the construction phase.
     2. The architecture is validated primarily through the implementation of an executable architecture baseline
     3. This is a partial implementation of the system which includes the core most architecturally significant components
     4. It is built in a series of small time-boxed iterations
     5. This phase includes the creation of use case diagrams, conceptual diagrams (class diagrams with only basic notation) and package diagrams (architectural diagrams).
#### Construction phase
    1. In this phase, the remainder of the system is built on the foundation laid in elaboration.
    2. System features are implemented in a series of short, time-boxed iterations
    3. Each iteration results in an executable release of the software. It is customary to write full-text use cases during the construction phase and each one becomes the start of a new iteration.
    4. Common Unified Modeling Language (UML) diagrams used during this phase include activity diagrams, sequence diagrams, collaboration diagrams, state transition diagrams and interaction overview diagrams.
#### Transition phase
    1. In this phase the system is deployed to the target users
    2. Feedback received from an initial release (or initial releases) may result in further refinements to be incorporated for several transition phase iterations
    3. The transition phase also includes system conversions and user training.

#### UP Best Practices and Concepts
     1. Central UP idea: Short, timeboxed, iterative, adaptive development.
     2. OOA/OOD/OOP/OOT
     3. High-risk, high-value issues are tackled in early iterations.
     4. Continuous engagement of users for evaluation, feedback, and requirements.
     5. Cohesive core architecture built in early iterations. →
     Architectural design is crucial for success!
     6. Continuous verification of quality: testing early, often and realistically.
     7. Application of use cases.
     8. Software model visualisation with UML.
     9. Careful requirements management.
     10. Practical change request and configuration management.
![spiritOfRUP](https://github.com/wasifzaman182/Safety-Critical-Systems/assets/75499379/002e8055-3697-454f-a044-aff6985cf4d1)

     
#### RUP & IEC61508 Combination

![RUPAndICE61508](https://github.com/wasifzaman182/Safety-Critical-Systems/assets/75499379/d210b537-6fe1-4aa9-888d-c06f2fa4d9d3)
![RupAndICE2](https://github.com/wasifzaman182/Safety-Critical-Systems/assets/75499379/8a2ea395-04ac-40f0-8ce2-7b029c3e3bb8)

#### 1st Example for Combination
    1. A hazard and risk analysis document has to be produced and  updated throughout the overall safety lifecycle.
    2. There are three objectives with the hazard and risk analysis:
         1. To determine the hazards and hazardous events of the EUC and EUC control system,
         2. To determine the event sequences leading to the hazardous events
         3. To determine the EUC risks associated with the hazardous events
  
    3. Are these requirements met by the default configuration of RUP?
        i. The information required by these requirements is not provided by RUP.
    4. Are these requirements in contradiction with RUP?
       i. These requirements only call for additional information and are therefore not in contradiction with RUP.
    5. How should these requirements be implemented within RUP?
       i. These requirements can be implemented within RUP as an activity- Plan Hazard and risk analysis- that is performed by a role- Safety Manager- and the result is an artifact- Hazard and risk analysis plan.

#### Enhanced RUP: Safety RUP
     1. Additional RUP discipline: Safety discipline
     2. The purpose of the Safety discipline is:
         1. to define the concept of the system,
         2. to define the scope of the system,
         3. to perform hazard and risk analysis,
         4. to specify the safety requirements of the system,
         5. to plan operation & maintenance of the system,
         6. to perform safety validation of the system.

# Software Process and Project Metrics
 #### General Benefits
     1. Process indicators enable a software engineering organization to gain insight into the efficacy of an existing process (i.e., the paradigm, software engineering tasks, work products, and milestones)
     2. they intend to provide indicators that lead to long-term software process improvement.
     3. Project indicators enable a software project manager to
            i. Assess the status of an ongoing project, 
            ii. track potential risks, 
            iii. uncover problem areas before they go critical,
            iv. adjust workflow or tasks, and
            v.  evaluate the project team’s ability to control the quality of software work products

 ####  Software Process Improvement
    1. The only way to improve any process is to measure specific attributes of the process, develop a set of meaningful metrics based on these attributes, and then use the metrics to provide indicators that will lead to a strategy for 
       improvement. 
       
## 1. Size-Oriented Metrics
     1. LOC measures are programming language dependent.
     2. LOC penalize well-designed but shorter programs.
     3. LOC cannot easily accommodate nonprocedural languages.
     4. TheuseofLOCinestimation requires a level of detail that may
     5. be difficult to achieve (i.e., the planner must estimate the LOC to
     6. be produced long before analysis and design have been completed)
     
## 2. Technical Metrics  --> Goals of Measuring 
    1.  Identify the Goal for the product/process/resource. This is the goal that your metrics customer is trying to achieve.
    2. Determine the Question(s) that will characterize how the goal is achievement will be assessed.
    3. Definet the metric (s) that will provide a quantitative answer to each question. Metrics can be objective (based solely on the object being measured) or subjective (based on the viewpoint taken as well as the object measured).

 ####  Different Approaches
     1. Complexity metrics
     2. McCall’s software metrics
     3. The Bangmetric
     4. Architectural Design metrics
     5. Coupling and Cohesion metrics
     6. CardandGlass metric
     7. Interface Design metric
     8. Halstead’s software science
     9. Testing metrics
     10 Object-Oriented metrics

# Requirements Traceability Matrix (RTM)
    1. Give each requirement item an ID
    2. Short title of the requirements item
    3. Add short Description: Functional, non-functional, safety, security, etc.
    4. Linkto requirements specification document
    5. Status!!!
    6. Signature of responsible team member!

# The Semantic Gap
 Classical Example: Ariane V Crash
    https://medium.com/dataseries/crash-and-burn-a-short-story-of-ariane-5-flight-501-3a3c50e0e284
    ####  Accident Root Causes
          i. Fault-tolerant design
         ii.  No checks on boundaries, or error propagation, ...
         iii. Reuse of software
         iv.  Verification and Validation
          v.  No testing with real data
          vi  Certification issues
        vii.  Software configuration management
        viii. Semantic Gap

     Software engineers must be knowledgeable and understand
        i. standard engineering practices,
        ii. scientific basics, and
       iii. system design decisions!

 Lufthansa A320 Warsaw
      Further causes:
          1. Two captains on the flight deck!
          2. Thin film of water on the runway that had not been cleared.
          3. Wheels aquaplaned, skimming surface, without gaining enough rotary speed to tell computer braking systems that the aircraft was landing.
          4. Sensors information did not trigger the software to declare a touchdown
          5. Computers (software!!!) refused to allow pilots to use aircraft’s braking systems. So did not work until too late.
          6. Still would not have been catastrophic if had not built a high bank at the end of the runway.
          
    Blaming pilots turns attention away from
        1. Why were pilots given out-of-date weather information?
        2. Design of computer-based braking system
        3. Ignored pilot commands
        4. Pilots were not able to apply braking systems manually
        5. Who has final authority? 
        6. Why allowed to land with water on the runway?
        7. Why was the decision made to build a bank at the end of the runway?

# Hazard Analysis
   #### Basics
            Hazard analysis investigates factors related to accidents
            1. Indevelopment to identify and assess potential hazards, and the conditions that can lead to them, so that the hazards can be eliminated or controlled.
            2. In operations to examine an existing system to improve its safety and to formulate procedures.
            3.  In licensing examine a planned system to demonstrate acceptable safety.
####  Hazard Analysis Methods
    1. Checklists
    2. Failure modes and effects analysis (FMEA)
    3. Fault tree analysis (FTA)
    4. Event tree analysis (ETA)

## Failure modes and effects analysis (FMEA)
    FMEA is a process to identify and prioritize potential failures in systems, processes, or products to prevent them from causing problems.

   #### FMEA involves the following steps
    1. Define the system or process
    2. Identify failure modes
    3. Determine failure effects
    4. Assign severity ratings
    5. Identify causes of failure
    6. Assign occurrence ratings
    7. Assign detection ratings
    8. Calculate risk priority numbers (RPN)
    9. Prioritize actions
    10. Implement actions
    11. Review and update

![FEMA](https://github.com/wasifzaman182/Safety-Critical-Systems/assets/75499379/5765ed06-7dda-4354-afe1-d6e8bcf81ef2)

#  Fault Tree Analysis (FTA) 
    1. FTA is a systematic method to analyze and assess the causes of undesirable events.
    2. means for analyzing causes of hazards, not identifying hazards
    3. Other techniques must have foreseen the top event. such as
        1. System Design --> Understanding the design and function of the system can highlight potential critical failure modes or events that need further analysis.
        2. Operational Experience--> Insights gained from the system's operational history, incidents, or near-misses can provide information about events that warrant attention in the FTA.
        3. Hazard Analysis Techniques -->  Previous hazard analyses, risk assessments, or safety studies may have already identified and specified the top event as a focus area for further analysis.
    4. uses Boolean logic to describe the combinations of individual faults 
    5. Each level lists the more basic events that are necessary and sufficient to cause the problem at the level above it.
![FTA2 drawio](https://github.com/wasifzaman182/Safety-Critical-Systems/assets/75499379/193a59b6-cef9-4661-a27b-141a6794cfd3)

####  FTA With Safety 
    1. SFTA identifies safety-critical interfaces and potentially hazardous software behaviour
    2. Understanding the minimum cut sets in a fault tree analysis is crucial because it helps identify weak points in the system design. These are combinations of events or failures that, if they occur together, could lead to the top 
       event (undesired outcome).
    3. Single-Point Failures Can Be Uncovered and Eliminated:
    4. Events that appear in multiple minimum cut sets are considered critical, as their failure can significantly impact the system. Focusing on these common events is essential for effective risk mitigation
    5. Common-cause failures, where multiple components fail due to a shared cause, may not be immediately apparent in fault tree analysis. I would need special attention to identify and address potential common-cause failure modes.
    6. If Common-Cause Failure Mode Detected, Elimination Is Easy
    7. Fault tree analysis provides a static snapshot of the system state and relationships between events. It may not capture the dynamic aspects of fault propagation, such as the sequence of events over time
    8. Fault Tree Is a Snapshot of the System State
    9. 35% of Actual In-Flight Malfunctions Not Identified or Not Identified as Credible
![FTA3](https://github.com/wasifzaman182/Safety-Critical-Systems/assets/75499379/9096f858-30ab-42f4-90b1-93e355a27a5d)

# Event Tree Analysis (ETA)
    1. Forward search to identify outcomes of an event
    2. It is necessary to know, where to start.
    3. Event tree from left to right
    4. Branches to two alternatives:
        i. Upper branch successful performance
        ii. Lower branch failure
    5. Includes probabilities
    6. Initial event characterized by frequency
    7. Secondary events are probabilities
    8. Elimination of impossible branches
    9. Determine the probability of negative outcomes resulting from an initiating event.
    10. Use detailed system information to construct the event tree diagram.
 #### Construction of Event Tree Diagram:
   ##### Initiating Event:
       1. Begins with an initiating event, often binary (success/failure).
       2. Consequences follow in a series of successes or failures.

  ##### Probability Calculation:
       1. Use fault tree analysis to calculate the probability of failures for intermediate events.
       2. Probability of success (ps) is calculated as ps = 1 - probability of failure (pf).
  ##### Event Tree Diagram:
       1. Models all possible pathways from the initiating event.
       2. Initiating event starts horizontally and branches vertically.
       3. Success/failure represented by vertical branches.
       4. Each event labeled with a tag (e.g., 1s for success, 1f for failure).
#### Steps for Event Tree Analysis:
   ##### Define the System:
       1. Establish system boundaries and components.
   ##### Identify Accident Scenarios:
       1. Assess the system to find potential hazards or accident scenarios.
   ##### Identify Initiating Events:
       1. Use hazard analysis to define specific initiating events.
   ##### Identify Intermediate Events:
       1. Identify countermeasures associated with each scenario.
   ##### Build Event Tree Diagram:
       1. Construct the event tree diagram outlining possible pathways.
   ##### Obtain Event Failure Probabilities:
       1. If failure probability is not obtained, use fault tree analysis.
  ##### Identify Outcome Risk:
      1. Calculate the overall probability of event paths and determine risk.
  ##### Evaluate Outcome Risk:
      1. Assess the risk of each path and determine acceptability.
  ##### Recommend Corrective Action:
      1. Develop design changes to mitigate unacceptable risks.
  ##### Document ETA:
      1. Document the entire process on the event tree diagrams.
      2. Update information as needed.
![Event_Tree_Diagram](https://github.com/wasifzaman182/Safety-Critical-Systems/assets/75499379/cb01fff2-7368-4d57-bb7e-573b7313f9cf)

#  Chain of Events Models
    1. This model helps analyze and understand the sequence of events that could lead to hazardous situations or accidents.
 #### Event Chain:
    1. The model identifies a series of events that can lead to a hazardous outcome. 
    2. These events are linked in a chain, where each event contributes to the overall risk.
#### Initiating Event:
    1. The chain typically starts with an initiating event, a failure, an error, or some unexpected circumstance.
    2. This event triggers the sequence that may lead to a safety-critical situation.
     e.g  1. A sensor failure in an aircraft's navigation system.
          2. An operator error in a nuclear power plant control room.
          3. An unexpected surge in demand for an online banking system.
          4. A software bug in a medical device      
#### Intermediate Events
    1. Following the initiating event, there are intermediate events in the chain.
    2. These events may involve system components, human actions, environmental factors, or other elements that contribute to the unfolding scenario.
#### Contributing Factors:
    1. The model considers various contributing factors at each stage of the chain.
    2. These factors can include design flaws, software errors, hardware failures, human errors, external conditions, etc.
#### Propagation of Events:
    1. The chain illustrates how events propagate and interact with each other.
    2. It shows the causal relationships between different elements, helping analysts understand the dynamics of the system.
#### Critical Points
    1. The model identifies critical points in the chain where the risk becomes significant.
    2. These critical points are often the junctures where preventive or mitigative measures can be applied to break the chain and prevent a hazardous outcome.
#### Risk Analysis:
    1. The CoE model is a valuable tool for risk analysis.
    2. By assessing the likelihood and consequences of each event in the chain, safety engineers can quantify and prioritize risks, informing decision-making for 
       safety improvements
#### Iterative Process:
    1. Safety analysis using the Chain of Events model is often an iterative process. 
    2. As more information becomes available or as system changes occur, the model can be revisited and updated to ensure its accuracy and relevance.

#### Limitations
   ##### Incorporating Social Systems
       1. It points out that technology and its underlying science are complemented by a social system that provides purpose, goals, and decision criteria.
       2. The implication is that accidents should be analyzed not only from a technical perspective but also considering the broader social context.
  ##### Limitations of the CoE Model
   ##### System Accidents
       1. The CoE model may have limitations when dealing with accidents involving entire systems. 
       2. These accidents could be influenced by complex interactions between various components and the overall system architecture.
  ###### Software Failures:
      1. The model might face challenges in adequately addressing software failures.
      2. Software is a critical component in many systems, and its failures may not always fit neatly into a linear chain of events.
 ##### Human Error:
      1. It points out that modelling human behaviour by breaking it down into individual decisions and actions might not be effective.
      2. Understanding human behaviour requires consideration of the broader physical and social context, as well as the value system in which it occurs.
#### Deviation from Normative Procedure vs. Established Practice:
    1. This suggests that human errors may occur not just from deviating from established norms but also from established practices. 
    2. It emphasizes the need to understand the context and the reasons behind deviations.

# Systems Theory
  ## Definitions
   #### System State:
      1. The system state at a specific time is defined as the set of relevant properties describing the system at that moment.   
   #### System Environment:
      1. The system environment comprises components external to the system whose behaviour can influence the system state.
   #### Abstract Model:
      1. The system is always considered an abstract model, emphasizing the conceptual representation rather than a concrete, physical entity.
 ## Foundation of Systems Theory
   #### Emergence and Hierarchy:
       1. Emergent properties at a given complexity level are irreducible and manifest differently on various levels.
       2. Safety is an emergent property in systems.
       3. Reliability and safety are distinct concepts, with reliability focusing on components' reliability, and safety being an emergent property.
  #### Communication and Control:
       1. Control in open systems necessitates communication.
       2. Imposing constraints on a level's activity is regulatory or control action.
       3. Optimization of individual components or subsystems may not lead to a system optimum.
 ## Concept of Emergence:
 #### Irreducible Properties:
        1. Emergent properties at a certain complexity level are irreducible and require a holistic understanding.
        2. Different levels of description reveal varied emergent properties.
        3. Safety is cited as an emergent property of systems.
 ## Control and Communication:
  #### Open Systems:
        1. In open systems, control implies the need for communication.
        2. Regulatory actions impose constraints on a level's activity.
        3. Optimizing individual components or subsystems may not lead to an overall system optimum.

# System-Theoretic Accident Model and Processes (STAMP)
    1. STAMP is a safety engineering framework used to analyze accidents and hazards systematically.
    2. The primary components of STAMP are integral to understanding and analyzing accidents from a systems perspective
    3. In STAMP, accidents are defined in terms of violations of safety constraints, which may result from
        i. system component failure(s),
        ii. environmental disturbances, and
        iii. dysfunctional interactions among (failing or nonfailing (!)) components.
<img width="709" alt="STPA_basic" src="https://github.com/wasifzaman182/Safety-Critical-Systems/assets/75499379/3b3d1406-27eb-4f74-a245-ed6a47ca3a59">

    3. In STAMP there are different levels such as 
        i. Constraints
        ii. Hierarchical levels of control
        iii. Process models
    let's explain one by one

#### Constraints 
    1. In STAMP, constraints are conditions or limitations imposed on the system's behaviour to ensure safety.
    2. Constraints play a crucial role in shaping the system's responses and actions.
    3. They can be both physical (e.g., speed limits for vehicles) and behavioural (e.g., operational procedures).
    for practical understanding please look into the notion document STPA part. 
#### Hierarchical Levels of Control
    1. STAMP introduces the concept of hierarchical levels of control to represent the different layers of decision-making within a system.
    2. The control hierarchy ranges from the highest (strategic) to the lowest (tactic and operational) levels.
    3. Each level contributes to the overall control of the system and influences its behaviour.
    for practical understanding please look into the notion document STPA part.
#### Process Models:
    1. Process models in STAMP represent the dynamic interactions and sequences of events within a system.
    2. These models illustrate how information flows, decisions are made, and actions are taken in response to various inputs.
    3. Understanding process models is crucial for identifying potential systemic issues leading to accidents.
Note: To understand it with the practical example which is related to ECG, please go to the notion document. 

## System Safety Plan
    1. Develop a tracking system within the SW and system configuration control structure to ensure traceability of safety requirements and their flow through 
       documentation.
    2. Establish the hazard auditing and log file.
    3. Develop a tracking system within SCM for tracking hazards and their resolution.
    4. Review lessons learned
    5. Establish certification and training requirements for personnel involved in the development, testing and operation
 #### Develop and review
     1. safety-related SW test plans,
     2. test descriptions,
     3. test procedures, and
     4. test cases.
 #### Perform safety analysis:
     1. Hazard analysis, e.g. STAMP
     2. HMI analysis
     3. analysis of interfaces between critical and non-critical components.

 ## System Design Tasks
     1. Update all analyses!
     2. Makesystemtradeoff studies.
     3. Ensure that identified hazards are being eliminated or controlled in the evolving design
     4. Tracesystem hazards into components!
     5. Again: Identify constraints on subsystems!
     6. Reviewandimprove test and evaluation procedures during the progressing project
     7.  Review training and operations plans.
     8. Evaluate any design changes for safety impact.
     9. Document all safety decisions and maintain all documents
     10.  Ensure that safety requirements are incorporated into
         i. system
         ii. subsystem-, and
         iii. HMI requirements.
 ## Implementation Tasks
     1. Again: Review and update the hazard analyses!
     2. Ensure that the SW engineers understand the software-related system safety requirements and constraints.
     3. Trace software safety requirements and constraints through the code.
     4. Revie wall designs to safety issues.
     5. Update testing and verification requirements.
     6. Review testing results.
     7. Trace back test results to system hazards.
     8. Again: Evaluate changes for safety impact.
     9. Design, update and evaluate training and operational procedures.
     10. Perform final evaluation of product design.
     11. Identify safety-critical
         i. components
         ii. classes/functions
         iii. data structures and variables
          to the SW developers!
## System Production and Deployment Tasks
    1. Update hazard analyses
    2. Perform safety evaluation and verification on system and subsystem level
    3. Perform safety inspections
    4. Ensure that safety-related information is incorporated into user/operator and maintenance documents
    5. Review change proposals for safety impact
    6. Perform final evaluation of the produced and deployed system
        i. Test at customer site
        ii. Flight tests
## System Operation Tasks
    1. Update and improve procedures
    2. Maintain an information feedback system
    3. Review hazard, incident, and accident analyses
    4. Conduct safety audits
    5. Review change and maintenance procedures

## Inadequate Control Actions
     In adequate control, actions fall into the following four general categories
 #### Not Provided
    1.  A required control action to maintain safety is not provided.
#### “Incorrectly Provided
    1. An incorrect or unsafe control action is provided that induces a loss.
#### Provided Too Early, Too Late, or Out of Sequence
    1. A potentially correct or adequate control action is provided too early, too late, or out of sequence
#### Stopped Too Soon
    1.  A correct control action is stopped too soon
![HazardFactor](https://github.com/wasifzaman182/Safety-Critical-Systems/assets/75499379/5b0f1531-6a90-444a-96a1-19d588d128c1)


# Software Hazard Analysis (Hazard Analysis as Part of Software Design)
    1. The system design may be changed to eliminate identified hazards which are affected by software or are not adequately handled by software, or to reduce the  
       hazards to acceptable levels, or to adjust the system architecture so that identified hazards are compensated by defense-in-depth
    2.  The software design may be changed to eliminate identified hazards or reduce them to acceptable levels.
    3. The quality of the software may be improved sufficiently to reduce the probability of a hazard to an acceptable level.
    4. The application system may be rejected if it is considered too hazardous
    5. General approach: Software hazard analysis should be a defined aspect of the software life cycle!
 #### Hazard Categories
 ![hazardCate](https://github.com/wasifzaman182/Safety-Critical-Systems/assets/75499379/22841129-f2be-42d2-8af6-787382cdbcf6)
![hazardLevels](https://github.com/wasifzaman182/Safety-Critical-Systems/assets/75499379/18ddd7d0-51a4-4bd6-bdcb-9fcd8d2a076f)
![HazardMatrix](https://github.com/wasifzaman182/Safety-Critical-Systems/assets/75499379/dbaca60f-b32b-4ae4-9632-625fb18e8532)

####  Output of Software Hazard Analysis
    1. A list of software hazards
    2. A criticality level for each hazard that can be affected by the software
    3. A criticality level for each software requirement.
    4. An analysis of the impact on hazards of the software when it operates correctly or incorrectly.
    5. Consequences of software hazards for system safety
    6. A list of software architectural design elements with assigned risk levels.
    7. Analysis of the impact on hazards of the software when the specified architecture is used.
    8. A list of design and coding constraints which are required to mitigate hazards associated with the architecture.
    9. Recommendations for design changes.
    10. Recommendations for increased analysis and testing to be carried out during detailed design V&V, code V&V and final system validation.
