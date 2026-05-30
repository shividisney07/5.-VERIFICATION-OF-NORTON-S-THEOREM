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
<img width="758" height="577" alt="image" src="https://github.com/user-attachments/assets/6e51c043-3940-413b-8854-9131f0524f4b" />



**To measure RTh or RN**
<img width="1607" height="642" alt="image" src="https://github.com/user-attachments/assets/9fc83c04-9b19-43ce-99f3-55aeaf19cf1a" />




**To measure IN or Isc**
<img width="1256" height="544" alt="image" src="https://github.com/user-attachments/assets/c745787e-9c71-4d62-8bf8-1746524aa1fb" />


 
**Thevenin’s equivalent circuit**
<img width="692" height="434" alt="image" src="https://github.com/user-attachments/assets/12d84174-92d4-4d75-aa69-eeadbae52d4a" />



**Norton’s equivalent circuit**
<img width="703" height="442" alt="image" src="https://github.com/user-attachments/assets/482c8aaf-ae45-4ef5-9d87-a7da1c079619" />



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
<img width="1104" height="488" alt="image" src="https://github.com/user-attachments/assets/3a1d7810-c372-45f0-99f1-2df05ba01354" />


Vi (volts)	IL (amps)

**TABULAR COLUMN:2**

To measure RTh or RN
<img width="1268" height="539" alt="image" src="https://github.com/user-attachments/assets/d9cd24fa-2b68-4950-ab06-7a3cafbb6d23" />


Vi (volts)	RTh (Ω)


**TABULAR COLUMN:3**

To measure IN or Isc
<img width="1363" height="491" alt="image" src="https://github.com/user-attachments/assets/7c6dd8fa-c4ce-4865-8b84-aaa7480a0544" />


Vi (volts)	IN (amps)
	
**MODEL CALCULATION:**

Practical value of IL (from tabulation 1) =2.9mA

**Verification of Norton’s theorem**

IL = IN * RN / ( RN+ RL ) = 2.77mA

Theoretical calculation of IL ,IN and RTh(RN) for the given circuit:
<img width="630" height="634" alt="image" src="https://github.com/user-attachments/assets/6df7dbaf-61c7-459c-ac53-04b0296b670e" />
<img width="898" height="611" alt="image" src="https://github.com/user-attachments/assets/dbca1c51-3bda-4526-b1e8-2aaef6b469b3" />
<img width="443" height="507" alt="image" src="https://github.com/user-attachments/assets/4b5295c6-8ba1-494a-a6ca-7064e9db8cdb" />

 


**RESULT:**
      Thus Nortons theorem is verified practically and theoretically.


