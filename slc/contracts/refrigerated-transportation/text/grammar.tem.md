# Contract for the Supply and Delivery of Refrigerated Goods

This Contract for the Supply and Delivery of Refrigerated Goods ("Contract") is entered into between {{ buyer }} of {{ buyerLocation }} represented by {{ buyerRepresentant }} referred to as the Buyer, and {{ supplier }} of {{ supplierLocation }} represented by {{ supplierRepresentant }} referred to as the Supplier. 

## 1. Electronic signatures and Blockchain Smart Contract

1.1 The Contract is binded to a Blockchain Smart Contract, referred as the BSC. The BSC will record agreements accordingly to this contract, in an immutable way. The BSC is stored on the Ethereum blockchain, identified by its Public address {{ bscPubAddress }}.

1.2 The Buyer and the Supplier will use a pair of Public and Private keys as electronic signatures to authenticate their agreements through the execution of this Contract, on the BSC, and to sign this Contract. The Private key will serve to sign agreements, and the Public key will identify the agreements of the Buyer and the Supplier. Each party agrees that the electronic signatures, whether digital or encrypted, of the parties included in this Contract and on the BSC are intended to have the same force and effect as manual signatures. 

Hereafter, the Buyer will be associated with the Public key {{ buyerPubKey }} and the Supplier will be associated with the Public key {{ supplierPubKey }}.

## 2. Goods supplied

2.1 The Supplier agrees to supply to the Buyer the Goods in strict accordance with the specifications and at the price stated for each item outlined below:

{{#ulist products}}
{{ id }}: {{ desc }}, {{ qt }} units x {{ unitPrice }}€ = {{ totalPrice }}€
{{/ulist}}

## 3. Charges and Payment

3.1 The total Price for the supply and delivery of the Goods under this Contract is {{ orderPrice }} ({{ orderPriceLitteral }}).

3.2 The Buyer must confirm or deny the good condition and order conformance of the Goods delivered in {{ daysToAgreement }} days. Otherwise, the payment shall become due to the Seller whatever the condition of the Goods delivered.

3.3 The Supplier shall invoice the Buyer on delivery of the Goods in accordance with this Contract and payment shall become due {{ daysToPayment }} calendar days after acceptation by the Buyer of the Goods. 

3.4 Payments shall be made in {{ orderCurrency }} by bank transfer to the following bank account of the Supplier: {{ supplierBankInfo }}.

## 4. Delivery

4.1 The Goods shall be delivered to: {{ deliveryPointLocation }} {{ daysToDelivery }} days after the signature of the Contract. Cost of delivery is deemed included in the Price specified in clause 3.1 of this Contract. If the Goods are delivered late, Buyer is entitled to claim a penalty up to {{lateDeliveryPenaltyRatio }}% of the Contract price.

4.2 The Goods must be stored and transported under {{ maxTemperature }}. A Sensor, provided by the Buyer and identified by the public key {{ devicePubKey }}, will monitor the temperature of the Goods during the transportation and inform the Buyer and the Supplier if the temperature excess this threshold.  

4.3 If the Goods are exposed to a temperature higher than the defined threshold in clause 4.2, the Buyer is entitled to terminate the contract with no cost.

4.4 The Buyer acknowledges that the Sensor is not compromised, altered, broken, or attached to the Goods in a way that could alter its correct functioning. 

## 5. Mediation

5.1 {{ mediator }} of {{ mediatorLocation }}, represented by {{ mediatorRepresentant }} and associated with the public key {{ mediatorPubKey }} referred to as the Mediator, will arbitrate if conflicts of any type occurs during the execution of this contract.

Buyer electronic signature: {{ buyerSignature }}
Supplier electronic signature: {{ supplierSignature }}