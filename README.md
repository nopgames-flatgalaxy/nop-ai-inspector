# NOP AI Inspector
AI-assisted code inspection plug-in for Eclipse.

##Installation##

1. Run Eclipse
2. Help → Install New Software
3. Add... 
4. Location: https://nopgames-flatgalaxy.github.io/nop-ai-inspector/
5. Add
6. If the list appears empty, disable: Group items by category

##If the NOP AI Inspector view does not appear automatically##

1. Window -> Show View -> Other
2. Other -> NOP AI Inspector

##Configure plugin##

1. Window -> Preferences -> NOP AI Inspector
2. Server preset: select one of predefined presets
3. Server URL: Base URL of an OpenAI-compatible API
4a. For local LLM server:
  - keep API key empty
  - run local model server
4b. For remote model server:
  - create or get API key from the server provider (https://openrouter.ai for example)
  - enter it to API key field
5. Press Model Load button
6. Model: set available model
7. Apply and Close
