# NotebookLM-to-Gemini
This Chrome Extension, 'NotebookLM to Gemini' handles text you select on a webpage and sends it to Google's Gemini service when you initiate an action. This extension does not store, save, or transmit any of your personal data or selected text to any servers other than Google's own Gemini service.

How to Use the "NotebookLM to Gemini" Extension
A simple guide to mastering the extension and automating your research workflow.1. Installation & Setup
① Install the ExtensionInstall the extension from the official Chrome Web Store. Once installed, you need to "pin" it to your toolbar for easy access.
② Pin the IconClick the puzzle piece icon (🧩) in your Chrome toolbar. Find "NotebookLM to Gemini" in the list and click the pin icon (📌) next to it. The extension's icon will now always be visible.

2. The Core Workflow

   The entire process is designed to be quick and intuitive, taking you from text selection to expert analysis in seconds.
   
2.1 Select Your Source Text. 
Go to any webpage or your NotebookLM notes. Use your mouse to highlight the text you want to analyze.

2.2 Send to Extension
   Right-click (🖱️) on the text you just highlighted. From the context menu that appears, click on the Send to Gemini option.
   
2.3 Open the Popup
   Click on the extension's icon that you pinned to your toolbar. A popup window will appear, showing the text you selected.
   
2.4 Choose Your Action
   Click one of the five action buttons in the popup window. This tells the extension what you want Gemini to do with your text.
   
2.5 Automatic Submission
   A new Gemini tab will open automatically. The extension's "robot" will then paste your text and the detailed instruction into Gemini and click "Submit" for you. Just sit back and watch!

3. Understanding the Actions
   Each button sends a unique, expert-level prompt to Gemini to perform a specific task.
   
   🎬Generate with VeoTransforms your text into a detailed video script and shot list.
   
   🔬Deep ResearchPrompts a multi-faceted analysis, identifying arguments and counter-arguments.
   
   🎨Send to CanvasAsks Gemini to create a mind map in Mermaid.js syntax for visual diagramming.
   
   📜SummarizeGenerates a concise, executive-level summary of the selected text.
   
   📊Create TableFormats the key information from your text into a structured markdown table.
   

5. Frequently Asked Questions (FAQ)
   Why didn't the "Open it in Canvas" button get clicked automatically?
   
     The ability to automatically open the visual Canvas view depends entirely on whether Gemini's interface provides that specific button in its response. Our extension will always look for it, but sometimes Gemini generates the text-based canvas without offering the button. In this case, our extension has worked correctly by providing the structured text.

   Why does one action sometimes trigger another?
   
     This is a rare bug that can happen if you perform actions very quickly. The latest version of the extension includes a fix to prevent this. If you still encounter it, simply reloading the extension from the chrome://extensions page will resolve it.
