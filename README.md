# random-intelligence-tests

As it was stated earlier "...only intelligence tests, with random tasks that have the same average difficulty, can provide a standard of intelligence for all times, sentient beings and artificial intelligence".

Although the standards of intelligence are already developed and freely available, they manifest themselves as dynamic HTML pages that are primarily intended for interaction with people. LLMs cannot yet directly interact with the pages.

FIRST.html and NEXT.html or NEXTSAFA.html are able to measure AI intelligence by comparing them to those timeless standards. The complexity of tasks is determined by the configuration: the size of the board, the number of chips and the number of types of chips. The complexity can be measured by a universal solver - Monte Carlo method. NEXTR.html measures the maximum and average intelligence of the universal solver and complexity of tasks for a given configuration.

NEXT.html uses only boards gotten from AI.
NEXTSAFA.html uses only SA FA values gotten from AI. This is useful when AI makes incorrect boards.

There is also possibility to compare intelligence of several test-takers (LLMs as well) without the standards of intelligence, giving them the same random tasks of varying difficulty from random_intelligence_test.html.

To evaluate ability of test-takers to pass the random tests open FIRST.html or random_intelligence_test.html in the Firefox browser and copy the text up to the "THE END OF THE TEST TASK".

You get a new task by reloading the FIRST.html or random_intelligence_test.html in the browser. After receiving the modified board from the AI, pass it to NEXT.html or NEXTSAFA.html. Reload the page for the next input.

It is possible to change complexity of the tasks by editing script in the FIRST.html, INPUT.html or random_intelligence_test.html. You will probably want to use a more random generator.

To compare maximum or average intelligence of the Monte Carlo method with intelligence of an AI, you need to open FIRST.html in Firefox, then NEXTR.html, and then NEXT.html or NEXTSAFA.html.

INPUT.html allows you to enter specified data into cookies, just like FIRST.html does.

FIRST.html, NEXT.html, NEXTSAFA.html, NEXTR.html and INPUT.html were tested in Firefox.
They were also tested in Devuan Chromium using a local server on port 8000:
python3 -V --> Python 3.11.2
cd /some_dir where *.html are
python3 -m http.server
in the Chromium --> http://localhost:8000/INPUT.html
