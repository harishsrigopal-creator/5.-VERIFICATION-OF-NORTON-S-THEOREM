# 5.VERIFICATION-OF-NORTON-S-THEOREM

**AIM:**

To verify Norton’s theorem practically and theoretically for the given DC circuit.

**APPARATUS REQUIRED:**

1.	Regulated Power supply ( RPS)	(0-30 V)	1
2.	Voltmeter	(0-30 V) MC	1
3.	Ammeter	( 0 - 10 mA) MC	1
4.	Resistors	470 Ω 560 Ω 1 K Ω	2 1 1
5.	Bread board	---	1
6.	Multimeter	---	1

**THEORY:**

**NORTON’S THEOREM:**

Norton’s theorem states that, ‘a linear two-terminal circuit can be replaced by an equivalent circuit consisting of a current source, IN (=Isc) in parallel with a resistor RN (= RTh), where IN (=Isc) is the short-circuit current through the load terminals and RN is the equivalent resistance at the load terminals when the independent sources are turned off.Norton’s Current, IN or Isc:
It is the short-circuit current through the load terminals. i.e., IN = Isc

Norton’s Resistance, RN:It is the look-back resistance across the load terminals when all the sources are replaced by their internal resistances. An ideal voltage source is replaced by short- circuiting as its internal resistance is zero. An ideal current source is replaced by open- circuiting as its internal resistance is infinity.
 
**CIRCUIT DIAGRAM: VERIFICATION OF NORTON’S THEOREM**

**To measure IL**
<img width="334" height="125" alt="image" src="https://github.com/user-attachments/assets/a1e655c5-7e8a-42e1-997c-7b3ce8d164d2" />



**To measure RTh or RN**
<img width="367" height="125" alt="image" src="https://github.com/user-attachments/assets/b5c33327-5254-414f-b5cf-482951dfc74d" />




**To measure IN or Isc**
<img width="367" height="149" alt="image" src="https://github.com/user-attachments/assets/f3405aa2-638f-46e6-9cce-63823232121f" />


 
**Thevenin’s equivalent circuit**
<img width="446" height="149" alt="image" src="https://github.com/user-attachments/assets/966cb941-bf60-44ab-ba24-573499735ce6" />



**Norton’s equivalent circuit**
<img width="451" height="166" alt="image" src="https://github.com/user-attachments/assets/c62bea53-7517-40e7-ac06-9fdb56dda723" />



**PROCEDURE:**

1.	Make the connections as per the Circuit Diagram:1

2.	Vary the RPS and set an input voltage of 10V.

3.	Note down the voltmeter reading (Vi) and ammeter reading (IL) in Tabular Column 1.

4.	Switch off the supply and make connections for Circuit Diagram 2.

5.	Measure the Thevenin’s resistance RTh= Norton’s resistance RN .

6.	Switch off the supply and make connections for Circuit Diagram:3.

7.	Set an input voltage of 10V in the RPS and note down the voltmeter readings Vi and VTh(=Voc) in Tabular Column:3

8.	Switch off the supply and make connections for Circuit Diagram 4.

9.	Set an input voltage of 10V in the RPS and note down the voltmeter reading Vi and Ammeter reading IN (= Isc) in Tabular Column 4.

10.	Draw the Thevenin’s equivalent circuit and Nortons’s equivalent circuit as shown in circuit diagrams 5 & 6 respectively.

11.	Calculate the IL value using the formula

   	Thevenin’s Theorem IL = VTh/ ( RTh+ R L)

   	Norton’s Theorem IL = IN * RN / ( RN + RL )

12.	Theoretically verify the Norton’s theorem.

**TABULAR COLUMN: 1**
To measure I L
<img width="290" height="119" alt="image" src="https://github.com/user-attachments/assets/2da34c5c-7fa5-44c6-9bed-729cdf993303" />


Vi (volts)	IL (amps)

**TABULAR COLUMN:2**

To measure RTh or RN
<img width="297" height="119" alt="image" src="https://github.com/user-attachments/assets/98405428-b8d9-4f31-9737-ed7dcb0e3bbf" />

Vi (volts)	RTh (Ω)


**TABULAR COLUMN:3**

To measure IN or Isc
<img width="248" height="122" alt="image" src="https://github.com/user-attachments/assets/7ceb6294-a085-4daf-8f9f-82ab81e5caa3" />


Vi (volts)	IN (amps)
	
**MODEL CALCULATION:**
<img width="365" height="250" alt="image" src="https://github.com/user-attachments/assets/01064151-588c-4e93-8661-0f0d16f95d48" />

Practical value of IL (from tabulation 1) =2.3mA

**Verification of Norton’s theorem**

IL = IN * RN / ( RN+ RL ) = 2.43mA

Theoretical calculation of IL ,IN and RTh(RN) for the given circuit:
<img width="277" height="413" alt="image" src="https://github.com/user-attachments/assets/a7637809-18e8-4d9a-b9f0-46c4d7aac0d0" />

 


**RESULT:**

Thus Thevenin’s and Norton’s theorem is verified practically and theoretically.
