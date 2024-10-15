# random-intelligence-tests

As it was stated earlier "...only intelligence tests, with random tasks that have the same average difficulty, can provide a standard of intelligence for all times, sentient beings and artificial intelligence".

Although the standards of intelligence are already developed and freely available, they manifest themselves as dynamic HTML pages that are primarily intended for interaction with people. LLMs cannot yet directly interact with the pages.

FIRST.html/FIRST-NB.html/FIRST-MC.html or INPUT.html/INPUT-NB.html and NEXT.html or NEXTSAFA.html are able to measure AI intelligence by comparing them to those timeless standards. The complexity of tasks is determined by the configuration: the size of the board, the number of chips and the number of types of chips. The complexity can be measured by a universal solver - Monte Carlo method. NEXTR.html measures the maximum and average intelligence of the universal solver and complexity of tasks for a given configuration.

FIRST-NB.html and INPUT-NB.html do not ask AI ​​to create boards. Use them with NEXTSAFA.html.
NEXTSAFA.html uses only SA FA values gotten from AI. This is useful when AI makes incorrect boards.
NEXT.html uses only boards gotten from AI, SA FA move addresses are not taken into account.

There is also possibility to compare intelligence of several test-takers without the standards of intelligence, giving them the same random tasks of varying difficulty from FIRST-MC.html/random_intelligence_test.html.

To evaluate ability of test-takers to pass the random tests open FIRST.html/FIRST-NB.html/FIRST-MC.html or/and INPUT.html/INPUT-NB.html or random_intelligence_test.html in a browser and copy the text up to the "THE END OF THE TEST TASK" then give it to AI.

You get a new task(s) by reloading the FIRST.html/FIRST-MC.html or random_intelligence_test.html in the browser. After receiving the modified board from the AI, pass it to NEXT.html. After receiving the move addresses SA, FA from AI, pass it to NEXTSAFA.html. Reload the page for the next input.

It is possible to change complexity of the tasks by editing script in the FIRST.html/FIRST-NB.html/FIRST-MC.html or/and INPUT.html/INPUT-NB.html or random_intelligence_test.html.

To compare maximum or average intelligence of the Monte Carlo(MC) method with intelligence of an AI, you need to open FIRST.html/FIRST-NB.html/FIRST-MC.html or/and INPUT.html/INPUT-NB.html, then NEXTR.html, and then NEXT.html or NEXTSAFA.html.

FIRST-MC.html prints given number of boards with their average MC-complexity values.
INPUT.html/INPUT-NB.html allows you to enter specified data into cookies, just like FIRST.html/FIRST-NB.html does.

All *.html were tested in Firefox.
They were also tested in Devuan Chromium using a local server on port 8000:

python3 -V --> Python 3.11.2

cd /some_dir where *.html are

python3 -m http.server

in the Chromium --> http://localhost:8000/INPUT.html
