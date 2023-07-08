
# Rarity algorithm for NFTs in XDC Network



Every NFT collection has attributes that consist of traits and values. Each trait and value defines the rarity of the NFT asset.

We Calculate the Rarity of the NFT in the following way:


## Step 1: Calculate the weight of each trait 

Tn = weight of trait n
An = No. of times the nth trait is repeated in the entire collection
N = Total number of NFTs in the collection

Tn = ( An / N )




## Step 2: Calculate the weight of each value

Vn = weight of Value n
Xn = No. of times the nth trait is repeated in the entire collection
N = Total number of NFTs in the collection

Vn = ( Xn / N )



##  Step 3: Calculate the total rarity using traits and values combined

TR = Total Rarity

TR = Tn + Vn



## Step 4: Calculate the final rarity using traits and values combined

FR = Final Rarity

FR = Sum of TR for the values
