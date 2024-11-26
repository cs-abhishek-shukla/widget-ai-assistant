# What's New

**Enhanced AI Assistant with Voice Recognition Feature**

A new **Voice Recognition** feature in our *AI Assistant* widget helps streamline SOC tasks with hands-free interaction. This enhancement brings greater flexibility, enabling users to interact through voice commands efficiently.

### Key Highlights
- **Press and Hold**: Activate the voice input by pressing and holding the microphone icon.
- **Automatic Stop**: Voice recording stops automatically when the microphone is released, simplifying the input process.
- **Quick Send**: After recording, press **Enter** to send the response for processing.

Try the Voice Recognition feature to elevate your SOC workflow!

> [!Note]
> The *Voice Recognition* feature is currently unsupported on the Firefox browser as the webkit `SpeechRecognition` is not compatible with Mozilla Firefox. Hence, the mic button is not available when the FortiSOAR&trade; environment is accessed using the Firefox browser.

**Conversation Thread Management**

Previously, conversation threads were deleted from OpenAI whenever *Clear Conversation* was clicked, and a new thread was started with each new prompt.

Now, threads are retained within OpenAI, enabling improved historical reference and continuity. Each new prompt still initiates a fresh thread, while the user interface continues to clear conversation history after each prompt, ensuring a clean workspace.