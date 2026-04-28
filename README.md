# Topher's Sora Prompt Sorter

Topher's Sora Prompt Sorter is a simple, 100% local-only tool that lets you import multiple JSON files from the official Sora export, extract the prompts, and organize them into a spreadsheet-ready format.

Drop in or select as many export files as you want, or even select the parent folder containing all your JSON files, and the tool will de-duplicate similar prompts (using word shingling plus corpus-weighted token similarity) via an adjustable uniqueness slider. You can either Copy to Clipboard or Download the final output, which includes `Order`, `ID`, `Prompt`, `Width`, and `Height`.

![Topher's Sora Prompt Sorter preview](preview.png)
