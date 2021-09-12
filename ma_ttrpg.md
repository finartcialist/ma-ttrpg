# M&A

**the tabletop RPG for everyone** 

## WARNING

This is a fictional artgame based on imaginary events, processes and companies. It's not meant to be fun not insigthful. Hopefully there will be entertainment gained during the reading of the rules.

Not meant to be representative of actual business processes - this is an arts game.

## Intro
The goal of the game is to be part of a conglomerate with the highest average Equity/Stock action ratio.

## Game set-up

### Character creation

The possible roles are: Market Maker, VC, Independent Business, and National Business Board.

There should be at most one VC for every three businesses; there can be no VC. 

There should be one and only one Market Marker and National Business Board.

#### Market Maker

You are the person responsible for managing this game; in other words, the DM. You are already winning.

#### VC

You start with more Equity than other players but with no Stock of your own. You have to build a conglomerate through Acquisitions only. You get to vote on pitches from Independent Businesses. You win if you have the highest Equity/Stock ratio.

You can gain or lose experience points on three categories: 

* Charm ( 0 to 10 )
* Thought Leadership ( 0  to 10 )
* Assertiveness ( 0 to 10 )

At the start of the game, you get 7 points of experience that you can choose to distribute however you like, given that every category must have at least one point.

#### Independent Business

The standard character. Roll the die to see how much Equity and Actions you start with. You can do both Mergers and Acquisitions. You can pitch to VC to raise Equity. You win if you have the highest Equity/Stock ratio, or as a part of the conglomerate with the highest such ratio.

You can gain or lose experience points for three categories:

* Perseverance ( from 0 to 20 points )
* Creativity ( from 1 to 11 points )
* Diplomacy ( from 0 to 10 points, works as a torus - see the Private Equity move section of the Rules) 

At the start of the game you get 9 points of experience, that you can choose to distribute however you like, given that every category must have at least one point.

#### National Business Board

Your role is to catch any wrongdoing and to favor competition between businesses. You get a percentage of every transaction. Since you cannot do either Merges nor Acquisitions, you can win the game if: 
a) the ratio of times you caught someone doing something to the number of times you did not manage to catch them or there was no wrongdoing is is higher than the highest weighted Equity/Stock ratio;
b) there is no clear winner, that is, the top two Equity/Stock ratios are less than 0,5 apart.
c) you also instantly win the game if you win an antitrust lawsuit.

You can gain or lose experience points for three categories:

* Cleverness (0 to 20 )
* Diligence ( 0 to 5 ) 
* Strategy ( 0 to 10)

At the start of the game you get 8 points of experience that you can choose to distribute however you like, given that every category must have at least one point.

### Non-playable companies

Every player gets to draw at least 3 cards with Non-Playable Companies categories featured on them. These cards must feature the same categories of points as IBs. 

After this is completed, the cards are shuffled and placed facedown on the table.

## Rules

Every turn follows an order:

* Deciding who is the first player for this turn. Next players are decided in a clockwise manner.
* Each VC and Independent Business players makes one possible move. Note that these moves might attract the attention of the NBB if there are discrepancies between the actors actions and the Rules. See the "Possible moves - National Business Board" section for more information.
* the value of each company in play is decided according to the dice 
* the National Business Board makes one move
* Anyone can change a rule, following the playing order, but only one person - the first one to succeed at changing a rule. Only one rule can be changed at a time.

### Possible moves - VC and Independent Business

Each time it is your turn you can do one of the following actions:

- Try to raise the Equity value of your business or part of conglomerate
- Try to merge with someone with the same role as you
- Try to acquire an Non Playable Company
Any other move must be passed through a throw of dice.

#### Try to raise Equity value

You can decide to raise the Equity value of one of your company by doing one of two things depending on the role of your character:

* If your character is an Independent Business, you can choose to do Private Equity (try to impress a VC in investing in your business) or to IPO (roll the dice to try to raise money from the general public)
* If your character is a VC, you can choose between Index Fund (roll the dice to try and invest your Equity on the public market) or Loan (roll the dice to see how much debt you can raise)

##### Private Equity

If you are an Independent Business, you can try to raise Private Equity from VCs, as long as those VCs do not own you as a part of their conglomerate. 

How it works:

* The Independent Business do a 30-second Pitch as to why we should invest in their business.
* Every VC rates the pitch on a hidden piece of paper, on a scale from 0 to 1,000,000
* To see if a pitch worked, the score is calculated in the following way:
        ( sum_vc ( score_vc * thought_leadership_vc) ) * creativity_ib / diplomacy_ib
* If the total score is below 100,000, the IB can roll a dice to see if they have a Last Chance to win their case: they win if they roll a one on a cubic dice.
* If the total score is between 100,000 and 500,000, the IB gains this amount in Equity.
* If the total score is over 500,000, the IB needs to see if the Private Equity can be transferred by rolling a 6-dice with a chance of 1/3 of having to accept only 500,000.

At the end of the Private Equity move:
* the IB lose a Diplomacy point if they managed to raise funds
* otherwise, IB wins a Diplomacy point
* If the Diplomacy points of the IB are are zero, it goes back to being at 10
* If the IB won through a Last Chance roll, all VCs lose one point of Thought Leadership.
* If the IB pitch worked (through a normal vote or with a Last Chance roll)

##### IPO

You can also decide to try and raise money from public markets.

How it works:

* Pick one and only one Company
* Roll a 20-sided dice. Note the number obtained.
* You need to score your business for the market: 
        round_down((Perseverance*number_obtained)/Creativity)
* If the score is at least 5 * (result of a roll of cubic dice), then you may increase the Equity of the Company you chose by (result of a roll of a cubic dice)/100.

##### Index Fund

If you are a VC you can try and invest your Equity on the public market. In this case, it works but we don't know by how much. Roll a cubic dice and raise your equity by (number obtained)/100, except if the number obtained is one; in this case, lose 2% of your equity.

##### Loan

If you are a VC and you try to get a Loan, in this case we don't know if it will work but we know how much is in play.

How it works:

* Choose the amount of debt you want to ask for, on a scale of 0 to 5% of the value of the highest single-Company Equity owned or played by one of the VC/IB.
* Roll a 20-sided dice. Divide the result by 2. If your Assertiveness is higher than the result, you have been pre-approved for a Loan.
* To see how much you have been pre-approved for, calculate the following:
        amount_asked * ( your_assertiveness / average_assertiveness ) 
* Now you need to seal the deal with your Charm. If your charm is lower than 5, roll a cubic dice with chances of 1/3 of winning; if your charm is at least 5, roll a cubic dice with chances of 1/2 of winning. If your charm is 10, roll one on a cubic dice to win. 

At the end of the Loan move:

* If your Loan was pre-approved and the deal was completed, gain one Charm and one Assertiveness points.
* If your Loan was pre-approved but the deal was not completed, gain one Assertiveness point.
* If your Loan was not pre-approved, lose one Assertiveness point.

#### Try to merge with a Playable Company

If you are an IB, you may start the process of merging with a IB-owned conglomerate or a single IB. 

How it works:

* Start by identifying which Playable Company you would like to merge with.
* You first need to make an Informal Offer. It gets lost in the mail with a chance of 1/6; roll a 6-dice.
* The Playable Company needs to send you a Formal Answer. If they are a Conglomerate, they first need to reach consensus on the question. Their vote is compiled in the following manner: every IB of the Conglomerate has one vote, weighted by their Equity/Stock ratio. The total of these votes needs to be higher than the current Equity/Stock ratio of the Conglomerate in order to be able to send a Formal Answer. IBs not part of Conglomerates do not need to vote.
* The Formal Answer is misinterpreted with a chance of 4/20; roll a dice in private - the current player cannot know that they are misinterpreting the Formal Answer.
* The current player receives the Formal Answer and makes a decision on the Merging operation. They can only accept the Merging if the Formal Answer was positive and not misinterpreted. In this case, they have to send a Confirmation. 
* The Confirmation is misinterpreted with a chance of 1/20. If the Confirmation is misinterpreted, the current player can try to send another one at its next turn; if they do so it counts as one move.

#### Try to acquire a Non Playable Company

This move is available to both IB and VCs. You may acquire the current Non Playable Company displayed on the table.

How it works:

* Roll a 20-dice. This is the value of the Non-Playable Company you want to acquire, in percentage of the value of the most valuable Playable Company in your conglomerate or of your single IB.
* You can decide to take it or leave it.
* If you take it, you pay the price, you add the card to your conglomerate, and turn a new one immediately

### End of turn

At the end of each turn, every player rolls the Stock Market dice to see how their business evolves.

Every individual IB or conglomerate chooses at most one business for which they will throw the dice to decide the new value of the Equity. Roll a 20-dice; divide the result by 100. This is the percentage you are gaining or losing in Equity for the business you chose. Roll a 6-dice; you have 1/2 chance of having a gain, otherwise it's a loss.

### Possible moves - National Business Board

At any time during a VC or an IB move, the NBB can address a discrepancy between the players actions and the rules in the following way:

* First, it needs to make a call to the Market Maker to see if they see something. Roll a 6-dice and calculate the following score: NBB_diligence * rolled_number.
* If the score is at least 18, the call succeeds. The Market Maker is now convinced that we should inquire publicly.
* The NBB sends a Public Announcement in the newspaper. Each Playable Company roll a 6-dice to see if they care; if the total is more than the sum of two rolls of a 20-dice, they do care. The inquiry shall proceed.
* The concerned actors roll 6-dice; the one with the highest number is chosen as the Main Contact for the group. 
* The NBB and the Main Contact both roll a 20-dice; the highest number wins.
* If the NBB wins, they get experience points: roll a 20-dice. The amount of point you obtain is the lowest of the following:
        a) score_dice * cleverness / strategy
        b) score_dice * cleverness / diligence
* With chances 1/2, you get to choose where you can use your experience points. If not, your Diligence is increased.

When every VC and IB has played, the NBB needs to decide if it launches an antitrust lawsuit.

If they so wish, here is how it works:

* Roll a 20-side dice.
* Calculate the following: (strategy + cleverness) / diligence
* If this score is higher than the dice result, you may proceed. If not, the NBB loses one Cleverness point.
* Name the actors of the antitrust. Since the Market Maker can be part of the antitrust, you need to do this publicly. Actors need to involve one Conglomerate for the lawsuit to hold.
* Actors get to defend themselves. If they are part of a Conglomerate, they can choose to Spin-Off a business to comply with the antitrust laws. This business needs to be a Playable Business. This decision needs to be made after a majority vote where every Actor, including outsiders VCs, IBs and the MM,  gets one vote. After choosing who has to exit the Conglomerate, the antitrust lawsuit ends. The NBB loses one Diligence point and gains one Strategy point.
* If the Spin-Off fails, the antitrust lawsuit may proceed. The NBB gains one Diligence point and one Strategy point before computing the following score:
            (roll-20-dice * diligence * cleverness ) / strategy
* The score of the Actors is computed in the following, where the points are taken from the Spin-Off profile:
            (roll-20-dice * (diplomacy/4) * perseverence ) / creativity
* Whoever has the highest score wins. Note that the NBB winning means they win the game.

### Possible moves - changing one rule

Rules of the game are negotiable. You first need to convince the Market Maker AND the NBB to listen to you. The rules of this negotiation are not negotiable.

How it works:

* First, state which rule you would like to change.
* both the MM and the NBB must be at least 1/2 willing to listen to your point. Roll a 6-dice.
* If they are both convinced, you may proceed to argue which rule should we change and how. Don't forget to explain why.
* Have a constructive discussion about the proposition. Keep in mind that only one rule can be changed at a 
time.
* Host a vote on the rule. The person to propose the rule can vote, and can vote against the proposition as it might have evolved. The MM is responsible for ensuring the fairness of the vote. In case of a draw, the NBB decides what to do.

## End of game

The game ends when :

* There is a duopoly.
* There is a conglomerate whose membership consists of at least 1/3 of total players, excluding the Market Maker.
* The National Business Board wins an antitrust lawsuit;
* All the VC and IB players have been eliminated through bankruptcy.

Monopoly situations are prohibited.

For IBS and VCs, only members of a Conglomerate can win, no matter if it's owned by a VC or by an IB. The one with the highest weighted Equity/Stock ratio wins.
