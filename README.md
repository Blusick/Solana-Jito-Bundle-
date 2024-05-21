# Solana Jito Bundle
You can find in this repo my work on a solana jito bundle (token deployer + snipe lp bundle and more)

# How does it work ?

    -> Edit config.js, there are 2 different keypairs and a rpc.  One is for paying all the sol distribution fees 
    and one is for creating the pool (so they have no ties whatsoever). 

    -> Run 'npm i'

    -> Start the script with 'node main.js'

# Menu 

    1. Create Keypairs
    2. Pre Launch Checklist
    3. Create Pool Bundle
    4. Sell All Buyers
    5. Sell % of Supply
    6. Remove Liquidity
    Type 'exit' to quit.

# BUYER UI 

    1. Create Market (0.3 SOL)
    2. Create LUT and WSOL ATAs Bundle
    3. Extend LUT Bundle
    4. Create ATAs and Send SOL Bundle
    5. Simulate LP Buys (Get exact amounts)
    6. Send WSOL Bundle
    7. Close WSOL Accounts to deployer

# FEATURES


    -> Create keypairs (1).  Don't need to do it for every launch, just when you want but ensure there no SOL in them. 

    -> Premarket (2).  DO ALL STEPS 2-6 IN ORDER!!!!  After each step check the Bundle ID to make sure it lands.  It the bundle
    doesn't land simply redo that step with a higher tip!  Then exit.  Check here: https://explorer.jito.wtf/

    -> CREATE POOL (3).  To create a pool just spam the function because sometimes it doesnt land.  Either increase the tip or SPAMMMMMMM. 
       I recommend tip of 0.1 SOL or more to land within the first few tries.

    -> SELL FEATURES (4/5).  Since pool is now live you can either SELL ALL keypairs at once using (4) and reclaim the WSOL in step 7 of 
    Premarket (2) after you rug.  YOU CAN ALSO sell small %ages of the supply before hand on demand (5).  It does this by sending 
    (input)% of every keypairs token balance to the fee payers then sells it all in 1 singular bundle AND only on 1 wallet!

    -> LP REMOVE (6).  If you dont burn your LP it simply removes it hehe

# Contact / Support

-> If you are interested by my script just send me a message on tg : @Blusick

