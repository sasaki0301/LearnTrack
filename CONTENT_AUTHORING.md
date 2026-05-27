# LearnTrack Content Authoring

Use `templates/lesson.template.html` and `templates/quiz.template.html` when creating new lessons.

## Naming

Lesson:

```text
content/courses/{courseId}/chapters/{chapter}/lessons/{chapter}{lesson}.html
```

Quiz:

```text
content/courses/{courseId}/chapters/{chapter}/quizzes/{chapter}{lesson}.quiz.html
```

Example:

```text
content/courses/chem002/chapters/03/lessons/0304.html
content/courses/chem002/chapters/03/quizzes/0304.quiz.html
```

## Style Rule

Do not paste a large CSS theme into every lesson. LearnTrack injects shared lesson, quiz, media, and mobile styles when it loads the content.

Use semantic blocks such as `section`, `concept-box`, `quick-check`, `activity`, `key-terms`, `video-block`, `simulation-block`, and `image-block`.

## Spreadsheet Type Values

Use:

```text
lesson
summary
assessment
```

Use `summary` for chapter summaries. Use `assessment` for chapter tests or final quizzes.
