# Tasks

Tasks is a minimalist web application designed to help you break bad habits by tracking your success in avoiding them, rather than completing tasks. It functions like a reverse to-do list, providing a clear, black-and-white interface focused on your progress.
Features

    Reverse To-Do List: Instead of marking tasks as "done," you mark habits as "avoided" for the day.

    Minimalist Design: Clean, black-and-white aesthetic with subtle interactions for a distraction-free experience.

    Quick Habit Addition: Easily add new bad habits directly from the main interface with optional priority and due date.

    Daily Tracking: Mark habits as avoided with a simple click on the custom checkbox-style circle.

    Progress Overview: See your daily progress with "Avoided / Total" counters and a subtle progress bar.

    Detailed Insights (Modal): Click on any habit to view a detailed progress modal, including:

        Current avoidance streak.

        Optional trigger and replacement habit information.

        A 30-day calendar view of your avoidance history.

        A chart visualizing your avoidance trend.

        Basic insights into your habit-breaking patterns.

    Delete Habit: Remove any habit (and its associated logs) via the details modal.

    Responsive Layout: Adapts to various screen sizes.

    Local Storage: All your habits and their daily avoidance logs are saved directly in your browser's local storage, so your data persists even if you close the tab.

## How to Use

    Add a New Habit:

        Type the name of the bad habit you want to track in the "Add task" input field.

        (Optional) Select a priority ("High," "Medium," "Low") and a due date using the respective inputs below the task field.

        Click the + button or press Enter to add the habit to your list.

    Track Your Daily Avoidance:

        For each habit on your list, click the circular checkbox on the left.

        If the circle is empty, clicking it will mark the habit as "Avoided Today" (the circle fills with black, and the text becomes grayed-out and struck-through).

        If the circle is filled (Avoided Today), clicking it will mark the habit as "Not Logged Today" (the circle becomes empty again, and the text reverts). This is how you "undo" an avoidance or clear a log for the day.

    View Habit Details:

        Click anywhere on a habit's text (not the checkbox or delete icon) in the main list to open a detailed modal.

        This modal provides a comprehensive view of your progress for that specific habit, including streaks, a calendar, a chart, and insights.

    Delete a Habit:

        Open the habit's details modal (by clicking on its text).

        Click the "Delete Task" button at the bottom of the modal. You will be asked to confirm.

## Getting Started

To run this application locally:

    Save the entire code into a single .html file (e.g., index.html).

    Open the index.html file in any modern web browser.

Your habits will be saved automatically in your browser's local storage.
