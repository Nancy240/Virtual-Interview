# Virtual-Interview
The Virtual Interview Platform is a web-based application designed to conduct automated video interviews. Candidates answer pre-selected questions, record their responses via webcam, and submit them for review. The application uses Flask for the backend, AWS S3 for video storage, and Google Cloud Speech-to-Text for transcription. The frontend is built with HTML, Bootstrap, and JavaScript, providing a user-friendly interface for device checks, interview progress, and feedback submission.

## Features


Device Check: Verifies microphone and camera functionality before starting the interview.

Randomized Questions: Selects two questions randomly from a predefined list for each interview session.

Video Recording: Records responses in WebM format, compresses them to MP4, and uploads them to AWS S3.

Countdown Timers: Provides preparation (5 seconds) and recording (10 seconds) timers for each question.

Feedback System: Allows candidates to submit feedback, stored as text and CSV files in S3.

Review and Retry: Enables candidates to review recorded answers and retry if needed.

Tab Switch Detection: Monitors tab switches to ensure interview integrity, reloading the page after multiple switches.

Rescheduling: Placeholder functionality for rescheduling interviews (requires backend implementation).

Fullscreen Mode: Prompts fullscreen for a focused interview experience.
