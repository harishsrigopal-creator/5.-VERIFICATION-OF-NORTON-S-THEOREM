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
<img width="339" height="110" alt="image" src="https://github.com/user-attachments/assets/d3dad785-08f5-4936-8e88-3f310103a0ee" />



**To measure RTh or RN**
<img width="337" height="120" alt="image" src="https://github.com/user-attachments/assets/893669f9-26bb-45c6-885b-9ad2de38b021" />




**To measure IN or Isc**
<img width="404" height="128" alt="image" src="https://github.com/user-attachments/assets/050b9723-ee84-49f8-9831-fc3c29b0d14e" />



 
**Thevenin’s equivalent circuit**
<img width="418" height="147" alt="image" src="https://github.com/user-attachments/assets/8582bc0f-b431-44b4-8bad-465eda2d22ae" />



**Norton’s equivalent circuit**
<img width="463" height="145" alt="image" src="https://github.com/user-attachments/assets/9edbae50-89b4-412a-a454-77aceb4605b5" />



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
<img width="275" height="114" alt="image" src="https://github.com/user-attachments/assets/924d6e78-3798-4e3e-88cb-50bdf5266c85" />


Vi (volts)	IL (amps)

**TABULAR COLUMN:2**

To measure RTh or RN
<img width="286" height="111" alt="image" src="https://github.com/user-attachments/assets/0f81c3ea-92be-45a3-9e28-c591af5f7c0d" />


Vi (volts)	RTh (Ω)




**TABULAR COLUMN:3**

To measure IN or Isc
<img width="257" height="139" alt="image" src="https://github.com/user-attachments/assets/0a5e9ed9-14c2-4adc-9f65-af9a58604733" />


Vi (volts)	IN (amps)
	
**MODEL CALCULATION:**

Practical value of IL (from tabulation 1) =2.3mA
<img width="395" height="248" alt="image" src="https://github.com/user-attachments/assets/19dca585-567d-49ec-b00a-1ebbbd5fd9c0" />




**Verification of Norton’s theorem**

IL = IN * RN / ( RN+ RL ) = 2.43mA
<img width="270" height="373" alt="image" src="https://github.com/user-attachments/assets/96f757f2-385d-430c-97e7-caec7d629a09" />


Theoretical calculation of IL ,IN and RTh(RN) for the given circuit:
 


**RESULT:**

Thus Thevenin’s and Norton’s theorem is verified practically and theoretically.
