how to choose ??
    CCA is not selected as in production it is dangerous because our model can never handle missing values there as it was never trained, just to learn we saw that
    Univariate-mean/median is used only if distribution is not changed after applying
    only if variance,correlation changes are comparable 
    most important condition is MCAR

    ARBITRARY
        if not missing at random then use this assign any value just to tell model this is something different as missing like age =-1 not possible
        use only if variance,correlation changes are comparable
        use only if  distribution is not changed after applying
        mostly used in categorical data