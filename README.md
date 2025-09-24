README (as requested, shown here not inside the zip)
What’s inside

One folder per chapter, plus 00_Unspecified for code that appears before the first “Chapter 1” heading.

806 code files extracted in total, grouped by chapter.

I kept all kinds of code: OCaml (.ml, .mli), Dune stanzas (dune, dune-project), YAML (CI), shell commands (.sh), Makefiles, .ocamlformat, and a few plain .txt when detection wasn’t certain.

File names follow block_###.<ext> when a concrete filename isn’t stated in the book. For things like Makefile, dune-project, or .ocamlformat, I used the real names. If a chapter had multiple of the same named file, I added a numeric suffix to avoid overwriting.

Chapter counts (blocks found)

00_Unspecified: 19

Chapter_01: 57

Chapter_02: 52

Chapter_03: 54

Chapter_04: 52

Chapter_05: 61

Chapter_06: 70

Chapter_07: 50

Chapter_08: 46

Chapter_09: 60

Chapter_10: 75

Chapter_11: 66

Chapter_12: 48

Chapter_13: 23

Chapter_14: 73

Total files: 806

Notes on accuracy

Detection is heuristic but thorough. I picked up fenced and unfenced code, Dune stanzas, CI YAML, Makefile targets, and shell lines near code comments.

Where the text shows the same file multiple times (for example dune-project templates), duplicates were preserved with suffixes so you can compare versions.

If you want me to rename files by inferred intent (e.g., split .ml vs .mli more strictly, or put all CI YAML into a ci/ folder), say the word and I’ll reorganize.

Source: OCaml Intermediate Guide (uploaded DOCX). 
