# ExclusiveWG_Paper

Templates, style files and helpful code for preparation of the ExclusiveWG paper.

## Directory Structure

Directory structure is as follows -

- Style_Files
  - A template ePIC style file to include in your analysis macro to format plots consistently
  - Add these lines to your macro
    - #include "ePICStyle.C";
    - gROOT->ProcessLine("SetePICStyle()");
- ROOT_Macros
  - Some root macros you might find useful for your analysis
- Analysis_Note_Template
  - A template .tex file for use in writing your analysis note
  - You can upload all of the included files directly to Overleaf etc if you want
- Analysis_Notes
  - Add folders with your analysis note here
      - Raw .tex files, images OR just link to overleaf. Either is fine
