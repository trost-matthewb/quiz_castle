# quiz_castle
App for facilitating quizzes

INTRO
The quiz_castle app is rooted in the history of bible quizzing for the ACC, NWO, Wayne County, West Liberty and Virginia quiz leagues.  Initial spec, development, and implementation of the app is being done by Matt Trost, coordinator for the Virginia league.

PURPOSE
The quiz_castle app will allow quiz matches to be constructed and facilitated around the following parameters and assumptions:
  1) Match questions (along with the associated answer) will be initially chosen and populated into a single match at random, whereupon the individual questions can be swapped out for other questions as desired or needed by the user.
  2) The pool of questions and associated answers is populated via an import from an external data source such as an MS Excel file or comma separated value file.  Questions have a corresponding reference, i.e., the Book, Chapter and Verse.
  3) From season to season the Book being used may be repeated, though with a different edition or version, and the app must allow and facilitate different versions of the biblical text to be used.
  4) A quiz match consists of two teams, with at most six participants from each team competing in a quiz match.  A match may contain up to 21 total questions, with as few as 15 total questions, depending on the league and whether the match score is tied after the regular set of match questions have been asked.
  5) A quizzer that attempts to give the initial answer for the question may incur an error if an incorrect answer is given.  After a team's fourth error, beginning with the fifth error by the team, five points is deducted from the team score for each error incurred.
  6) When the initial answer given for a question is judged to be incorrect, a bonus is given to the corresponding quizzer on the other team.  An incorrect answer for the bonus question does not count as an error.  The bonus question is the original question, read in entirety before it must be answered (a quizzer may "buzz in" at any time during the reading of the initial question, at which time the quiz master stops reading the question).
  7) A correct answer is awarded 10 points for the quizzer giving the answer, also increasing the team's total score by 10 points.
  8) A quizzer that has reached a certain point total, either 30 points or 40 points depending on the league, is awarded a 'quiz out' and receives an additional five points for their personal total as well as the team's total score.
  9) An individual quizzer that has incurred three errors in a single match is considered 'errored out' and may not remain in the match after their third error.  Their seat must be left empty for the remainder of the match, meaning that the team may only have at most three quizzers in the match for the remainder of the match.
  10) Each team is allowed to take up to three timeouts during a single match
  11) When four members of a single team answer the initial question correctly, the team receives an extra 20 points for a 'team bonus'.  Answering a bonus question correctly does not count toward the team bonus.
  12) If the score is tied 
