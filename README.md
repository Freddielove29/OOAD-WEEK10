ภาพที่ 1 
```
@startuml
fluke ->    boss: hi Good morning
boss --> fluke: Good morning
fluke -> boss: How are you this morning?
fluke <-- boss: Find, thanks, and you? 
@enduml
```
![](http://www.plantuml.com/plantuml/img/LSv12eGm38NXVK_n3c0l88Ewqhb6fHqjQW9DYtZxQMTKCCla-o6TH1DYsbRrMTFYe1la6LcankmnC5ji7CZJfCeMEeiVhP_7E_-tRzvXWiF12N7sShdsX2-jJzbxibKsXXQfOCYMfeNg7DdornS0)

ภาพที่ 2
```
@startuml
fluke -> "Boss()" : Hello
"Boss()" -> "This is very\nlong" as Long
' You can also declare:
' "Boss()" -> Long as "This is very\nlong"
Long --> "Boss()" : ok
@enduml
```
![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuKhBASrELT2rKr1ooYykrj1KKh1Iy4ZDoSddWWk094CoCeiLWAWijQWo9YydFozTII6nMC47oE1ILuZCBrL8JinJICmfpbT8IKtEIInAjGAA8ni1KWhIWiqeBh2aBgehyhEv75BpKa2E1000)

ภาพที่ 3
```
@startuml
salesperson -> "Delivery man()" : Order items
"Delivery man()" -> "Delivery System" 
' "Delivery man()" -> Long as "Delivery System"  "Delivery man()":ok
@enduml
```
![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuIfEp4ajBaWjAixFKz2rKr1oISt9B4ijgbJ8JSpJq5HIi5BmBqf9BLB8B4dDBUR2a4RH4bnP35IbfC35nQMkW4sfJtvUka9YCHOj6CgjyhEv75BpKa1kv080)

ภาพที่ 4
```
@startuml
customers -> "postman()" : Order items
"postman()" -> "Delivery System" as Long
' You can also declare:
' "postman()" -> Long as "Delivery System"
Long --> "postman()" : Order items 
@enduml
```
![](http://www.plantuml.com/plantuml/img/VOwz2i9048JxVOhX6hN82wIG52a52olBvMu9WVkHtJiXRs_EIXHiv_jccCagQsqfaczMIn8r36UuHx6QE1zF3YEk6aInLab6dwIBiyJrARhXjjakEB3XKl921znBW-SCZbOGn4TM6VVyQwBRlVKpHMyo_Bi3cYI7Vf_e1G00)

ภาพที่ 5
```
@startuml
customers -> "ATM()" : Insert card
"ATM()" -> "keypad" as Long : press
' You can also declare:
' "ATM()" -> Long as "keypad"
Long --> "ATM()" : password is incorrect 
@enduml
```
![](http://www.plantuml.com/plantuml/img/LOwn2i8m48RtUugVBkhG5-WWTHHqSt4yaaEAQHBk4eflRreewFhnVV_TQ8Mrr3cGgrRIB6hep-WkZ_lnr670DPfeWMFrjDDLUCidi-_0XbkAhsPc5JCwu9bgqoCuM88N5rXbQFodtefMxYkqWVxlS6Qp9Qd7P9YYIwhY2cYKwDTtYRu0)




















# OOAD-WEEK10
Sequence Diagram


README.md 
md เป็นภาษา Markdown นิยมใช้ใน wiki ของ github 

ตัวอย่างโค้ด
```
# Heading ระดับ 1 
## Heading ระดับ 2
### Heading ระดับ 3
 
```

ผลที่ได้
# Heading ระดับ 1 
## Heading ระดับ 2
### Heading ระดับ 3


## Code ภาษาซี

ตัวอย่างโค้ด
<pre>
  ``` c
  #include <stdio.h>
  Main()
  {
     Printf("Hello");
  }
  ```
</pre> 
ผลที่ได้
  ``` c
  #include <stdio.h>
  Main()
  {
     Printf("Hello");
  }
  ```
 
