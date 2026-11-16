# Section 8: AI Analysis and Verification

POLISCI 150A section practice. This starter is separate from the Section 7 repository.

## Create your own copy and clone it

1. On the instructor template page, choose **Use this template → Create a new repository**.
2. Set yourself as owner. Name your repository `section8-practice` and choose **Private**.
3. On your new repository, choose **Code → HTTPS** and copy the URL.
4. In RStudio, choose **File → New Project → Version Control → Git**. Paste **your own repository URL**, choose a parent folder, and click **Create Project**.
5. The project opens automatically. Check that the **Git** tab appears.
6. Open `face_ai.Rmd`. The dataset `face.csv` is already in the same main folder.

Later, reopen this project by double-clicking its `.Rproj` file in the cloned folder.

## During section

- Save the exact prompt in the Rmd and in `prompts/01.txt`.
- Preserve the raw response, then commit: `AI code, unverified`.
- Run and check the analysis. Add an independent check and a three-sentence verification note.
- Commit the corrected analysis: `Verify face analysis`.
- Add an interaction row to `AI_LOG.csv`. Its commit field refers to the checked-analysis commit. Then commit the log and push to your own repository.

Use `read.csv("face.csv")` in this project. See `DATA_SOURCE.md` for provenance. HTML output avoids requiring a local LaTeX installation.
