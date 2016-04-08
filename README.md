# Quadratic Vote Slack Bot

QuadVoteBot is a slack bot that allows teams to vote quadratically. This is a vote buying system where everyone can purchase as many votes as they want within their budget, but the cost of each vote goes up by the square of the vote count. So 1 vote costs 1, 2 votes cost 4, 3 costs 9, and so on. At the end of the vote, the collection of money used for voting is distributed on a pro rata (the pile is divided evenly amongst the citizens) basis to the community.

This leads to a situation where a person who really wants a vote to pass can save up there vote money and spend it. However, it will be costly because of the squaring of cost. Additionally, a collection of impoverished voters can still overwhelm a rich voter because they can still vote cheaply.

Where in a direct democracy, there is always a loser, in a quadratic democracy, there is some conciliation to the losing side because of the redistributing effect. Instead of lobbying the government, plutocrats can use their money as a part of the system. And where that lobby money would normally have enriched a minority of powerbrokers, it is then redistributed back to the populace.

For the purpose of the SlackBot, we create a situation where everyone starts off with one hundred vote dollars. People can call a vote on a subject. Slack participants then vote for or against, and mark their vote quantity. The pile is then evenly redistributed to the participants.

### Dependencies

Quad Vote Requires:
- Python
- MongoDB
- Heroku

### Slack `/slash` commands

### Configuration

### Running QuadVote Locally

### Running QuadVote on Heroku

### License
