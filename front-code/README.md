Interview Questions
===================

## Within it you will find:

- signup.png — a screenshot of what the signup edit page in the NationBuilder control panel currently looks like (edited to remove some input fields).

- signup.html — HTML of the signup edit page. Includes many more input field than the screenshot.

- New UI elements.jpg — style guide of new UI elements (note this file is 2x for retina screens. the actual size of the elements should be 50%).

- icon fonts folder — icon font file for the signup edit page.

Modify and update signup.html in the following ways:

- Create a new stylesheet and style the page so it looks like signup.png. 

- Update the UI elements (input fields, buttons, etc.) to match the new styles shown in New UIelements.jpg. Note that the following button should simply change to the eye icon button shown in theNew UI elements.jpg file, and that a tooltip should appear which says "follow".

- Replace the grid system and other relevant markup to use Bootstrap. This does not mean create a new page from scratch on Bootstrap. Instead, retrofit signup.html to use these elements as cleanly as you can. Make sure any icons use the font icons provided.

- Please note that you're simply creating a static page. We don't expect anything to submit or for the search form in the drop downs to work.

## JAVASCRIPT TEST:

For the calendar page found here, please complete the following tasks using JavaScript and/or jQuery. You can test your code via the editor at the top of the page. Simply copy/paste your solutions in reply to this email.

Part 1

Your customer would like to have all the events of this calendar on one page, but NationBuilder paginates every ten events by default. Given an unknown number of events and pages, how would you display all the events on a single page?

Tasks:
- Display all of this calendar's events on a single page
- Remove the now extraneous paginator

Part 2

Your customer then decides that she wants to highlight the most popular events, but events are sorted by start time by default. Help her move the events with the most number of RSVPs to the top of the list.

Tasks:
- Using the list of all events as obtained in Part 1, sort events by descending number of RSVPs
- Events which have the same number RSVPs should be sorted by their start dates, with the soonest events higher up on the list

Part 3

A designer on your team decides that a delightful way to reveal the complete list of sorted events obtained in Part 2 would be to fade in each event one by one. How would you implement this feature?

Tasks:
- Events are hidden until they've been loaded and sorted
- Events fade in one after the other, with the first event revealed before the second one is revealed, and so on, until the full list of events is visible
