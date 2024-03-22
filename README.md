# gfx-pixel-creator
Create bitmaps for monochrome OLED/LC displays

The code for this project was generated primarily from ChatGPT 3.5 (chat.openai.com). The prompts consisted of descriptions of the desired layout, labels, and actions. It went through several rounds of refinement to 
* adjust the visual layout 
* add new functionality (e.g. change the size of the grid, add a draw & erase mode)
* correct the behaviour of specific actions

The prompts contained some domain-specific knowledge (e.g. details about mouse states and events; references to specific divs), but generally focused on what was perceived to be wrong with the behaviour and clarifying the desired outcomes.

Second pass: adding row/column index labels and export
* did not get correct code from GPT for creating divs with the correct alignment and sizing, required a fair bit of guess and test
* export to C code worked the first time

