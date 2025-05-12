![alt text](images/PopSkully_Tag.jpg)

# Cross-chain Rebase Token

1. A protocol that allows user to deposit into a vault and in return, receiver rebase tokens that represent their underlying balance.
2. _Rebase token_ -> balanceOf function is dynamic to show the changing balance over time.
   - Balance increases linearly with time.
   - Mint tokens to our users every time they perform an action. (minting, burning, transferring, or.... bridging)
3. _Interest rate_
   - Individually set an interest rate for each user based on some global interest rate of the protocol at the time the user deposits into the vault.
   - This global interest rate can only decrease to incentivize/reward early adopters.
   - Increase token adoption.
