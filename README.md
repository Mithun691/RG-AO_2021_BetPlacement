# RG-AO_2021_BetPlacement

***A framework to place bets for ATP tornaments based on B365 betting rates tested on Australian Open & Rolland Garros 2021***

!<img src="https://media.gettyimages.com/photos/novak-djokovic-of-serbia-celebrates-against-juan-martin-del-potro-of-picture-id1149924107?k=6&m=1149924107&s=612x612&w=0&h=MkEIPn0ucLWeW436tDdhPDy7Kx1NfxHR4VRQnWKaTLk=" width="450" height="400">
!<img src="https://media.gettyimages.com/photos/rafael-nadal-of-spain-celebrates-after-winning-a-point-during-his-picture-id1279355454?k=6&m=1279355454&s=612x612&w=0&h=U9Ad5ry79KDm5ind2zWj-bcUnn5XEY31NYnE_Ndd5jQ=" width="450" height="400">

1) The framework models the winning probabaility using a bayesian neural network trained on 16 features like h2h, record on surface, career win-loss, ATP rankings etc.
2) The winning probabilities,the variance from this network along with the betting odds(Bet365) are then incorporated in the algorithm to place bets optimally
3) The output of the algorithm is the % of money in hand that should be placed in the bet & on which player

## Results

#### Money Multiplier for Australian Open 2021 - *1.18*
#### Money Multiplier for Rolland Garros 2021 - *2.05*

### -------------------------------- Money In Hand Across RG-2021 --------------------------------------
<img src="https://user-images.githubusercontent.com/54732254/128619656-a4350473-0469-42ce-a7ad-105e97afd2d7.png" width="750" height="500">






