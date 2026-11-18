# claude-calculus-teacher
A Claude skill that turns Claude into a patient calculus teacher for Problems in Mathematical Analysis (G. S. Baranenkov, B. P. Demidovich et al., ed. B. P. Demidovich, Mir Publishers).

It can open pages, chapters and problems from the book, guide you with step-by-step hints, check your answers and quiz you. It works in English and Turkish.

Features
Navigate the book: "open page 45", "open chapter 3", "open problem 215", "next page", "show the answer"
Teaching, not just answers: asks where you're stuck first, then gives hints in stages. You get a full worked solution only when you ask for it.
Verification: checks results by differentiating, substituting or comparing with the book's answer section
Practice mode: "quiz me on chapter 4" gives you problems one at a time, from easier to harder
Bilingual: replies in the language you write in (English or Turkish)

Turkish commands work too: 45. sayfayı aç, 3. bölümü aç, 215. soruyu aç, cevabı göster.

Book coverage
#	Chapter
1	Introduction to Analysis
2	Differentiation of Functions
3	Extrema and Geometric Applications
4	Indefinite Integrals
5	Definite Integrals
6	Functions of Several Variables
7	Multiple and Line Integrals
8	Series
9	Differential Equations
10	Approximate Calculations
Installation
Download this repository (or just the SKILL.md file).
Put SKILL.md in a folder named calculus, then zip that folder.
In Claude, go to Settings → Capabilities → Skills and upload the zip.
For Claude Code, copy the calculus folder into ~/.claude/skills/.
Usage
Start a chat and attach your PDF copy of the book.
Ask naturally, for example:
open chapter 2
open problem 512 and give me a hint
I got x² ln x for problem 1040, is that right?
quiz me on series

Note: The book is not included in this repository. You need to supply your own copy of the PDF. Without it, the skill still teaches calculus. To work on a specific problem, paste its text or upload a photo of it.

Files
calculus/
├── SKILL.md   # skill instructions
└── README.md
Contributing

Issues and pull requests are welcome. Useful contributions include better navigation (for example, a page-offset table for common PDF editions), more languages and teaching improvements.
