# CS230FinalProject
The Gaming Room Software Design

PROMPT SUMMARY

  The Gaming Room was the client for this project. They currently operate an Android-based game called Draw It or Lose It and wanted to expand the application into a web-based platform that would be accessible across multiple operating systems and devices. The software needed to support multiple teams and players, maintain unique identifiers for games and users, provide access to a shared drawing database, and ensure that game sessions could run simultaneously without conflicts. The design also needed to account for scalability, security, and cross-platform compatibility while maintaining a consistent user experience across Android and web clients.

MY STRENGTHS

  I believe one of my strongest contributions was the depth of my operating platform analysis. Rather than simply identifying advantages and disadvantages of each platform, I evaluated Linux, Windows, macOS, and mobile operating systems from both server-side and client-side perspectives. I also incorporated concepts such as scalability, containerization, WebSocket communication, memory management, and distributed systems to justify my recommendations. This allowed my final recommendation to be supported by technical reasoning rather than personal preference.

DESIGN REFLECTIONS

  Creating the design document helped me consider the application's architecture before implementation. The UML domain model clarified the relationships between the Game, Team, Player, and GameService classes and reinforced object-oriented design concepts such as inheritance, composition, aggregation, encapsulation, and the Singleton design pattern. Having these relationships clearly defined before coding reduced uncertainty and provided a roadmap for implementation. The design document also encouraged me to consider scalability, security, and performance requirements that might otherwise be overlooked during development.

REVISEMENT CONSIDERATIONS

  If I could revise one section of my design document, I would revisit the recommendations section. While I am satisfied with the level of detail I provided regarding Linux, storage management, memory management, and distributed systems, I think I focused too heavily on infrastructure and operating system concepts. As a result, I spent less time discussing software engineering principles that are equally important to the success of an application.
  In a revised version, I would expand my discussion of maintainability, modularity, scalability, and fault tolerance. I would also integrate security considerations more directly into the architectural recommendations rather than primarily addressing them in a dedicated security section. Additionally, I would spend more time evaluating the limitations of my recommendations. While Linux and OpenZFS provide strong scalability, reliability, and cost advantages, they can also introduce additional complexity for organizations without Linux administration experience. A stronger recommendation would acknowledge these tradeoffs while discussing alternative solutions based on organizational needs.

CLIENT REQUIREMENTS

  I interpreted the client's needs by focusing on their goal of expanding an existing Android game into a web-based application that could support cross-platform gameplay. To address these requirements, I designed a centralized architecture that supports multiple game sessions, unique identifiers, shared access to game assets, and communication between clients and the game server. These decisions were made to ensure consistency, reliability, and scalability for users across different platforms. Considering user needs is critical because software ultimately exists to solve user problems. A technically advanced solution can still fail if it does not meet the needs and expectations of the people who use it.

SOFTWARE DESIGN APPROACH

  My approach to software design began with understanding the business requirements and technical requirements before evaluating potential architectural solutions. I used requirement analysis, UML modeling, object-oriented design principles, and platform evaluation to develop recommendations for the application. Throughout the project, I considered scalability, maintainability, security, cost, and performance when making design decisions.

FORWARD

  In future projects, I would continue using requirement analysis and UML modeling early in the design process. I would also spend more time developing architecture diagrams, evaluating security requirements throughout the design phase, and performing more formal tradeoff analyses between competing technologies before making recommendations.

