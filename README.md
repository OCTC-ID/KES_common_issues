# KOLA Course Reviews: Common Issues and Simple Fixes

A one-page guide for OCTC faculty covering the issues that come up most often in KOLA course reviews, with a manageable fix and a short video for each.

**View the page:** https://octc-id.github.io/KES_common_issues/

KES is the set of quality standards for fully online courses. KOLA is the review of a course against those standards.

## Topics and direct links

Each link opens the page at that topic. Use these in review feedback.

| Topic | KES | Direct link |
|---|---|---|
| Course organization and learning modules | 1.4 | https://octc-id.github.io/KES_common_issues/#organization |
| Module overviews | 1.1, 1.8, 1.9 | https://octc-id.github.io/KES_common_issues/#module-overviews |
| Accessibility: PDFs, Word documents, and images | | https://octc-id.github.io/KES_common_issues/#accessibility-documents |
| Accessibility: PowerPoint and AI-generated decks | | https://octc-id.github.io/KES_common_issues/#accessibility-slides |
| Rubrics and assessment grading | 3.1 | https://octc-id.github.io/KES_common_issues/#rubrics |
| Participation and outside activities | 2.7 | https://octc-id.github.io/KES_common_issues/#outside-activities |
| Student feedback throughout the course | | https://octc-id.github.io/KES_common_issues/#student-feedback |
| A useful Start Here module | | https://octc-id.github.io/KES_common_issues/#start-here |
| Course technology instructions and support | 4.17 | https://octc-id.github.io/KES_common_issues/#technology |

## Adding or replacing a video

1. In Loom, copy the video's share link.
2. Open `index.html` and find the topic's video line: `<div class="video" data-loom=""></div>`
3. Paste the link between the quotes: `data-loom="https://www.loom.com/share/..."`
4. Commit the change. The page updates within a few minutes.

An empty `data-loom=""` shows "Video coming soon."

## Files

- `index.html`: the whole page (content, styles, and the script that builds the video players). No other files or dependencies.

## Contact

Stephanie Self, Instructional Designer and eLearning Coordinator, Owensboro Community & Technical College
stephanie.self@kctcs.edu
