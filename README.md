# LearnTrack Content: Organic Chemistry

This repository stores LearnTrack lesson and quiz content for `chem002`.

## Active Structure

Use the organized course folder for new links and future edits:

```text
content/courses/chem002/
  course.json
  chapters/
    01/
      lessons/
      quizzes/
```

Lesson files use `.html`; quiz files currently use `.quiz.html` while LearnTrack remains on the Apps Script HTML quiz flow.

## Compatibility

Root-level files such as `CHEM002_0101.html` are preserved for backward compatibility. Do not delete them until all spreadsheet rows and deployed lessons have been verified against the organized paths.

## Styling

LearnTrack applies the shared lesson, quiz, media, and mobile styles from the Apps Script dashboard renderer. Keep lesson content semantic and avoid adding page-wide CSS that fights the platform frame styles.
