# Teaching Mining:

When ever blocks are mined, the miner receives a reward for their hard work.

Blocks are mined, on average, every 10 minutes. 

Mined blocks, are: 

- A list of all transactions.
- Those transactions are added together to create one long 'string'
- That string is then put through a function that does SHA256 vs another RANDOM NUMBER.
- The function keeps going until the result comes out with the required amount of 0's in the beginning.

### Practical example:

- Teacher has a list of [5] 'transactions' that are simple math problems.
- The students need to complete all the problems and save the answers.
- The answers are then added together.
- The students need to find out how much more needs to be added so that the number equals 'xxx'
- The first student to add all the numbers, and get the magic number is the winning 'miner' and is rewarded the payout.
- Next block!. If the time was quick, hand out a more difficult paper. If the time was slow, hand out an easier paper.

### Demonstration.

> The following is expanded upon in the [mining worksheet](MINING_WORKSHEET.md)

Teacher hands out a paper, that has the following problems:

1. 4+8=
2. 2*9=
3. 10/5=
4. 80-72=
5. 12*3=

The student answers the questions and has the answers:

1. =12
2. =18
3. =2
4. =8
5. =36

The student then ADDS all these numbers

`12+18+2+8+36 = 76`

The number needs to be 111! How much do you need to add to get 111?

`111-76 = 35!`

The magic number is `35`! The first student to show the teacher their CORRECT proof of work wins the block!
