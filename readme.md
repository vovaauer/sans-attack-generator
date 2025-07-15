# sans's attack-o-matic (Sans Attack Generator)

A web-based tool that uses generative AI to create custom attack patterns for **[jcw87's Bad Time Simulator](https://jcw87.github.io/c2-sans-fight/)**. Describe the attack you want, and the tool will generate the `.csv` file needed to run it in the simulator.

## Live Demo

**You can use the live tool here: [https://vovaauer.github.io/sans-attack-generator/](https://vovaauer.github.io/sans-attack-generator/)**

## The Workflow

Using this tool is a two-part process: first, you generate the attack file, then you load it into the simulator.

### Part 1: Generate Your Attack

1.  **Get an API Key**
    The generator requires an AI provider's API key. It's pre-configured for Google Gemini.
    -   You can get a **free API key** from **[Google AI Studio](https://aistudio.google.com/apikey)**.

2.  **Configure the Generator**
    -   On the webpage, find the `* api settings` section.
    -   Paste your API key into the `* api key` field.

3.  **Generate and Download**
    -   Describe the attack you want in the main text box.
    -   Click **`* get dunked on (Generate)`**.
    -   Once the attack appears, click **`* take it with ya (Download)`** to save the `.csv` file to your computer.

### Part 2: Test Your Attack in the Simulator

1.  Go to the **[Bad Time Simulator](https://jcw87.github.io/c2-sans-fight/)**.
2.  Click **`Custom Attack`**.
3.  Click **`Load File`** and select the `.csv` file you just downloaded.
4.  Click **`Back`**.
5.  Click **`Run Custom Attack`** to see your creation in action!

## Features

-   **Natural Language Prompts**: Generate complex attack sequences by describing them in plain English.
-   **Context-Aware**: The AI is provided with engine documentation and dozens of examples to produce accurate and valid attack code.
-   **Easy Export**: Download the generated code directly as a compatible `.csv` file.
-   **Persistent Settings**: Remembers your API configuration in your browser's local storage.

## Credits

This tool generates attack files specifically for the excellent **Bad Time Simulator** created by **[jcw87](https://github.com/jcw87)**.