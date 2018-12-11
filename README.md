# BigDataProject3
A CNN and a Logistic Regression model for classifying tweets as talking about medical condition: No [0], Yes[1], Ambiguous [2]

# Instructions:

  To train the networks (optional):
  
      python train_network.py --model TWEETNET
      
      python train_network.py --model TWEETCONV
  
  To run the networks with the tweets gathered using the keywords:
  
      python use_network.py --model TWEETNET
      
      python use_network.py --model TWEETCONV
      
Results can be found in the 'results' folder in the main directory. 

# Network Validation Acc
  TWEETNET: ~75%
  
  TWEETCONV: ~76%
