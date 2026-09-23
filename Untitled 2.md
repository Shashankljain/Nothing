```mermaid

flowchart TD
Disease / RUQ Pain] ::: primary --&gt; B[Initial Imaging: Abdominal Ultrasound USG] ::: primary B --&gt; C{USG Findings} ::: warning C --&gt;|Gallstones in Gallbladder| D[Cholelithiasis Identified] ::: primary C --&gt;|CBD Dilatation / CBD Stone| E[Obstructive Biliary Disease] ::: danger D --&gt; F{Symptomatic Status} ::: warning F --&gt;|Symptomatic / Cholecystitis| G[Indication for Surgery] ::: danger F --&gt;|Asymptomatic| H[Conservative Monitoring] ::: success G --&gt; I[Laparoscopic Cholecystectomy] ::: success E --&gt; K[Non-Invasive Imaging: MRCP / EUS] ::: primary K --&gt; L[Therapeutic Intervention: ERCP] ::: primary L --&gt; M[Sphincterotomy &amp; Basket Retrieval / Stenting] ::: success M --&gt; N[Elective Laparoscopic Cholecystectomy] ::: success 
```
