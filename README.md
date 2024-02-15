# react_
Assessment
 # Burn Page UI Fragments
 # Overview
 # Why Fragments?
 This repository contains a Burn Page component, which is part of a larger application. The Burn Page allows users to burn tokens and view related statistics and transactions.
 The UI of the Burn Page component was split into several selective components to make the code easier to read, maintain, and reuse.

1. **BurnButtonBar**: This component handles everything related to burning tokens, like the input field for the amount to burn and the burn button. Breaking it into its own component helps keep the burning functionality organized and easy to understand.

2. **BurnStatsContainer**: Here, you'll find the display for burning statistics, such as supply bars and labels. By splitting it into a separate component, we can focus solely on rendering statistics, making the code cleaner and more manageable.

3. **TransactionTable**: This component deals with presenting the table of burn transactions. Breaking it down isolates the logic for displaying transaction data, making the code more organized and readable.

4. **ChainSelector**: Responsible for allowing users to switch token chains, this component is now neatly separated from the rest of the UI. This makes it simpler to manage and reuse across different parts of the application.

5. **AppToast**: Handles the display of toast messages. By fragmenting it into its own component, we centralize the logic for showing toast messages, making it easier to use throughout the application without duplicating code.

# Conclusion
Fragmenting the UI into selective components improves code readability, maintainability, and reusability. By isolating different aspects of the UI into separate fragments, the code becomes easier to understand, manage, and extend over time.
