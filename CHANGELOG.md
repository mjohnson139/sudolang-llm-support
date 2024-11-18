# Change Log

## SudoLang v1.0.10 -> v1.0.11 (In Progress)

### Added

- New [Autodux](examples/autodux.sudo) demonstrates how to use SudoLang to create a Redux state management system that automatically generates reducers, action creators, and selectors based on a brief description.
- New [Whispers](examples/whispers.sudo) text adventure game demonstrates rich constraint-based programming and game `/save` and `/load` commands.
- New [Swift App Builder](examples/swift-app.sudo) demonstrates how to use SudoLang to build Swift apps using Apple's technologies.

### Changed

- Updated [Robot](examples/robot.sudo) to improve command dispatching success rate and give the robot a more human-like personality and emotes.

### Deprecated

- The `cup` and `cap` operators are deprecated in favor of `union` and `intersection` due to instability in Claude 3.5. The new `union` and `intersection` keywords were tested in GPT-4o, Claude 3.5, and Llama 3.1 with 100% accuracy.

## SudoLang v1.0.9 -> v1.0.10

### Added

- New teaching program [Experience Levels](examples/experience-levels.sudo) teaches a topic to a student on a variety of levels ranging from child to world-class expert.
- New [Life Coach](examples/life-coach.sudo) example program.
- New [Robot](examples/robot.sudo) example demonstrates how to get the AI language model to issue commands to other systems (such as a robot, or API controller) for autonomous agents.
- "Why SudoLang?" section in README.md explains why SudoLang is useful, with links to supporting research.

## SudoLang v1.0.8 -> v1.0.9

### Added

- Better description of SudoLang in the specification.
- More documentation for constraints in the specification.

## SudoLang v1.0.7 -> v1.0.8

No changes to the core language, which is why its version is still set to v1.0.7.

### Added

- New Todo App Example (Works great with Bing Chat)
- New Newsbot App example (Requires Bing Chat or browser/search plugin)
- New Learn SudoLang example (Currently the best way to learn SudoLang)
- New AI Friend chatbot builder
- PromptCrafter: New light source descriptions.

### Fixed

- PromptCrafter's improve function sometimes didn't work as expected. It should work better and more often, now.

## SudoLang v1.0.6 -> v1.0.7

### Added

- Added documentation for cap and cup operators.
- Added documentation for /commands.
- Updated RPG Game example to showcase new features and best practices.
- Introduced CodeBot, an AI assistant for writing unit tests and code.
- Added Improve Anything, an example that demonstrates iterative code improvement.
- Implemented Music Recommender, an example that suggests music based on user preferences.
- Created PromptCrafter, a tool for building midjourney prompts.
- Developed StudyBot, an AI-powered learning tool featuring vocabulary, flashcard game, and Q&A functionalities.

## SudoLang v1.0.5 -> v1.0.6

### Added

- Added more keywords to syntax highlighting.
- Reimplemented examples folder to use new features and style guide recommendations.

## SudoLang v1.0.4 -> v1.0.5

### Added

- Added `interface`, `warn`, and `require` for defining the structure and behavior of functions and objects, enhancing the constraint-based paradigm of SudoLang.
- Added `lint` for linting SudoLang code and providing recommendations based on the improved SudoLang Style Guide.
- Ported Riteway (in the `examples` folder) to improve test writing practices and use language model inference capabilities for quality unit tests.
