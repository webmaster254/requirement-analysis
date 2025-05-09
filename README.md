
# Requirement Analysis in Software Development.
This repository focuses on crafting a comprehensive foundation for software development by documenting, analyzing, and structuring requirements for a booking management system

## What is Requirement Analysis?
Requirement Analysis is the process of gathering, analyzing, documenting, and managing the requirements of a system or software to ensure it meets the needs and expectations of its stakeholders. It is a critical phase in the software development life cycle (SDLC) that helps define what the system should do before any design or development work begins.
### Why is Requirement Analysis Important?
- Reduces the risk of missing critical features or functionality.
- Prevents costly rework during later stages of development.
- Ensures alignment between stakeholder expectations and delivered software.
- Provides a clear roadmap for developers, testers, and project managers.

### Key Activities in Requirement Analysis.
1. Requirement Elicitation :
- Collecting requirements from users, stakeholders, and domain experts using interviews, surveys, workshops, use cases, etc.
2. Requirement Analysis :
- Evaluating and prioritizing the collected requirements for clarity, feasibility, and consistency.
3. Requirement Specification :
- Documenting the finalized requirements in a structured format (e.g., Software Requirements Specification - SRS document).
4. Requirement Validation :
- Reviewing and verifying the requirements with stakeholders to ensure accuracy and completeness.
5. Requirement Management :
- Tracking and controlling changes to requirements throughout the project lifecycle.

  ## Types of Requirements
  ### Functional Requirements
  - User Registration & Login
  - Search for Hotels
  - View Hotel Details
  - Room Booking
  - Payment Processing
  - Booking Confirmation
  - Cancel/Modify Booking
  - Admin Dashboard
 
    ### Non-Functional Requirements
    - Performance
    - Scalability
    - Security
    - Usability
    - Reliability
    - Maintainability
    - Availability
    - Compatibility
    - Recoverability/Fault Tolerance
   
      ## Use Case Diagrams
      A Use Case Diagram is a type of Unified Modeling Language (UML) diagram that visually represents the functionalities of a system from the perspective of its users (actors) . It shows how different actors interact with various use cases , helping to define and clarify the system's scope and boundaries

      ## Purpose of Use Case Diagrams
      - To identify and model user interactions with the system.
      - To capture functional requirements.
      - To provide a high-level view of system behavior.
      - To support communication between developers, clients, and stakeholders.
      - To serve as a foundation for more detailed design and testing phases.

        ### Benefits of Use Case Diagrams
        - **Clarity:** Helps understand what the system does without getting into implementation details.
        - **Communication Tool:** Makes it easier to discuss system features with non-technical stakeholders.
        - **Scope Definition:** Clearly defines which functionalities are included in the system.
        - **Requirement Validation:** Assists in identifying missing or redundant requirements early.
        - **Design Guidance:** Guides further modeling like sequence diagrams, class diagrams, etc
       
          ![use case diagram](https://github.com/webmaster254/requirement-analysis/blob/main/alx-booking-uc.png)

      ## Acceptance Criteria.
      Acceptance Criteria are the specific, measurable, and testable conditions that a software system must satisfy to be accepted by stakeholders. They define how to verify that a requirement or feature has been successfully implemented.

      In Requirement Analysis , acceptance criteria play a crucial role in ensuring clarity, alignment, and quality throughout the development process.

      ### Example of a acceptance criteria
      #### User Story: Checkout Feature
      1. Access to Checkout
         - Given the user has selected a room and initiated the booking,
         - When they proceed to checkout,
         - Then they should be directed to the checkout page containing all booking details and payment options.
      2. Display of Booking Summary
         - The checkout page must display:
         - Hotel name and address
         - Check-in and check-out dates
         - Room type and price per night
         - Total number of nights
         - Subtotal, taxes, and total amount due
      4. Payment Options
         -  The system should present at least two valid payment methods (e.g., Credit Card, PayPal).
         -  Users should be able to select one payment method before proceeding.
      6. Payment Processing
         - Given the user selects a payment method and enters valid payment details,
         -  Then the system should:
         -  Communicate with the payment gateway
         -  Confirm successful payment
         -  Proceed to the booking confirmation step
      8. Error Handling – Invalid Payment
         - Given the user enters invalid or incomplete payment information,
         - Then the system should:
             - Display an appropriate error message
             - Highlight the fields requiring correction
             - Allow the user to re-enter the correct details
      10. Booking Confirmation
          - After successful payment,
          - The system shall :
               - Generate a unique booking ID
               - Display a confirmation screen with booking details and payment summary
               - Send a confirmation email/SMS to the user
      12. Cancel During Checkout
          - If the user decides to cancel during the checkout process,
          - They should be able to return to the previous step or abandon the booking without any charges.
      14. Session Timeout
          - If the checkout process remains inactive for more than 10 minutes,
          - The system should:
               - Notify the user
               - Redirect them to the homepage or login screen
               - Discard the incomplete booking
