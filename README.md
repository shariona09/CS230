# CS230
# The Gaming Room - Software Design Document

This repository contains the completed software design document for **The Gaming Room**, developed as part of the CS course project. The document outlines the architecture, design patterns, and system structure used to support the game *Draw It or Lose It* across multiple platforms.

---

## Client Overview

The Gaming Room is a client that wanted to expand their game *Draw It or Lose It* from Android to multiple platforms. They required a scalable, well-structured software design that would support consistent game logic and performance across devices.

---

## Design Reflection

In developing the design document, I did well in organizing the software architecture and choosing appropriate design patterns such as Singleton and Iterator. These helped manage shared game state and user interactions efficiently. Having the design in place before writing code made development smoother, since I had a clear understanding of component responsibilities and interactions.

If I were to revise one part, I would enhance the domain model diagrams by including clearer labels and multiplicities to improve readability for developers.

I translated the client’s needs into specific features and components, ensuring the design stayed focused on usability and the player experience. Considering user needs is essential—it ensures that the software is not only functional but also valuable.

My approach to the design was top-down, starting with high-level architecture and refining it into detailed components. In future projects, I’ll continue to use UML diagrams, user stories, and proven design patterns to create scalable, maintainable software systems.

---

## Repository Contents

- `GamingRoom_DesignDocument.pdf` – Final design document
- `README.md` – Project summary and reflection

- The Gaming Room is a client that requested a software application version of their game Draw It or Lose It, which was originally developed for the Android platform. Their goal was to expand this game across multiple operating systems using a cloud-based, scalable approach. They needed a well-structured software design that ensured maintainability, performance, and security, while following proper object-oriented principles. My task was to analyze their requirements and develop a complete software design document that would guide development and ensure a consistent architecture across platforms.

In developing this documentation, I think I did particularly well in clearly organizing the software architecture and identifying the appropriate design patterns to use, such as the Singleton and Iterator patterns. These decisions helped establish a strong foundation for managing shared game state and navigating lists of games and players efficiently. I also focused on using clean, client-facing language to make sure the document was understandable to both technical and non-technical stakeholders.

Working through the software design document before developing the code gave me a clear roadmap. It allowed me to think about component interactions, data flows, and user requirements in advance, which made writing the actual code more structured and purposeful. It also helped me avoid some common issues related to scope creep or vague implementation logic.

If I had to revise one part of the document, I would improve the domain model diagrams. While they communicated the relationships between entities well, I think I could have added more clarity by including multiplicities and a brief legend. These additions would have made it easier for developers unfamiliar with the project to understand entity interactions at a glance.

To interpret and implement the user’s needs, I first translated their high-level requirements into specific use cases, such as managing player sessions, rendering drawings in real time, and allowing team-based gameplay. From there, I designed features that directly addressed those use cases. It’s critical to consider user needs in software design because the success of an application is ultimately measured by how well it solves the user’s problem. Ignoring those needs risks building something technically functional but practically useless.

When approaching this software design, I used a top-down strategy. I began with the broad system architecture, then broke it down into classes, interfaces, and relationships. In the future, I’d continue using techniques like UML diagrams, agile user stories, and pattern selection based on the system’s scale and complexity. These help ensure that the design remains modular, scalable, and aligned with the client's goals.



