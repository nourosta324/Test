![SC](https://github.com/user-attachments/assets/7835ce07-94e7-46c3-ad6d-9572b215168c)
The goal of this project is to predict the optimal amount of raw materials a company must order to end up with exactly 1,000 functional pieces. 
The process goes through 5 different machine and each machine has a given failure rate.
Given the failure rates, I began by working from machine 5 all the way to machine 1 to discover how many pieces the company must order. 
If we want to end up with 1,000 pieces and machine 5 has a failure rate of 1.9%, then we must use this formula to determine how many pieces passed through machine 4: (1,000/(1-0.019))
(1-0.019) signifies the amount of pieces that passed through 
