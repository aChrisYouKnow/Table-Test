# ComparisonTables (*working title*)

Welcome to **ComparisonTables** – a repository dedicated to creating and maintaining comparison tables for a wide range of topics, including software, hardware, services, and more. The goal is to provide up-to-date, comprehensive, and easy-to-navigate tables to help make informed decisions.

## About the Tables

These tables cover various categories and are designed to be comprehensive and user-friendly. Given the nature of the data, some tables may be extensive and are best viewed on larger screens. It may be post effective to copy and paste these tables into a spreadsheet for sorting and filtering as your need dictates. 

### Example Table: Lightning Wallet Comparison 
  Notes:
  - I think a more selective use of colored circles may be more effective. I plan to circle back here to experiement with that. 
  - Keeping the columns narrow and moving longer notes/comments to below the table (via links?) may be a better option. Play around with options there.
  - Turn all wallet names into links to main websites

Wallet   |  Custodial?  |  OS               |  Channel Open Fees                           |  Liquidity Provider?  |  Lightning Tx Fees  |  Open Source  |  Notes / Trade Offs
----------|--------------|-------------------|----------------------------------------------|-----------------------|---------------------|---------------|----------------------------------------------
Cash App  |  🔴 Yes       |  🟢 iOS/ Android  |  🟢 N/A                                       |  🟢 N/A                |  🟢 Free             |  🟠 No         |  🟠 Full KYC, 🟠 not available in all states
Primal    |  🔴 Yes       |  🟠 iOS only            |  🟢 N/A                                       |  🟢 N/A                |  🟢 ~0-5 sats        |  🟢 Yes        |  🟠 Paired with Nostr Client
Muun      |  🟢 No        |  🟢 iOS/ Android  |  🟢 N/A                                       |  🟢 N/A                |  🔴 On-Chain Fees    |  🟢 Yes        |  🟡 Stores Bitcoin On-Chain, 🟢 Easy to use
Aqua      |  🟢 No        |  🟢 iOS/ Android  |  🟢 N/A                                       |  🟢 N/A                |  🟠 ~500 sats        |  🟠 No         |  🟡 Stores Bitcoin on Liquid and can be slow
Breez     |  🟢 No        |  🟢 iOS/ Android  |  🟡 0.4% or On-Chain Fees                     |  🟢 Yes (50k sats)     |  🟢 ~0-5 sats        |  🟢 Yes        |  🟡 Uses Greenlight (Less Stable?)
Zeus      |  🟢 No        |  🟢 iOS/ Android  |  🟡 10k sats or On-Chain Fees                 |  🟢 Yes (80k sats)     |  🟢 ~0-2 sats        |  🟢 Yes        |  🟡 Slow to Open / Load, 🟢 Non-custodial lightning address
Blixt     |  🟢 No        |  🟢 iOS/ Android  |  🟡 On-Chain Fees or 6850 sats (Lightning)    |  🟢 Yes (Dunder LSP)   |  🟢 ~0-5 sats        |  🟢 Yes        |  🟡 Lightning Channel Open Still Buggy
Mutiny    |  🟢 No        |  🟢/🟡 PWA          |  🟡 40k sats (On-Chain) 15k sats (Lightning)  |  🟢 Yes (100k sats)    |  🟢 ~0-5 sats        |  🟢 Yes        |  🟡 App Must be Open to Send / Receive, 🟢 Nostr Wallet Auth
Phoenix   |  🟢 No        |  🟢 iOS/ Android  |  🟡 On-Chain Fees + 1000 sats (w/Splicing)  |  🟢 Yes (80k sats)     |  🟡 0.4 % + 4 sat  |  🟢 Yes        |  🟡 Slightly Higher Lightning Tx Fees, 🟢 Fast and reliable

## 🤝 How to Contribute

Your contributions keep these tables relevant and valuable. If you'd like to suggest a change or an update, please follow the [Contribution Guidelines](CONTRIBUTION.md) which includes step-by-step instructions for submitting a pull request.

## 🔄 Markdown and CSV Conversion

For simple changes, editing the .md file is probably sufficient. For larger changes, there are a number of tools to convert csv files to markdown including:
  - Simple web tool: https://csvtomd.com/
  - Python script: https://github.com/mplewis/csvtomd

## 🆕 Starting a New Comparison Table

(Instructions on starting a new table – to be added)

## 📝 Table Update Requests

(Information on how to request updates for existing tables – to be added)

## 📜 License

ComparisonTables is open source and made available under the MIT License.

Copyright (c) 2024 aChrisYouKnow

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

---

Hopefully this repository serves as a valuable resource for everyone. Looking forward to your contributions!




