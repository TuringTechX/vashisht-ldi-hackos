<h1 align="center">
  <img src="https://github.com/TharunBalaji2004/vashisht-ldi-hackos/assets/95350584/5eb57991-768e-433f-a602-1e19293eae18" alt="TRAZ Logo" width="50%" height="50%" />
  <div>
    <h5>Unlocking the future of Supply Chain System 📦</h5>
  </div>
</h1>

## Team Members

<div>
  <p>Team Number: <b>VH002</b></p>
  <p>Team Name: <b>LDI HACKOS</b></p>
</div>

| Name | Role | GitHub Profile |
| :----: | :----: | :----: |
| Tharun Balaji R | Blockchain & Backend | [TharunBalaji2004](https://github.com/TharunBalaji2004) |
| Tharun R | Blockchain Development | [TharunR222](https://github.com/TharunR222) |
| Sriram RS | Blockchain Development | [SRIRAM-001](https://github.com/SRIRAM-001) |
| Keerthana S | UI & Frontend | [keerthana054](https://github.com/keerthana054) |

Special thanks ❤️ to all Team members, for their effort and dedication towards building the project!

## Problem Statement

The opacity of global **supply chains** hinders traceability, informed decision-making and perpetuating unethical practices. This lack of **transparency** contributes to **counterfeit** goods, hidden environmental impacts, and erodes consumer trust in product **authenticity** and ethical sourcing.
We have categorized the problem into three aspects:

1. **Untraceable Supply Chains:** In today's global marketplace, supply chains are often convoluted, with **50-60%** of producers and consumers facing challenges in tracing the journey of products from source to shelf. 

2. **Counterfeit of goods:** Growing consumer concerns about product authenticity and ethical sourcing face a significant challenge due to the opaque nature of many supply chains, leading to an estimated **35%** rise in counterfeit good. (Eg) Fake Nike shoes, etc

3. **Customer Distrust:** The absence of **reliable** information about product origins, manufacturing, and fair trade has significantly eroded brand trust, causing around **70-85%** of consumers to hesitate in making purchases.

## Project Usecases

Imagine a consumer, Sarah, wants to purchase a new smartphone. Concerned about ethical sourcing and product authenticity, she scans the QR code on the phone's packaging. Instantly, she accesses the Blockchain-powered platform, where she sees detailed information about the phone's journey, from raw materials to manufacturing to distribution. Seeing the transparent supply chain and adherence to ethical practices, Sarah confidently makes the purchase, knowing she's supporting a responsible brand.

**Benefits:**
- **Enhanced Transparency:** Every stakeholder in the supply chain gains visibility into the product journey, fostering trust and accountability.
- **Mitigated Counterfeiting:** Blockchain's tamper-proof features prevent counterfeit goods from infiltrating the market, safeguarding consumers and brands alike.
- **Consumer Empowerment:** Access to detailed product information empowers consumers to make informed, ethical purchasing decisions, driving demand for transparent supply chains.

## Challenges faced 

During the project building phase, we encountered certain challenges such as:

- **Integration Complexity:** Integrating Blockchain technology with supply chain system was quite challenging and migrating smart contracts. We tackled this challenge, by thorough planning and co-ordination to ensure seamless integration by testing with our local system blockchain network.
- **Scalability:** Blockchain networks must handle large volumes of data transactions efficiently to support real-time tracking and traceability in supply chains. We were able to adopt certain compression and encoding techniques to store data with efficiently and perform transactions.

## Project Images
### 1. Website Dashboard (for Owners)

| 1) TRAZ: HomePage |  
| :---: |
| <img src="https://github.com/TharunBalaji2004/vashisht-ldi-hackos/assets/95350584/f616d891-c835-4833-8c7d-5debb98af5d5" alt="1" height="450px" width="900" /> | 

| 2) TRAZ: RolesPage - Owner assigns roles to authorities |  
| :---: |
| <img src="https://github.com/TharunBalaji2004/vashisht-ldi-hackos/assets/95350584/06f2dca6-1694-473c-acda-7544b7b92432" alt="2" height="450px" width="900px" /> | 

| 3) TRAZ: ProductsPage - Owner creates product to supply chain |  
| :---: |
| <img src="https://github.com/TharunBalaji2004/vashisht-ldi-hackos/assets/95350584/5663d325-adb7-4341-a642-41c0c77abad7" alt="3" height="450px" width="900px" /> | 

| 4) TRAZ: SupplyPage - Updating product journey at each stage |  
| :---: |
| <img src="https://github.com/TharunBalaji2004/vashisht-ldi-hackos/assets/95350584/0bf4f59f-0efe-45f7-833e-ec8f3321c870" alt="4" height="450px" width="900px" /> | 

| 5) TRAZ: TrackPage - Owner/Consumer can track the product journey |  
| :---: |
| <img src="https://github.com/TharunBalaji2004/vashisht-ldi-hackos/assets/95350584/1147f30d-8ee4-4f21-b5e0-09cfb5ba3cf2" alt="5" height="450px" width="900px" /> | 

### 2. Mobile Application (for Consumers)

| QR Code Scanning | QR Code Results |
|:---:|:----:|
| <img src="https://github.com/TharunBalaji2004/vashisht-ldi-hackos/assets/95350584/7f0c951f-4b01-49c3-b199-c952ca974547" height="1000px" width="520px" /> | <img src="https://github.com/TharunBalaji2004/vashisht-ldi-hackos/assets/95350584/d8c1539f-9e5f-4204-862a-60b75f30a0d2" height="1000px" width="520px" /> |

## Project Steps

#### Step 1
Clone the github repo and open root directory
```bash
git clone https://github.com/TharunBalaji2004/vashisht-ldi-hackos.git
cd supply-chain-truffle-react
```

#### Step 2
Open ganache UI/CLI and create sample local Ethereum blockchain network, also configure the truffle-config.js

#### Step 3
Inside the root directory, compile and deploy the smart contracts
```bash
npx truffle compile
npx truffle migrate
```
> NOTE: If you make changes in the smart contract you have to redeploy it using `npx truffle migrate --reset`

#### Step 4
After deploying smart contract, install modules in `client` folder
```bash
cd client
npm install
```

#### Step 5
Start the development server to run frontend website dashboard
```bash
npm run start
```



