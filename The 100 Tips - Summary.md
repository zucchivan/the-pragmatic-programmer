
# Pragmatic Programmer - The 100 Tips (20th Anniversary Edition) Summarized

#### Chapter 1: A Pragmatic Philosophy

1.  **Care About Your Craft**
    Take pride in the software you create, treating development as a professional discipline where quality, skill, and attention to detail matter deeply. Aim for excellence and continuous improvement in your work.

2.  **Think! About Your Work**
    Actively engage your mind while programming; constantly analyze, question, and critique your approach and decisions rather than coding mechanically or running on autopilot.

3.  **You Have Agency**
    Recognize that you possess the power and responsibility to influence and change your work, your environment, and your career path; don't be a passive victim of circumstances.

4.  **Provide Options, Don’t Make Lame Excuses**
    When facing problems or setbacks, take ownership and proactively offer solutions, alternatives, or ways forward, rather than resorting to blame or justifications for failure.

5.  **Don’t Live with Broken Windows**
    Address small problems, imperfections, and technical debt (bad designs, poor code, wrong decisions) as soon as they are discovered, as neglecting them creates an environment where entropy and decay accelerate.

6.  **Be a Catalyst for Change**
    Gently introduce improvements or changes by starting small, demonstrating value incrementally (like the stone soup story), and encouraging others to join in, rather than attempting large, disruptive changes upfront.

7.  **Remember the Big Picture**
    Continuously maintain awareness of the overall context and goals of your work, avoiding the "boiled frog" syndrome where gradual negative changes go unnoticed until it's too late.

8.  **Make Quality a Requirements Issue**
    Explicitly involve users and stakeholders in defining the necessary level and aspects of quality for the software, treating it as a fundamental requirement alongside functionality, rather than an assumed standard or an afterthought.

9.  **Invest Regularly in Your Knowledge Portfolio**
    Continuously learn and expand your technical skills, knowledge, and experience, treating it like a financial portfolio that requires regular investment, diversification, and rebalancing to remain valuable.

10. **Critically Analyze What You Read and Hear**
    Question and evaluate information actively, considering the source, context, biases, and applicability, rather than blindly accepting advice, trends, or vendor claims.

#### Chapter 2: A Pragmatic Approach

11. **English is Just Another Programming Language**
    Apply the same principles of clarity, precision, consistency (DRY), and careful construction to your written and spoken communication as you do to your code.

12. **It's Both What You Say and the Way You Say It**
    Recognize that effective communication requires tailoring your message, style, timing, and delivery method to your specific audience and their context.

13. **Build Documentation In, Don't Bolt It On**
    Integrate documentation directly with the code, using comments primarily to explain the *why* behind decisions and leveraging tools to generate API documentation from the source itself, keeping it synchronized.

14. **Good Design Is Easier To Change Than Bad Design**
    Embrace the core principle that the fundamental measure of good software design is how readily it accommodates future changes and adapts to new requirements (Easier To Change - ETC).

15. **DRY—Don’t Repeat Yourself**
    Every piece of knowledge or intent must have a single, unambiguous, authoritative representation within a system to avoid the maintenance nightmares caused by duplicated logic, data, or documentation.

16. **Make It Easy to Reuse**
    Foster an environment and design components in a way that makes finding and reusing existing code and knowledge easier than writing it from scratch, thereby reducing duplication and effort.

17. **Eliminate Effects Between Unrelated Things**
    Design components to be independent and self-contained (orthogonal), so that changes in one area do not unintentionally affect unrelated areas, increasing robustness and reducing maintenance effort.

18. **There Are No Final Decisions**
    Treat design and architectural decisions as provisional and written in sand, not stone; build flexibility into your system to accommodate inevitable changes in requirements, technology, or understanding.

19. **Forgo Following Fads**
    Focus on fundamental design principles, adaptable architectures, and solving the core problem rather than chasing the latest fleeting technological trends or buzzwords.

20. **Use Tracer Bullets to Find the Target**
    Build a simple, thin, end-to-end working skeleton of the system early on to verify the architecture, demonstrate feasibility, get feedback, and provide a robust structure for incremental development.

21. **Prototype to Learn**
    Employ prototypes specifically to explore unknowns, answer specific questions, reduce risk, or test concepts, with the clear understanding that the prototype code itself is exploratory and disposable.

22. **Program Close to the Problem Domain**
    Design and code using the language, abstractions, and concepts inherent to the problem domain itself, making the software more intuitive and aligned with user needs, potentially via domain-specific languages.

23. **Estimate to Avoid Surprises**
    Use estimation not just for scheduling but as a vital tool to better understand the scope, complexity, potential risks, and feasibility of a task or project, thereby managing expectations.

#### Chapter 3: The Basic Tools

24. **Iterate the Schedule with the Code**
    Refine project schedule estimates continuously based on the actual progress and learning gained during each development iteration, acknowledging that initial estimates are inherently uncertain.

25. **Keep Knowledge in Plain Text**
    Store crucial project information, including code, documentation, and configuration, in plain, human-readable text formats to ensure longevity, enable automation, and leverage the power of existing tools.

26. **Use the Power of Command Shells**
    Become proficient with your command-line shell to automate repetitive tasks, compose powerful tool combinations using pipes and scripts, and gain deeper control over your development environment beyond GUIs.

27. **Achieve Editor Fluency**
    Master your primary text editor to the point where manipulating code and text becomes an unconscious, fluid extension of your thoughts, minimizing friction and maximizing focus on the problem itself.

28. **Always Use Version Control**
    Employ a version control system for *everything* you create that forms part of the project (code, documentation, configuration, notes, scripts, etc.), tracking history, enabling collaboration, and providing an essential safety net.

#### Chapter 4: Pragmatic Paranoia

29. **Fix the Problem, Not the Blame**
    When a bug occurs, focus your energy on understanding the root cause and implementing a solution, rather than wasting time and damaging morale by trying to assign blame.

30. **Don’t Panic**
    When faced with a bug, error, or unexpected problem, resist the urge to react impulsively; instead, take a deep breath, step back, and think logically and methodically about the situation.

31. **Failing Test Before Fixing Code**
    Before attempting to fix a bug, first write an automated test that reliably reproduces the failure; this verifies your understanding and ensures the fix is effective and doesn't regress.

32. **Read the Damn Error Message**
    Don't immediately dismiss or ignore error messages or stack traces; read them carefully, as they often contain precise information pointing directly to the source of the problem.

33. **“select” Isn’t Broken**
    Assume problems lie within your own code or your use of external components before blaming the underlying operating system, libraries, compilers, or third-party products; bugs are usually closer than you think.

34. **Don’t Assume It—Prove It**
    Rigorously verify your assumptions about code behavior, data states, or environmental conditions through tests, experiments, or debugging, rather than taking potentially flawed beliefs for granted.

35. **Learn a Text Manipulation Language**
    Master a powerful text processing language (such as Python, Ruby, Perl, or even awk/sed combined with shell scripting) to automate data transformation, code generation, and other text-based tasks efficiently.

36. **You Can’t Write Perfect Software**
    Accept that all non-trivial software contains flaws and that perfection is unattainable; use this understanding to motivate defensive coding, robust error handling, and thorough testing.

37. **Design with Contracts**
    Use preconditions, postconditions, and invariants to formally specify and verify the rights and responsibilities associated with software modules, leading to more reliable, understandable, and verifiable code.

38. **Crash Early**
    When a program detects that something is seriously wrong or an internal state has become corrupted, it's often safer to terminate execution immediately rather than risk causing further, potentially hidden, damage.

39. **Use Assertions to Prevent the Impossible**
    Add assertions liberally to your code to explicitly check for conditions that you believe should "never" happen according to the program's logic, catching bugs close to their origin.

40. **Finish What You Start**
    Ensure that the function, method, or object that allocates a resource (such as memory, file handles, sockets, locks) is also responsible for its deallocation to prevent leaks and maintain balance.

#### Chapter 5: Bend, or Break

41. **Act Locally**
    Design components to be self-contained, operating on their own internal state and data passed to them, minimizing dependencies on global state or distant parts of the system.

42. **Take Small Steps—Always**
    Approach development through small, deliberate, and incremental changes, constantly seeking feedback and making adjustments, rather than attempting large, risky leaps.

43. **Avoid Fortune-Telling**
    Resist the urge to make binding decisions based on uncertain future predictions; focus on building adaptable systems that can accommodate change rather than trying to guess the future perfectly.

44. **Decoupled Code Is Easier to Change**
    Minimize coupling between modules by reducing their interdependence, making it easier to change or replace individual components without causing widespread ripple effects.

45. **Tell, Don’t Ask**
    Instead of asking an object for data and then making decisions based on that data, tell the object what to do, moving the responsibility and related logic into the object that owns the data.

46. **Don’t Chain Method Calls**
    Avoid long sequences of method calls (train wrecks) like `a.getB().getC().doSomething()`, as they expose internal implementation details and create tight coupling across multiple objects; aim for one dot per line where practical.

47. **Avoid Global Data**
    Minimize the use of globally accessible data, as it creates hidden dependencies, makes code harder to reason about and test, and increases the risk of unintended side effects.

48. **If It’s Important Enough to Be Global, Wrap It in an API**
    Instead of exposing global data directly, encapsulate it within a module or class and provide access through a well-defined API, allowing you to manage access and change the implementation later.

49. **Programming Is About Code, But Programs Are About Data**
    Shift your focus towards how data flows and transforms through your system; thinking in terms of data transformations often leads to simpler, more decoupled, and easier-to-understand designs.

50. **Don’t Hoard State; Pass It Around**
    Design functions and components to operate on input data and produce output data, minimizing internally held state and making data flow explicit, which enhances clarity and reduces coupling.

51. **Don’t Pay Inheritance Tax**
    Avoid using implementation inheritance solely for code reuse, as it creates tight coupling and can lead to fragile hierarchies; prefer alternatives like interfaces, delegation, or mixins.

52. **Prefer Interfaces to Express Polymorphism**
    Use interfaces (or protocols) to define shared behavior and enable polymorphism, allowing different classes to be treated uniformly without forcing them into a rigid inheritance hierarchy.

53. **Delegate to Services: Has-A Trumps Is-A**
    Favor composition (using helper objects or services) over implementation inheritance (is-a relationships) to add functionality, leading to more flexible and less coupled designs.

54. **Use Mixins to Share Functionality**
    Employ mixins or traits to add common functionality to multiple classes without using inheritance, allowing for flexible combinations of behavior while avoiding deep or complex class hierarchies.

55. **Parameterize Your App Using External Configuration**
    Extract parameters, credentials, URLs, feature flags, and other environment-specific details from your code into external configuration files or services, making your application adaptable without code changes.

#### Chapter 6: Concurrency

56. **Analyze Workflow to Improve Concurrency**
    Model your system's workflows (e.g., using activity diagrams) to identify independent tasks that can potentially be executed concurrently or in parallel, optimizing for throughput and responsiveness.

57. **Shared State Is Incorrect State**
    Recognize that mutable state shared between concurrent processes is a primary source of errors; minimize or eliminate shared state to simplify concurrency management.

58. **Random Failures Are Often Concurrency Issues**
    Be highly suspicious of intermittent or seemingly random bugs, as they are frequently caused by underlying race conditions or other concurrency problems that only manifest under specific timing conditions.

59. **Use Actors For Concurrency Without Shared State**
    Consider using the actor model, where independent processes communicate via asynchronous messages and manage their own private state, eliminating the need for locks and shared memory synchronization.

60. **Use Blackboards to Coordinate Workflow**
    Employ blackboard systems where independent agents or services cooperate by reading and writing facts or data to a shared space, allowing for flexible and decoupled coordination of complex workflows.

#### Chapter 7: While You Are Coding

61. **Listen to Your Inner Lizard**
    Pay attention to your gut feelings, doubts, or uneasiness while coding; these non-verbal signals from your subconscious often indicate underlying problems or risks that warrant investigation.

62. **Don't Program By Coincidence**
    Ensure you understand *why* your code works; relying on luck, accidental successes, or undocumented behavior leads to fragile systems that are hard to debug and maintain.

63. **Estimate the Order of Your Algorithms**
    Develop an understanding of the performance characteristics (e.g., using Big-O notation) of the algorithms you use or write, particularly concerning how they scale with input size.

64. **Test Your Estimates**
    Verify your assumptions about algorithm performance by measuring actual runtime or resource usage under varying conditions, rather than relying solely on theoretical analysis.

65. **Refactor Early, Refactor Often**
    Continuously improve the design of existing code through small, safe refactoring steps as you gain better understanding or identify areas for cleanup, treating it as an integral part of development, not a separate phase.

66. **Testing Is Not About Finding Bugs**
    Recognize that the primary benefit of writing tests often comes from the design feedback gained *while* writing them, forcing you to think about contracts, coupling, and usability, not just from catching errors later.

67. **A Test Is the First User of Your Code**
    Use the process of writing a unit test as an opportunity to evaluate the usability and design of your code's API from a client's perspective.

68. **Build End-To-End, Not Top-Down or Bottom-Up**
    Favor an incremental approach that builds and tests thin slices of end-to-end functionality early (like tracer bullets), rather than building components in isolation from the top down or bottom up.

69. **Design to Test**
    Consciously design your code modules with testability in mind, ensuring they have clear interfaces, minimal coupling, and mechanisms to control dependencies, making unit testing easier and more effective.

70. **Test Your Software, or Your Users Will**
    Accept that all software will be tested eventually; take responsibility for thorough testing yourself, rather than relying on your users to find the bugs in production.

71. **Use Property-Based Tests to Validate Your Assumptions**
    Employ property-based testing frameworks to automatically generate a wide range of inputs and verify that your code upholds specified contracts, invariants, or properties, often revealing unexpected edge cases.

72. **Keep It Simple and Minimize Attack Surfaces**
    Reduce security risks by minimizing complexity, limiting the number of access points (APIs, UIs, inputs), and reducing the overall amount of code and external dependencies that could potentially be exploited.

73. **Apply Security Patches Quickly**
    Maintain the security of your systems by promptly applying updates and patches to operating systems, libraries, and frameworks, as unpatched vulnerabilities are a major vector for attacks.

74. **Name Well; Rename When Needed**
    Choose names for variables, functions, classes, etc., that clearly reveal their intent and purpose; don't hesitate to rename things when their original name becomes misleading or inaccurate due to code evolution.

#### Chapter 8: Before the Project

75. **No One Knows Exactly What They Want**
    Accept that clients and users rarely have a complete and accurate understanding of their requirements upfront; requirements emerge and evolve through a process of exploration and feedback.

76. **Programmers Help People Understand What They Want**
    See your role not just as implementing given specifications, but as actively collaborating with clients and users to explore possibilities, clarify needs, and help them discover what they truly require.

77. **Requirements Are Learned in a Feedback Loop**
    Treat requirements gathering as an ongoing, iterative process involving feedback cycles with users, using prototypes, mockups, and working software to elicit and refine understanding.

78. **Work with a User to Think Like a User**
    Gain deeper insight into user needs and context by directly observing or participating in their workflow, fostering empathy and leading to more effective and usable solutions.

79. **Policy Is Metadata**
    Separate relatively stable core requirements from more volatile business rules or policies; implement the general mechanism in code and parameterize it with the specific policies as configurable metadata.

80. **Use a Project Glossary**
    Create and maintain a central glossary of domain-specific terms and definitions agreed upon by the entire team (including users) to ensure consistent understanding and communication.

81. **Don't Think Outside the Box—Find the Box**
    Instead of ignoring constraints, focus on accurately identifying the *real* limitations and boundaries (the box) of a problem, as well as the degrees of freedom within which a solution can be found.

#### Chapter 9: Pragmatic Projects

82. **Don’t Go into the Code Alone**
    Leverage collaborative practices like pair programming or mob programming to improve code quality, share knowledge, and solve complex problems more effectively than working in isolation.

83. **Agile is not a Noun; Agile Is How You Do Things**
    Understand agility as an adjective describing *how* you respond to change and feedback, rather than a specific, rigid process or methodology (noun) to be followed prescriptively.

84. **Maintain Small Stable Teams**
    Foster effective communication and collaboration by keeping project teams small (typically under 10-12 members) and minimizing churn in team membership.

85. **Schedule It to Make It Happen**
    Allocate specific time in your project schedule for important non-feature activities such as refactoring, learning, experimentation, and process improvement, otherwise they are unlikely to occur.

86. **Organize Fully Functional Teams**
    Structure teams to possess all the necessary skills (frontend, backend, testing, UX, etc.) to deliver features end-to-end, minimizing handoffs and dependencies on external groups.

87. **Do What Works, Not What's Fashionable**
    Critically evaluate methodologies, tools, and practices based on their effectiveness in your specific context, rather than adopting them simply because they are popular or trendy (avoid cargo cults).

88. **Deliver When Users Need It**
    Aim for the capability to deploy working software frequently and reliably, ideally on demand, allowing you to release value to users precisely when it makes business sense.

89. **Use Version Control to Drive Builds, Tests, and Releases**
    Leverage your version control system as the trigger and source of truth for automated build, test, and deployment pipelines, ensuring consistency and repeatability.

90. **Test Early, Test Often, Test Automatically**
    Integrate comprehensive, automated testing into every stage of the development process, starting with unit tests written alongside the code, to catch bugs early and provide rapid feedback.

91. **Coding Ain't Done 'Til All the Tests Run**
    Consider a piece of functionality incomplete until it is accompanied by robust automated tests that verify its correctness; passing tests are part of the definition of "done."

92. **Use Saboteurs to Test Your Testing**
    Verify the effectiveness of your test suite by deliberately introducing bugs (or using automated tools like mutation testing or chaos engineering) and ensuring the tests correctly detect the failures.

93. **Test State Coverage, Not Code Coverage**
    Focus testing efforts on exercising the important states and transitions within your code and its data, rather than merely aiming for high line or branch coverage, which doesn't guarantee detection of state-related bugs.

94. **Find Bugs Once**
    When a bug is found (especially by a human), ensure it's the *last* time that specific bug is found by creating an automated test that permanently guards against its recurrence.

95. **Don't Use Manual Procedures**
    Automate every aspect of the build, test, and deployment process; manual steps are error-prone, inconsistent, and hinder the ability to deliver reliably and frequently.

96. **Delight Users, Don't Just Deliver Code**
    Focus on understanding and exceeding your users' underlying expectations and solving their actual business problems, rather than simply fulfilling the letter of a requirements specification.

97. **Sign Your Work**
    Take professional pride and ownership in the code and systems you build, associating your name with quality, reliability, and craftsmanship.

98. **First, Do No Harm**
    Be acutely aware of the ethical implications and potential negative consequences of the software you create; actively strive to protect users and society from harm.

99. **Don't Enable Scumbags**
    Take ethical responsibility for the purpose and impact of your work; refuse to participate in projects that facilitate illegal, unethical, or harmful activities.

100. **It’s Your Life. Share It. Celebrate It. Build It. And Have Fun!**
    Remember to enjoy the challenging and rewarding craft of software development, share your passion and knowledge, celebrate achievements, and build a fulfilling life and career.