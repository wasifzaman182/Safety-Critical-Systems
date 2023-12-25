# Safety-Critical-Systems
This Repo will have all topics of safety-critical systems which is being taught in the HIS program at Frankfurt University

# Complexity in software development 
--> Complexity in software development refers to the complex nature of designing, implementing, and maintaining software that plays a crucial role in ensuring a system's safety and reliability.

--> Here are the some aspects

## Stringent Requirements 
  --> SCSs often have stringent and precise requirements that must be met.
  --> These requirements come from regulatory bodies, industry standards, or specific safety standards applicable to the domain.

## Integration and Compliance
--> SCS is subject to rigorous certification processes to ensure it complies with safety standards.
--> The documentation and evidence required for certification can significantly increase the complexity of the development process.

## Fault Tolerance and Redundancy
--> Building bag/error-free systems with redundancy is common in SC Applications.
--> Implementation and testing redundancy mechanisms, such as backup systems or failover strategies, add complexity to the software architecture. 

## Real-time constraints 
--> SCS meeting deadlines and response time requirements add complexity to software design

## Verification and Validation
--> V&V for SC software are extensive.
--> Rigorous testing, simulation, and formal verification methods are often used to ensure that software behaves correctly under all conditions.

--> Integrating the legacy systems into new systems adds complexity
--> Human Factors, trying to design user-friendly systems add complexity to the systems





# Complexity Metrics in SCS
--> Complexity metrics in SCS are measures used to quantify the intricacy(detail Small part of a system) and intricacies of the software or system design.
--> These metrics help assess the potential challenges and risks associated with managing and maintaining safety-critical software.

Below are some of them.

## Halstead Complexity Metrics
Developed by Maurice Halstead, these metrics include measures such as program length, vocabulary, volume, difficulty, and effort. They provide insights into the complexity of software based on the number of operators and operands.

## McCabe's Complexity (or Cyclomatic Complexity) Metrics
Derived from Thomas J. McCabe's work, these metrics quantify the complexity of a program by counting the number of decision points and loops. A higher value indicates a more complex code structure.

## Depth of Inheritance Tree (DIT)
DIT measures the number of levels in the inheritance hierarchy for a class. In safety-critical systems, excessive inheritance depth can lead to increased complexity and potential difficulties in understanding and maintaining the software.

## Fan-In and Fan-Out
Fan-In measures the number of functions or methods that call a particular function or method. Fan-Out measures the number of functions or methods called by a specific function or method.

## Coupling and Cohesion Metrics
Metrics related to the coupling and cohesion of software components provide insights into how interconnected and independent different parts of the system are. Low coupling and high cohesion are generally desirable in safety-critical systems.

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

## Cybersecurity Threats
Unauthorized access, data breaches, and cyber-attacks can compromise the integrity and safety of software systems.

## Software Complexity
The complexity of modern safety-critical software continues to grow with advanced functionalities, integration of artificial intelligence, and intricate control systems. Increased complexity can lead to challenges in understanding, testing, and ensuring the reliability of the software.

## Autonomous Systems Risks
The development and deployment of autonomous systems, such as autonomous vehicles and drones, introduce new risks. Issues related to perception, decision-making algorithms, and the ability to handle unforeseen scenarios pose challenges in ensuring the safety of these systems

## Machine Learning and AI Risks:
Safety-critical systems incorporating machine learning and artificial intelligence algorithms face challenges in ensuring the predictability and reliability of AI-driven decisions. Understanding the behaviour of complex learning systems and validating their safety becomes crucial.

## Data Integrity and Quality
Safety-critical systems often rely on data for decision-making. Ensuring the integrity and quality of data, especially in dynamic and uncertain environments, is a challenge. Incorrect or compromised data can lead to incorrect system responses.

## Regulatory Compliance Challenges
Evolving regulations and standards for safety-critical systems can pose challenges in maintaining compliance. Adapting to changing regulatory requirements and ensuring that systems meet the latest safety standards are ongoing concerns.

## Environmental Factors
Safety-critical systems operating in challenging environments, such as extreme weather conditions or hostile territories, face additional risks. Adapting to diverse environmental factors and ensuring the robustness of systems in such conditions is a concern.


# IEEE Code of Ethics 
--> In recognition of the importance of our technologies in affecting the 
quality of life throughout the world, and in accepting a personal obligation to our profession, its 
members and the communities we serve, do hereby commit ourselves to the highest ethical and 
professional conduct and agree: 

## To uphold the highest standards of integrity, responsible behaviour, and ethical conduct in professional activities.
  1. Prioritize the safety, health, and welfare of the public in professional activities.
  2. Strive to comply with ethical design principles and promote sustainable development practices.
  3. Protect the privacy of individuals and disclose factors that might pose risks to the public or the environment
  4. Improve public and individual understanding of the capabilities and societal implications of both conventional and emerging technologies, including intelligent systems.
  5. Avoid real or perceived conflicts of interest, and disclose them when they exist.
  6. Avoid engaging in unlawful conduct in professional activities and reject bribery in all its forms
  7. Seek, accept, and offer honest criticism of technical work. Acknowledge and correct errors. Be honest and realistic in making claims or estimates based on available data. Credit properly the contributions of others.
  8. Maintain and improve technical competence. Undertake technological tasks for others only if qualified by training or experience, or after full disclosure of pertinent limitations.
  9. Make the rules simple to understand. This emphasizes clarity and accessibility in ethical guidelines.

## To treat all persons fairly and with respect, to avoid harassment or discrimination, and to avoid injuring others. 
  1. Treat everyone fairly and with respect. Do not discriminate based on race, religion, gender, disability, age, national origin, sexual orientation, gender identity, or gender expression.
  2. Do not engage in any form of harassment, including sexual harassment or bullying behaviour.
  3. Avoid causing harm to others, their property, reputation, or employment. Refrain from false or malicious actions, rumours, or any other verbal or physical abuse.

## To strive to ensure this code is upheld by colleagues and co-workers.
  1. to support colleagues and co-workers in following this code of ethics, to strive to ensure the code is upheld, and to not retaliate against individuals reporting a violation.  


# Process for safety and reliability
  --> Ensuring safety and reliability in critical systems involves a systematic and rigorous process throughout the entire lifecycle of the system.
  Below is an overview 

## Requirements Analysis:
--> Safety and Reliability Requirements: Clearly define safety and reliability requirements at the beginning of the project. These requirements should be specific, measurable, and achievable.

## System Design:
Failure Modes and Effects Analysis (FMEA): Identify potential failure modes of components and systems. Assess the impact of these failures on the overall system and prioritize them for mitigation.

Fault Tree Analysis (FTA): Analyze how individual faults or failures contribute to system-level failures. This helps in understanding the relationships between different failure events.

Redundancy and Diversity: Incorporate redundancy and diversity in critical components to enhance reliability. Redundancy involves having backup systems, while diversity involves using different methods or components to achieve the same function.

## Development and Implementation:
Standards Compliance: Adhere to industry standards and regulations specific to safety and reliability. Compliance with standards ensures that the system meets established criteria for safety and reliability.

Testing and Validation: Conduct thorough testing, including functional testing, performance testing, and stress testing. Validation involves ensuring that the system meets the specified requirements and operates reliably under normal and extreme conditions.

## Operational Phase:
Monitoring and Maintenance: Implement continuous monitoring of system performance during its operational phase. Regular maintenance and inspections help identify and address potential issues before they lead to failures.

Incident Reporting and Analysis: Establish a system for reporting and analyzing incidents or failures. Learn from incidents to improve the safety and reliability of the system.

Software and Firmware Updates: Keep software and firmware up-to-date with the latest security patches and improvements. Regular updates can address vulnerabilities and enhance system reliability.

## Documentation and Training:
Comprehensive Documentation: Maintain detailed documentation, including design documents, manuals, and incident reports. Comprehensive documentation aids in understanding the system's architecture and behaviour.

Training Programs: Provide training programs for operators and maintenance personnel. Well-trained personnel are better equipped to operate and maintain the system safely.

## Continuous Improvement:
Lessons Learned: Collect and analyze data from incidents and failures to identify lessons learned. Use this information to implement improvements in processes, design, and operations.

Feedback Loop: Establish a feedback loop that allows ongoing input from operators, maintainers, and other stakeholders. This feedback can help identify issues and improvement opportunities.


# Process for high-integrity software and systems
 --> Developing high-integrity software and systems involves a systematic and disciplined process to ensure reliability, safety, and adherence to stringent quality standards. Below is a generalized overview

 ## Requirements Analysis
Clearly define and document high-level requirements, considering both functional and non-functional aspects such as safety, security, and reliability.

## Risk Analysis and Management
--> Conduct a comprehensive risk analysis to identify potential threats and vulnerabilities. Develop strategies to mitigate or manage these risks, particularly those related to safety and reliability.

## System Architecture Design
--> Create a robust system architecture that meets the specified requirements. Consider redundancy, fault tolerance, and isolation mechanisms to enhance system integrity.

## Formal Specifications
--> Use formal methods to specify the behaviour and properties of the software and system. Formal specifications provide a precise and unambiguous representation of system requirements.

## Coding Standards and Guidelines
--> Enforce coding standards and guidelines to promote consistency, readability, and maintainability. Follow best practices for high-integrity software development, such as MISRA-C for embedded systems.

## Verification and Validation
--> Implement rigorous verification and validation processes, including static code analysis, dynamic testing, and model checking. Verify that the software meets its specifications and validate its functionality in a real-world environment.

## Safety and Security Assessments
--> Perform safety and security assessments to identify potential vulnerabilities and ensure compliance with relevant safety standards (e.g., ISO 26262 for automotive, DO-178C for aviation).

## Configuration Management:
--> Establish robust configuration management practices to control changes to software artifacts, track versions, and ensure traceability between requirements, design, and implementation.

## Documentation
--> Maintain comprehensive documentation, including design documents, requirements traceability matrices, test plans, and safety cases. Documentation is essential for understanding, maintaining, and auditing high-integrity systems.

## Change Management:
--> Implement a rigorous change management process to assess the impact of proposed changes on system integrity. Changes should be carefully evaluated and validated before implementation.

## Certification and Compliance:
--> Seek certification from relevant regulatory bodies or standards organizations. Ensure compliance with industry-specific standards and regulations governing high-integrity systems.

## Continuous Improvement
--> Establish a culture of continuous improvement. Collect feedback from operational experiences, incidents, and audits to drive improvements in processes, tools, and the overall system.
