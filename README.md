# StoryLoop — Infinite Adventure Engine

[![Demo](https://img.shields.io/badge/demo-storyloop.fd--it.com-blue)](https://storyloop.fd-it.com/) [![Top Language](https://img.shields.io/github/languages/top/rodrigofd/storyloop)](https://github.com/rodrigofd/storyloop) [![License](https://img.shields.io/github/license/rodrigofd/storyloop)](https://github.com/rodrigofd/storyloop/blob/main/LICENSE)

A browser-based engine for endless, generative “choose your own adventure” stories. StoryLoop lets you play procedurally generated narrative scenes, pick choices (or speak them), see scene art, and keep persistent adventures — all powered by AI.

Live demo: https://storyloop.fd-it.com/

What you can do
- Start or import adventures that evolve with each choice.
- Read scenes that include descriptive text + AI-generated scene art.
- Choose from multiple options per scene (buttons or voice).
- Enjoy narrated scenes with text-to-speech controls and a narration status indicator.
- Track your timeline and inventory; revisit earlier scenes.
- Customize visual style prompts to influence generated imagery.
- Export and import sessions to share or continue stories.

Core user flows
1. New adventure — provide a short prompt or visual style and begin an infinite story.
2. Play — read the current scene, pick a choice (or speak it), and move to the next scene.
3. Narration & voice — toggle narration, listen to scenes, or speak your choice; the app maps speech to the closest option.
4. Timeline & inventory — open the sidebar to view past scenes, current quest, and collected items.
5. Export/Import — save adventures locally and reload them later or share with others.

Languages supported
- English, Spanish and Portuguese (UI and generated content adapt to the selected language).

Privacy & minimal tech notes
- The app uses an AI service for text and images; AI features require an API key (do not commit secrets).
- Sessions are stored locally in the browser to preserve privacy by default.

Troubleshooting tips
- If narration or image generation fails, check your network and that AI services are reachable.
- If voice recognition misinterprets you, try repeating clearly or use the choice buttons.
- Export your session before testing major changes if you want to keep a backup.

Contributing (short & friendly)
- Found a bug or have a feature idea? Open an issue with reproduction steps or a short use case.
- Want translations, better style prompts, or UI tweaks? Create issues or share examples/screenshots.
- For design suggestions, include images/GIFs and describe the expected behavior briefly.

Acknowledgements
- Uses Google GenAI models for story and image generation.
- Tailwind classes used for the UI and layout.

License
- See the LICENSE file in the repo.

Enjoy exploring infinite stories!  
— GitHub Copilot Chat Assistant
