[images]: # (Image References)
[image_0]: images/backtick-key.jpg "Data Types"
[image_1]: images/backticks.gif
[image_2]: images/pastebin.gif
[image_3]: responsive.gif
[image_4]: synchronousQuery.jpg
[image_5]: images/reviews.gif

## Contents
- [Creating HTML pages for Ratings, with Links to Reviews](#Review)
- [Classroom Mentor](#MENTOR)
- [Posting Code in the Chat Window](#SNIPPETS) (for shorter code snippets)
- [Posting Code on an External Site](#CODE) (for longer segments of code/scripts) 

<a id='Review'></a>
## Creating HTML pages for Ratings, with Links to Reviews

- The 2 notebooks in this repository have the same output:
  * HTML pages of: Ratings, Reviews, Your Submissions, Peer Reviews, and Ratings and Reviews Combined.
  * These pages are _grouped by_ projects (can be turned off), and
  * they all contain links to the relevant reviews
  
_Use the non-Pandas version._ The main difference between the two notebooks is that the one marked _"PANDAS"_ uses pandas dataframes (which may be handy for analysis). That version is slower (for 300 reviews, the pandas notebook takes about 45 seconds, the other takes about 15 seconds) and, if you want the `Combined` webpage, you **have to** create both the `Ratings` and `Reviews` webpages too (with the JSON version, you can pick and choose).

_Note:_ For either version, python's `markdown` module has to be installed.

**In either case, just fill in the 3 required strings (and change the 3 options, if you wish), and click `Cell` in the notebook menu then select `Run All` and the relevant webpages will be created.**

### An Example Reviews Page:

![alt text][image_5]
    
_______________

<a id='MENTOR'></a>
## Classroom Mentor

- The role of a classroom mentor is to answer your questions regarding the courses that you are taking. We enjoy answering questions, so feel free to post your questions in the mentor chat window.

- When you post a question or comment, you can expect a reply within 24 hours - i.e. communication isn't *Live*, classroom mentorship is not a *chat service*. I will respond to your questions as soon as possible.

- So any technical questions that you have will have to be posed in a way that is clear, so that I can answer them directly (i.e. if I need clarification on any parts of your question then they will be difficult to answer, and will lead to a frustrating time lag for you).

  - Include a link to the quiz, where relevant.
  - Include any code (see below), where relevant.

- Classroom mentors do not review projects before submission (We can clarify questions that you have about the requirements or review comments but we can't pre-review projects). Once you are happy that you have met the requirements (laid out in the project Rubric), then you are ready to submit your project.

<a id='SNIPPETS'></a>
## Posting Code in the Chat Window:

- On **separate** lines, **before** and **after** your code, you put three **backticks**  (which are beside 1 on a QWERTY keyboard  <kbd>  ` </kbd> <kbd>  1 </kbd> </kbd> <kbd>  2 </kbd>  ) - which looks like (*See the footnote for other keyboard layouts* <sup>[1](#myfootnote1)</sup>):

    ![alt text][image_0]
    
- To move to a new line, in the chat window, press <kbd>Shift</kbd> + <kbd>Enter</kbd> at the same time.

- **Note**: Any spaces on the lines with _`'backticks'`_ will produce very odd formatting.

- For example:

    ![alt text][image_1]

- That is, the individual steps are:

  1. Type three backticks.

  2. Press <kbd>Shift</kbd> + <kbd>Enter</kbd> at the same time (to move to a new line).

  3. Copy and paste your code directly into the window.

  4. Press <kbd>Shift</kbd> + <kbd>Enter</kbd> at the same time (to move to a new line).

  5. Type three backticks.


<a id='CODE'></a>
## Posting Code on an External Site:

You can post your code at http://pastebin.com/ - **No Login is required**

1. Go to http://pastebin.com/

2. Copy and paste your code into the window in *`pastebin`*

3. Select the appropriate syntax highlighting (type the first few letters of the language).

4. Click *`Create New Paste`* and copy the **URL** and **post that URL in the chat window**

    
    ![alt text][image_2]
    


*(Note: There are many different external sites that allow you to post code. Feel free to use the service that you prefer).*

## Footnotes:

<a name="myfootnote1">1</a>: <a href="http://superuser.com/questions/254076/how-do-i-type-the-tick-and-backtick-characters-on-windows">Location of 'backticks' on different keyboards</a>
