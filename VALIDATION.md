# Validation record

Checked on November 18, 2026.

- Rendered the complete Rmd successfully in a fresh `Rscript --vanilla` process, using R 4.6.1 and RStudio's bundled Pandoc.
- No warnings or errors appeared in the render log; warnings were not globally suppressed.
- Confirmed the RStudio project opens and the Rmd is available in its editor.
- Confirmed all 20 CSV files match the official ZIP archive byte for byte.
- Independently checked 10 participants per arm, eight observations per participant, and the group means reported in the text.
- The birthday simulation uses 10,000 runs at each of 49 group sizes (490,000 runs total).
- The t-test simulation uses 5,000 runs at each of seven true means (35,000 datasets total).
- Confirmed 11 uniquely named chunks, no package installation commands, and four valid relative image links in the Markdown report.
- Visually inspected all four generated plots for legible titles, labels, legends, and unclipped content.
- Results quoted in prose use inline R expressions rather than manually entered numerical values.

## Remaining publication steps

The local project is complete. A public GitHub repository has not been
created or updated by this task. Review the files, publish the repository
including the Rmd, Markdown, data, and figure folder, then personally submit
the repository URL to CourseWorks. No CourseWorks submission has been made.

The assignment page gives November 18 at 11:59 pm as the deadline and says
commits after the deadline count as late; it does not state a year or timezone.
