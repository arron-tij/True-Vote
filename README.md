# True-Vote
A blockchain based website to conduct secure and reliable elections.
# Features and their implementation:
- ### Know the candidates:
    > The majority of voters are oblivious to the true records of all the candidates contesting the elections which leads to them making ill-infomed choices based on information they get from untrustworthy sources

    The homepage of the website will contain a verified information desk with the list of all voters. Each candidate name will be a link to all their pevious records such as "Number of promises kept", "Criminal records", "Educational qualifications" etc. The voters will hence be able to compare the candidates.
- ### Registration:
    >Many people eligible to vote are not able to due to lack of a voter ID and the process of creating one is a time consuming process. Many people hence choose to ignore to vote even upon turning 18.

    The website will have access to the Aadhar Card (or other similar form of identification varying from organisation and country ) so that as soon as a candidate turrns 18 his name will be added to the voting list. All they would have to do is register themselves once with a username as their Aadhar number and set up a password. The registration process will be made secure using a confirmatory email and a face verification (via webcam).

- ### How to vote?
    >It has been seen many people out of laziness or remoteness of their houses find it tiresome to go to voting centres to vote.
    
    Anyone with a internet connection, a computer, and a webcam can vote. Apart from this voting centres can also be set at places with no internet connectivity where people can log in and vote. 
    To vote, the user will login using their Aadhar number as username and previously set password. A confirmation email will be sent to their registered email ids with a unique private key and they would also be required to verify their presence by clicking their face via webcam. Access would be denied if the voter's face doesn't match their aadhar verified picture or in case there are more than one person (the voter)in the room.
    Now the voter will have to choose the candidate they wish to vote and enter their private key they received and hit submit. 
    Each vote will be sealed in a block and get added to the existing blockchain. Each block would be added only if the private key entered is one among the ones which were distributed to voters. Now since a copy of blockchain is stored on every voter's computer, changing a vote would require altering the chain on every computer and this would require a heavy computing power which makes the votes very safe. 
    Using this process the counting of votes would be done in real-time too with the vote count of each candidate being updated after every vote.
    
    
    

    
    
    




