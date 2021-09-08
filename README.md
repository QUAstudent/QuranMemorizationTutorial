# MEMORIZING THE QURAN TUTORIAL #

## SUMMARY ##
In this tutorial, we introduce an effective method to memorize the holy Quran in full. This method works regardless of previous memorization capabilities. The goal of this method is to enable the reader to reach a state of reciting the entire Quran from memory in front of Allah SWT on judgement day. 

## HOW NOT TO MEMORIZE THE HOLY QURAN ##
In order to succeed, it is important to also understand and avoid failure conditions. We share some common ones below:
*	Memorizing many new pages per day.
*	Allocating a long time for memorization per day especially in the beginning
*	Not setting up a consistent dedicated time for the memorization.

## THE ALGORITHM ##
We share a 3 milestone multi-year process as following:

### MILESTONE 1: PREPROCESS ###
During this milestone, we don’t aim to memorize the Quran but to prepare your heart and mind for the actual memorization procedure in the next milestone. By the end of this milestone, you should have accomplished the following:
*	Have recited from memory every single page in the entire Quran to a peer (but may have forgotten many/most/all of those pages already).
*	Is capable of reciting from memory at least 10 consecutive pages chunks anywhere in the Quran if given an hour to review.

This milestone should last anywhere between 1.5 to 3 years depending on memorization progress and enthusiasm. It is important to emphasize that __consistency is more important than speed__ in the entire process. The memorization process in this milestone consists of the following components:

*	Memorize
    *	Should be no less than __half a new page__ and no more than __1 new page per day__.
    *	__Listening__ before reading/memorization helps hearing the right pronounciation.
*	Review
    *	Should start at no less than __2 pages__ of previously memorized (but maybe forgotten) and recited pages.
    *	Note that, if you couldn't finish the revision pages on time, __try again the next day__ but don't do partial revision (maintain a consistent monotonically increasing window size).
*	Recite
    *	Should be to __a friend or peer__ over a call that is scheduled at a fixed time ideally every day. 
    *	This call should be run like a __scrum__ in project management and should be __chitchat-free__.
    *	This call should take __no longer than 15 minutes__ and should recur ideally __every day__ in the week.


The mechanics of the algorithm rely on a variation of spaced repetition memorization technique. We employ two memorization pointers: __a slow pointer__ for the __new page__ memorization and __a fast pointer__ for the __review pages__. The slow pointer always runs at a fixed rate of no less than 0.5 new page per day and no more than 1 new page per day. The faster review pointer starts at 2 pages per day and increases by 1 page on every crossover. For example, consider the following run:

*	Day 1: memorize new page 1. No review. #-- (no review warmup period)
*	Day 2: memorize new page 2. No review.
*	Day 3: memorize new page 3. No review.
*	Day 4: memorize new page 4. No review.
*	…
*	Day 10: memorize new page 10. Review page 1 and page 2. #-- (start adding review)
*	Day 11: memorize new page 10. Review page 3 and page 4.
*	…
*	Day 18: memorize new page 18. Review page 17 and page 18 #-- crossover 1 (increment the review pages by 1)
*	Day 19: memorize new page 19. Review page 1,2, and 3. #-- now we review 3 pages every day but say that you really struggled with the 3 pages and your memorization was weak/non-acceptable especially on the last page (stops, stuttering, and mistakes).
*	Day 20: memorize new page 20. Redo the review page 1,2, and 3. #-- Retry the revision from yesterday since we couldn't do all the revision pages well.
*	Day 21: memorize new page 21. Review page 4,5, and 6 #-- Continue revision normally
*	…
 
The execution goes as following:

*	Schedule a __no-more-than-1-hour__ meeting each day to memorize. 
    *	You should be all by yourself and your Quran.
    *	This time should __never be interruptible__ by anything no matter what.
*	Find a __peer or a friend__ and schedule a __15-30 minutes phone call__ with that friend ideally every day to recite to each other.
    *	The friend needs to at least be __able to read the Quran in Arabic__.
    *	It is important to emphasize that this phone call should be laser focused on the goal and shouldn’t involve any chitchat. 
    *	This way, it remains __lightweight/agile__ and doesn’t become a burden with time.
    *	If you __don’t have a friend__ or prefer to go by yourself, you can __record yourself reciting__ and then play it back while looking at the Quran to review your own recitation. Though a peer is more preferred to maintain the momentum.


### MILESTONE 2: MEMORIZE ###
At this point now that you have finished preprocessing, you are now __ready__ to actually __start__ memorizing the Quran. The goal of this milestone is to __minimize the time it takes to review the entire Quran from memory__. In other words, we would like to maximize the length of the daily review pages now that there are no new pages to memorize/preprocess. Assuming that maximum review window length from previous milestone was 10 pages per day (60 days to review the entire Quran from memory) we demonstrate __the doubling algorithm__ with the following example:

*	Day 1: review pages 1-10.
*	Day 2: review pages 11-20.
*	Day 3: review pages 1-20 #-- first even doubling
*	Day 4: review pages 11-30
*	Day 5: review pages 21-40
*	Day 6: ...

Using this method, we train our memory to __double the number of pages we can review in 1 day__. We repeat the doubling until we converge to __100 review pages per day__. Once we reach that point and stabilize, we should maintain the review of the entire Quran every 6 days at that pace and move on to the next milestone.


### MILESTONE 3: MARATHON ###
The goal of this milestone is to enable ourselves of __full Quran recitation from memory at once__. This way we prepare for the __judgement day recitation__. It is expected that we have already reached stability from previous milestone and in this stage, we want to apply doubling algorithm with 100 pages increments until we recite the full Quran over the entire day.

## FAQ ##
*	Q: I realized that I forgot everything from yesterday :( Should I go back?
    *	A: __No__. Just forget about yesterday altogether and move on. It will come back in future iterations.
*	Q: You said to only allocate 1 hour each day in milestone 1 and then said that I need to memorize [0.5, 1] new page along with reviewing a monotonically increasing number of pages from previously forgotten memorization, how can I do all that in __just 1 hour__?
    *	A: This is the beauty of this algorithm. So, the basic idea is that for new pages that have never been heard, it may take up 30-40 minutes of time to memorize them. But once you memorize and then forget, it will come back to you in progressively shorter times. For example, after you forget the first time, it will take 10 minutes to come back (even if it took more than 30 minutes to memorize the first time). Should you forget it again then that becomes 3-5 minutes and so on. Some pages will never be forgotten as you make progress.
*	Q: I feel sad that I forgot all the Suras that I memorized during childhood. What should I do?
    *	A: Just __focus on the task for the day__. It will __come back in future iterations__.
*	Q: When is the best time to memorize?
    *	A: That varies from one person to another but I personally prefer __after fajr__.
*	Q: Are all the awesome things we hear about those who memorize the Quran true?
    *	A: Yes in Donia and Akhera.
* Q: When should I start?
    *	A: Right now!
