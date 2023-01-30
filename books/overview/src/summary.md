# Summary

The society works on the premise of "getting and keeping a good reputation increases your income".

All of the below rules are starting value suggestions and should be changed as needed by society.

## Sub systems

### Ratings

There's a google page rank like algorithm that allows people to trust other people to *do certain things under certain circumstances*.

Initially you'd port over old world certifications. You'd upload a copy of your certificate, and people would *trust* the certificate to be legit.

Later there would be a chain of skills passing down through teaching. For example:

 * I trust Joe to lay bricks well.
 * I trust Joe to teach brick laying and certify new people
 * Joe declares he has trained Sam, and now Sam can lay bricks

Once this system is established finding a job and workers should be as easy as typing into a search.

#### Growth over time

As you continue to serve in a role over time, your trust / rating levels increase and so does your income every time you do your job.

This will be written into the automated rules.

TODO: Should there be a dampener? For example a brick layer can't get infinitely better than other brick layers. Perhaps the trust level should grow logarithmically then transfer into trust as a teacher?

### Democracy

As the whole system is based on automated rules there will be several "jobs" ways to make money:

 * Proposing new rules and alterations to existing rules
 * Filtering new propsals (Because everyone gets a say, there would be a lot of proposals)
 * Voting on filtered proposals
 * Coding the laws into automation
 * Monitoring newly implemented changes and proposing adjustments

Initially everyone gets the same level of trust in all of the above jobs. This level can go down for low quality work (eg. prank proposals) or corruption.

The higher your trust level:

 * The higher up the list your proposals go
 * The higher your weight when filtering
 * The more weight your vote has? TODO: ?
 * The more visibility your code suggestions will have
 * The more weight your adjustment proposals have
 * The more you get paid

People that have given few proposals/code/filters will get extra weight to prevent entrenchment and promote visibility of new.

You get more pay if you contribute to a law that gets implemented and more still the longer it goes unchanged, up to say a year.

### Economy

Your ID/token can own money.

The economy is automated and self regulating according to automated rules.

Main tenets:

 * Money is created as needed to fund:
   + Universal Basic Income
   + Infrastructure projects (bridges, train tracks, cabling, etc)
   + System hosting costs (block chain nodes, index providers, etc)
 * Inflation is defeated through money eating rules and making it harder to create new money
 * There is a target money pool size of $100k per token/ID
   + This will mean the pool size will grow/shrink with the population
 * The rules will aim to reach the target pool slowly. Over say a year.

#### Target money pool

There is a target money pool size of $100k per token/ID.

Automated rules aim to reach the pool size within 12 months.

##### Money eating rules

Money eating rules reduce the overall money pool size (and so inflation) by destroying money.

At the beggining of each 4 week period:

 1. The distance to the target is calculated.
 2. The upcoming period's transations are estimated (through some stastistical rule)
 3. The upcoming period's transaction fees and (possibly reverse interest is declared)

At the end of the period:

 4. The interest is applied to every money store

For example:

 1. There are 2 billion people / tokens / IDs in the system
    1.1. The target money pool is 2 billion * 100k
    1.2. Suppose we are a 100 million over the target
 2. We estimate there will be 20 trillion dollars (10k per person) of transactions this upcoming period
    2.1. We want to reach the goal within 10 periods, so this period we need to destroy (100 million / 10 = 10 million)
    2.2. We split the 10 million 50/50 (TODO: Should this be adjustable?) between transaction fees and negative interest
 3. We declare a transaction fee of 5 million / 20 trillion = 0.0000025 %.
    And an interest rate of (-5 million / current money pool (2.1 billion) = -0.238%)
 4. All transactions during the period incur the fee automatically.
    At the end of the period all money is decreased by 0.238%

The negative interest rate would encourage people to spend and drive the economy.

The transaction fee would dampen unnecessary spending.

##### Money creation management

New money creation is for infrastructure projects is managed by voting. I 

START HERE
   
    
 * Transaction fees
 * Reverse interest




#### UBI

### Infrastructure projects

## Safe guards

### Anti-corruption

Accusations of corruption should be investigated (by people who are trusted to do this).

The penalty for false cliams should be a severe drop in trust. This will be written into the automated laws. I suggest `n` years of lost growth plus `n` years of a red flag being on record.

### Resetting

Should a bad actor screw up their token/id so badly, they'd better off getting a new one, we'd prevent that by:

 * Initially there'd be a 1 year stand down with on economic activity for new tokens
 * New Ids/tokens need to be authentited by trusted authenticators using old world ID documents
 * Eventually when someone is born, a someone who is trusted to assign new IDs working at the hospital would assign their ID. The ID would become economically active 18 years later.
