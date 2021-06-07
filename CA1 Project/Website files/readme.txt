/////////////////
Changes to Layout
/////////////////

1. About Me (index.html)
  - 1.1 Lackign a good recent solo photo of myself in good quality and can't go out to take one due to Covid.
	As such, I resorted to using a photo with 2 of my friends and I on a swing @ East Coast Park.

2. What's Going on Now (lspj_current.html)
  - 2.1 Studies and workload and timetable (web table) was supposed to be in a 66% to 33% format.
	But time table be too small for viewing. Hence, the format was changed to be two 100% columns.
  - 2.2 Added an additional paragraph underneath the timetable as a continuation of the above paragraph.

3. What the Future Holds (lspj_future.html)
  - 3.1 Potential Careers portion was meant to be complimented with a picture of a cybersecurity specialist.
	Changed it to show the statistics of the jobs as it made more sense along with the content. 
  - 3.2 Career Prospect portion was meant to be complimented with a picture of statistical data. Which has been
	changed to show a picture of a cybersecurity specialist, as this portion talks about the overall
	cybersecurity ecosystem and relevance in today's world.

4. Feedback (lspj_feedback.html)
  - 4.1 "How helpful was the information presented on my website? *" was supposed to have radio buttons from 
	1 to 10. But has been changed to a slider for better usability
  - 4.2 "How aesthetically pleasing was my website?" similarly was changed to a slider for better usability.
  - 4.3 "What improvements could I make to my website?" was supposed to be merely a text input, but has been
	changed to textarea to allow for more content.
  - 4.4 Added a new segment, "Image Upload" to allow visitors to upoad screenshots or pictures of bugs on the
	website or to show a specific segments, so that improvements can be made.


/////////////
HTML Comments
/////////////

1. What's Going on Now (lspj_current.html)
  - 1.1 Timetable was meant to use colspan, but chrome has an issue with colspan. Hence, unable to show 30 minute
	intervals for some modules.
  - 1.2 The previous issue was solved by using nested tables and giving classes to different lengths of lessons.


////////////
CSS Comments
////////////

1. Validator (https://jigsaw.w3.org/css-validator/)
  - 1.1 Error of "text-decoration-thickness doesn't exist". However, this styling does exist and it changes the
	thickness of the underline text decoration.
  - 1.2 Error of "text-underline-offset doesn't exist". However, this styling does exist and it moves the underline
	text decoration further down.


////////////////
General Comments
////////////////

1. Images
  - 1.1 The images in the "photos" folder have been ensured to be less than 800KB.

2. Videos
  - 2.1 As "Web Graphics file" are JPG, GIF, and PNG. The videos (.mp4) exceed 800KB, 12.5MB and 27.9MB respectively. 

3. Naming Convention
  - 3.1 The webpage logo being "Lucas' SP Journey" has been reduced to LSPJ, which is the naming convention for files
	such as lspj_past.html, lspj_current.html, etc.
