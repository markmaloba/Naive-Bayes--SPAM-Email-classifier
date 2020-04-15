# Background

Long ago, in a distant land, email was established as a form of communication for the public, those who would wish to do us harm followed right on the heels of this invention, tying all they could to turn it into a proponent for EVIL!

However, not all hope is lost! The realm of men (read *consumer emails*) is protected by valiant warriors (read *Nerdy Machine Learning Engineers*) on the frontlines battling spam email and its propagators.

The dataset used here is a result ofsuch an attempt by Hewlett-PAckard engineers. Luckily, the data has been cleaned quite well, and already tokenized for our use, so there is no need to use any natural language processing toolkits.



### Defining the question

Using a sample of 4600 emails, all correctly identified as either SPAM or NOT SPAM, can we create a Machine Learning model that correctly categorizes received emails in either of the two categories?

### Metric for success

Modern email spam filters are not 100 percent accurate. Google, for example, has a distinct advantage in this space by virtue of providing the service that handles about **twenty percent** (that's a conservative estimate) of opened emails worldwide. At 111 billion consumer emails sent per day, 20% is a pretty large chunk of that.

That means that they have A LOT more data to work with, and they have continually refined their AI as far as spam filtering goes.

With our modest DATASET, I'd be very comfortable with a 70% accuracy rate, and OVERJOYED if 80% is achieved.

### Experimental design choices

We will use a Gaussian Naive Bayes algorithm to solve this problem, for reasons explained as we go along.

### Appropriateness of the data to answer our question

AS far as sppropriateness goes, the answer is 1-for-1. You need smaple emails for analysis if you are to categorize them as spam. That's what we have here, a PROPER sample of 4600 emails to use in our analysis. Yes the data is appropriate.
