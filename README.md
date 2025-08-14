# TypeRace
User Story: 

As a new visitor, I want to see clear instructions so that I can understand how to take the typing test.

Acceptance Criteria:

Instructions are visible on the homepage.
Instructions explain how to start, complete, and retry the test.
Instructions are concise and easy to understand.

Tasks:

Write concise instructions covering start, completion, and retry steps.
Add instructions section to homepage HTML.
Style instructions for visibility and clarity.
Review instructions for ease of understanding.

User Story: 

As a user, I want to start the test easily so that I can quickly begin measuring my typing speed.

Acceptance Criteria:

A prominent "Start Test" button is available.
Clicking the button begins the test immediately.
The test area is focused and ready for typing after starting.

Tasks:

Add a prominent "Start Test" button to the UI.
Implement JavaScript to begin the test on button click.
Set focus to the typing input area when the test starts.


User Story:

As a user, I want to select a difficulty level and text passage so that I can challenge myself appropriately.

Acceptance Criteria:

Difficulty levels (e.g., easy, medium, hard) are selectable before starting.
Multiple text passages are available for each difficulty.
Selected passage is displayed when the test starts.

Tasks:

Create UI controls for selecting difficulty levels.
Prepare multiple text passages for each difficulty.
Display the selected passage when the test begins.


User Story: 

As a user, I want the website to be responsive so that I can use it comfortably on any device.

Acceptance Criteria:

Layout adapts to desktop, tablet, and mobile screens.
All features are accessible and usable on different devices.
No horizontal scrolling is required on mobile.

Tasks:

Implement responsive layout using CSS media queries.
Test and adjust UI for desktop, tablet, and mobile screens.
Ensure all features are accessible and usable on all devices.
Remove horizontal scrolling on mobile devices.

User Story: 

As a user, I want to see a paragraph to type and an input area so that I can complete the test.

Acceptance Criteria:

A paragraph is displayed clearly above the input area.
Input area is easy to locate and use.
Only the displayed paragraph can be typed in the input area.

Tasks:

Display the paragraph above the input area in the UI.
Implement a typing input area.
Restrict input to match only the displayed paragraph.


User Story: 

As a user, I want to receive real-time feedback on my typing accuracy so that I can improve as I type.

Acceptance Criteria:

Incorrectly typed characters are highlighted immediately.
Correct characters are visually indicated.
Feedback updates as the user types.

Tasks:

Implement logic to compare user input with the displayed text in real time.
Highlight incorrect and correct characters as the user types.
Update feedback dynamically with each keystroke.


User Story: 

As a user, I want to see my typing speed in Words Per Minute (WPM) after the test so that I can track my performance.

Acceptance Criteria:

WPM is calculated and displayed after the test ends.
WPM calculation is accurate and based on standard formula.
WPM result is easy to find and read.

Tasks:

Calculate WPM using standard formula after test completion.
Display WPM result clearly in the UI.
Validate accuracy of WPM calculation.


User Story: 

As a user, I want a retry option so that I can attempt the test again to improve my score.

Acceptance Criteria:

A "Retry" button is available after the test.
Clicking "Retry" resets the test and allows a new attempt.
Previous results are not lost when retrying.

Tasks:

Add a "Retry" button to the results screen.
Reset test state and input area when retrying.
Preserve previous results for comparison.


User Story: 

As a user, I want to see my best results for comparison so that I can monitor my progress over time.

Acceptance Criteria:

Best WPM score is saved locally (e.g., in browser storage).
Best score is displayed alongside current results.
Best score updates if a new high score is achieved.

Tasks:

Store best WPM score locally (e.g., localStorage).
Display best score alongside current results.
Update best score if a new high score is achieved.