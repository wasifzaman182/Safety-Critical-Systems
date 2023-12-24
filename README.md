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

