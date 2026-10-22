[README (1).md](https://github.com/user-attachments/files/33827283/README.1.md)
# Early Learning Snapshot

Early Learning Snapshot is an informal, teacher-administered Early Literacy and Early Numeracy skills inventory designed to help identify demonstrated skills, emerging skills, instructional needs, and possible intervention targets.

## Purpose

The Snapshot may be used with learners at different grade levels when foundational reading or mathematics skills need to be informally explored. The selected grade provides context only; tasks should be selected according to the learner's instructional needs.

This tool is intended for informal instructional screening, intervention planning, tutoring, and progress-monitoring conversations. It is **not** a standardized assessment and does not provide norms, percentiles, risk classifications, diagnoses, or eligibility determinations.

## Using the Snapshot

1. Open the hosted Early Learning Snapshot in a web browser.
2. Enter a **nonidentifying student code** and select the learner's grade and screening window.
3. Administer the Early Literacy and/or Early Numeracy items that are appropriate for the learner.
4. For scored items, select:
   - Correct
   - Self-Corrected
   - Incorrect
   - No Response
   - Not Assessed
5. Use **Not Assessed** for items that are skipped or not appropriate. Not Assessed items are excluded from skill scoring.
6. Review the Results & Intervention Guide for the skill profile, strengths and needs summary, and suggested intervention priorities.
7. Print/save or export results only when appropriate for your workflow.
8. Select **Reset** after each screening to clear the current browser session.

## Privacy for the Public-Hosted Pilot

Do not enter student names, student ID numbers, dates of birth, or other identifying information into the public-hosted pilot. Use a nonidentifying code such as `Student-01`.

Downloaded PDFs or CSV files are separate files and are not removed when the web form is reset. Handle or delete exported files according to the requirements of your setting.

## Scoring

The Snapshot uses descriptive instructional classifications for completed skill sets:

- **Established**
- **Developing**
- **Not Yet Demonstrated**

These classifications describe performance within this informal Snapshot only. They should not be interpreted as grade-level benchmarks, normative scores, disability indicators, or eligibility criteria.

Some areas, including counting sequence and emergent writing, are recorded descriptively rather than forced into a percentage score.

## Files

- `index.html` — the web application and GitHub Pages entry file.
- `README.md` — project description and use guidance.

## GitHub Pages

The application is a self-contained static webpage. Keep `index.html` at the top level of the repository and configure GitHub Pages to publish from the branch containing that file.

## Current Scope

The current Snapshot emphasizes foundational skills such as print concepts, alphabet knowledge, letter-sound knowledge, phonological awareness, listening comprehension, emergent writing, counting, cardinality, numeral recognition, quantity comparison, composing small numbers, shapes, patterns, and positional concepts.

When using the Snapshot with older learners, administer foundational items according to demonstrated instructional need rather than assuming the items represent the learner's enrolled grade curriculum.

## Setup

### What you need

- A GitHub account.
- The `index.html` file for Early Learning Snapshot.
- This `README.md` file is recommended for project documentation, but it is not required for the assessment itself to run.

### Repository setup

1. Sign in to GitHub.
2. Create a new repository. A simple repository name is `early-learning-snapshot`.
3. If you are using GitHub Free for the pilot, use a public repository for the straightforward GitHub Pages setup described here.
4. Upload `index.html` to the top level of the repository.
5. Upload `README.md` to the same level.
6. Commit the uploaded files.

Your repository should look like this:

```text
early-learning-snapshot/
├── index.html
└── README.md
```

`index.html` is the web application. `README.md` documents the project and its intended use.

## Publish with GitHub Pages

GitHub Pages can publish a site from a repository branch. The site needs an entry file such as `index.html`, and when publishing from a branch/folder, that entry file must be at the top level of the selected source folder.

1. Open the `early-learning-snapshot` repository in GitHub.
2. Select **Settings**.
3. Open **Pages** in the repository settings.
4. Under the Pages build/deployment settings, configure the site to publish from the branch that contains `index.html`.
5. Select the folder that contains `index.html`. If the file is at the top level of the repository, use the repository root as the source folder.
6. Save the Pages configuration.
7. Return to the Pages settings to access the published website link after GitHub has published the site.
8. Open the published website in a browser rather than trying to open the raw `index.html` file from a device's Files app.

### Updating the assessment later

When a new version of Early Learning Snapshot is created:

1. Keep the live application's filename as `index.html`.
2. Replace the existing `index.html` in the repository with the updated version.
3. Commit the change to the branch used for GitHub Pages.

This keeps the project structure simple and avoids having to change the assessment's launch location each time the content is revised.

## Using the Hosted Version

For the current public-hosted pilot:

- Use nonidentifying learner codes only.
- Do not enter names, student ID numbers, dates of birth, or other identifying information.
- Select the learner's enrolled grade for context, but administer skills according to instructional need.
- Use **Not Assessed** when an item is not appropriate or is intentionally skipped.
- Review the Results & Intervention Guide after administration.
- After saving or recording any needed results, select **Reset** before beginning another learner's screening.
- Remember that resetting the web form does not delete PDF or CSV files that were separately downloaded to the device.

## iPad Access

Once the Snapshot is published through GitHub Pages, open the published website address in Safari rather than opening `index.html` directly from the iPad Files app. The same hosted site can also be opened from a desktop or laptop browser.

## Important GitHub Pages Privacy Note

GitHub's documentation states that GitHub Pages sites are publicly available on the internet. Do not place sensitive student information in the repository or enter identifying student information into this public-hosted pilot.
