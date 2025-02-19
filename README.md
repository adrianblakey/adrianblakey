# Welcome to Adrian (Arseny) and Richard's Technologies

This is the home of the Remora Electronic Commutators (eCom) for slot car brushless motors. This will also be the place where we'll list some other things we've been working on.

eCom's are little electronic gizmos that you need to run a brushless motor in a slot car. 

What's really good about the Remora is that with a little effort you can make one yourself if you don't want to buy one.

If you want to read more about the Remora1 read the [Getting Started](https://github.com/adrianblakey/slot-car-ecom/wiki/Getting-Started) on the WiKi.

## The 22,500K<sub>v</sub> "AART" Motor

We have a limited supply of very competetive motors for sale. A couple of well-known racers have used them and been quite successful in eurosport and unlimited club racing events. They run and brake well with a Remora1. We owe a lot of thanks to Martin Ellis for help with the design.

<img src="/assets/images/aart-motor-sideon.jpeg" style="width: 35vw; min-width: 200px;">

<img src="/assets/images/aart-motor-shaft.jpeg" style="width: 35vw; min-width: 200px;">

These are "1105", 6 magnet motors with an overall diameter of 13.68mm (.5395"), and a 1.5mm shaft, with 110mm lead wires. They fit comfortably next to a 3/32" axle with 5:40 72p gearing. They are 9N6P - six magnet motors. They have 5 turns of 0.38mm wire with Delta termination. The wire diameter is 0.015” or 0.38mm which is half way between 27awg and 26awg.

For those of you with Ron Kiddell's motors: Ron's assessment: "Your shell size is 13.7mm outer and 12.2mm inner with 1.1mm magnet thickness. Mine is 13.9mm outer and 12.6mm inner giving a magnet thickness of 1.3mm. Your shell thickness .5 and mine .3." The stator sizes are the same.

This was our working drawing. The dimensions differ because of the paint :-)

<img src="/assets/images/aart-motor.png" style="width: 35vw; min-width: 200px;">

They need a bit of effort to install properly, namely: Either; very carefully use a dremel wheel to grind off a few thou. around the circlip that locates the shaft so that it clears the motor mounting bracket or: use a dremel tool to enlarge the motor bracket (probably not a good idea) or: remove the circlip and slide on a 2mm diameter washer to the motor shaft followed by a very short (~1mm) piece of aluminium tubing (K S tubing, part: KS8101 has an internal diameter of 1.67mm) to space it out to the back of the pinion.

We have some ideas about how to improve this design to make them even better - [want to help?](mailto:sales@aart.dev?subject=[AART Motor])

We can offer them at £22/€27/$28 each.

## The Remora1

The is the world's best eCom. It beats the competition hands down by being the fastest, cheapest, most robust, and most flexible eCom you can buy. It can commutate all motors ranging in performance from 2,000K<sub>v</sub> up to 22,500K<sub>v</sub>+. The same board can do it all. 

If you are using a high K<sub>v</sub> motors (say 17,000K<sub>v</sub> and above) you might need to make a couple of simple configuration changes - but that's not hard because [there's plenty of help](https://github.com/adrianblakey/slot-car-ecom/wiki/Getting-Started) on the WiKi.

All the information you might want is on the [github WiKi.](https://github.com/adrianblakey/slot-car-ecom/wiki)

### The Hardware

The hardware design is open source. You'll find all of it in this [git hub repo](https://github.com/adrianblakey/slot-car-ecom).

The schematic and board design were all done using [KiCad](https://github.com/adrianblakey/slot-car-ecom) and the production files are all in the repo.

### The Software

The board needs firmware to run. We use an open source product called [ESCape32](https://github.com/adrianblakey/slot-car-ecom). This is exceptional code designed to run a variety of Electronic Speed Controllers very efficiently. It's actively maintained and there's always a [current release](https://github.com/neoxic/ESCape32/releases) for the Remora.

### Purchasing One 

We sell:  

The ***Remora1.2*** - this is the latest revision of the board. It's a slight improvement over the first release by using better Field Effect Transistors(fets) and manufactured on a thinner (.8mm) board with more expensive gold metal plated contacts. It's supplied flashed with the latest version of the ESCape32 binary. This will work right out of the box. Solder on the leads and motor wires and off you go.   

The ***WiFi Link*** - fully flashed with the latest 1.2 firmware. This allows you to set all the parameters of an eCom. This comes with a small cable to attach it to the Remora1 and a bent crocodile clip that you'll find useful for extracting the connector from the eCom. You'll only ever need one of these.  

### Retail Pricing

Remora1.2 - US pricing $40, UK pricing £30, EU pricing €35 <img src="/assets/images/1-top.jpeg" style="width: 35vw; min-width: 200px;"> <img src="/assets/images/1-bot.jpeg" style="width: 35vw; min-width: 200px;"> 

WiFi Link (with enclosure, wire and clip) - US pricing $22, UK pricing £17, EU €20 <img src="/assets/images/wifi-link.jpg" style="width: 35vw; min-width: 200px;">

Replacement WiFi Link enclosure - US $3, UK £1.50, EU €2     

Replacement WiFi link cable (check the WiKi for a better suply). US $2.50, UK £1.50, EU €2  

Replacement WiFi link Adapter for an ESP32 S2 mini. US $8, UK £5, EU €6 <img src="/assets/images/aart-adapter.jpg" style="width: 35vw; min-width: 200;"> 

Replacement Crocodile clip. US $1.25, UK £.80, EU €1 <img src="/assets/images/croc.jpg" style="width: 35vw; min-width: 200px;">  

3D-printed Remora1 board carrier - ask.    

### Ordering

If you would like to order any of these parts, please send us email to: [Sales](mailto:sales@aart.dev?subject=[Purchase please]) In the body of the email please put:

  Your full name.   
  Your email address (if it's different from the one you're send this from).    
  Your phone number.   
  Your shipping address.   
  The part(s) you'd like to order, and the quantity.   
  Your shipping preference (special, first, second, tracked, signed). 
  
  Note: The parts usually fit in a Royal Mail "large letter". Domestic special delivery is ~£7.35, first class is ~£2.10 (to give you an idea).

Perhaps needless to say, we do not sell your information.

### The Process

We'll respond to you by email with an order number, quoting a price for the parts, plus shipping and the lead time. There is a chance that we might not have enough inventory to ship you the parts immediately, if so we'll tell you what we can do, either split the shipment or wait till we have them.

If you agree - then please reply affirming the order. If not, tell us why you're rejecting the quote (e.g. cost, lead time etc.) we'd like to hear why you changed your mind so we can improve our service.

If you affirm the order, we'll send you an invoice request to pay either by PayPal™, or by direct debit (UK). If you elect to use PayPal™, We ask that you send the funds - "friends and family". 

### Inquiries

If you have any inquiries about anything, please [send us email](mailto:sales@aart.dev?subject=[Inquiry]) and just ask. We are happy to answer any questions. You might for example want to also give us a heads up when you might like to place an order in the future to help our planning.

### Disclaimers

Please be persistent in your attempts to get in touch. This is not our day job but a hobby and we might be enjoying ourselves. We believe in providing the best service possible and we will replace any parts you think are bad. If you need help in a hurry get on the [ESCape32 Discord server, slot car channel](https://discord.com/channels/1103745257046278144/1151565789984469144).
