# Pricing an nft using attributes

# for the model we hqve two things to consider:
# 1. the attributes of the frenchie
# 2. the floor price of the frenchie

# To price the features we can use past data of the frechies that were sold 
# by detrending the trade price from the floor price to remove the effect coming from the market demand
# then we will be able to price frecnhies amoung them purely based on the attributes
# after adjusting (multiplying by the floor price) we are able to get the price for any nft

# we can use a linear regression model to predict the trade price of a frenchie
# we can use the attributes of the frenchie as features and the floor price as the target variable

# an other model is just to take a tree model and use features as categorical variables to predict the trade price

# look at the most similar nft with the most common attributes and use the trade price of this frenchie as the price of the frenchie we want to price and use an average accross the most similar frenchie to get the price