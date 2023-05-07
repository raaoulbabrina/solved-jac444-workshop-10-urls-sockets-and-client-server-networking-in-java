Download Link: https://assignmentchef.com/product/solved-jac444-workshop-10-urls-sockets-and-client-server-networking-in-java
<br>
This assignment lets you practice Multi-Threaded programming in Java and includes concepts such as Threads, Guarded Blocks, and Synchronization.<strong> </strong>

<em>Give a solution to the following problem: </em>

You want to help your friend with some money. You and your friend have access to a shared account, but in a “Strange Bank.”




The Strange Bank has the following rule for the accounts: once you deposit some money in some currency (to an account with an initial balance of zero,) you are not allowed to deposit money in another currency, unless the account balance would be zero (again.)




You have one Dollar, two Euros, and three Pounds and you want to transfer these amounts to your friend. Write a Java program that simulates you depositing to and your friend withdrawing from the shared account.




<em>Hints: You and your friends are Java </em><em>Thread</em><em>s that try to access the bank account concurrently (you to deposit, your friend to withdraw). You must communicate through </em><em>wait</em><em> and </em><em>notify</em><em> methods. </em>

<em>Make sure that <strong>all the deposit and withdraw actions between you and your friend should happen to be in </strong>amounts of one<strong> (at a time)</strong>. </em>

<em> </em>

<em>This is a classical problem in thread theory called “Producer/Consumer” in which there is a container that accepts only one object at a time. Producer wants to put in the container as many objects as it produces but must wait until the consumer consumes the already-shared object from the container. </em>

<strong> </strong>